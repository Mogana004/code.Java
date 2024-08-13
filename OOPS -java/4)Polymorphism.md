# Polymorphism
### Polymorphism is derived from two Greek words poly and morphs. The word poly means "many" and morphs means "forms". So polymorphism means many forms.
### Polymorphism in Java refers to an object’s capacity to take several forms. Polymorphism allows us to perform the same action in multiple ways in Java.

## Polymorphism is of two types:

1) Compile-time polymorphism
2) Runtime polymorphism

## 2.1 Compile-time Polymorphism
A polymorphism that occurs during the compilation stage is known as a Compile-time polymorphism. Method overloading is an example of compile-time polymorphism.

### code 
```java
class Shapes {
    public void area(int radius) {
        System.out.println("Area of Circle = " + 3.14 * radius * radius);
    }

    public void area(double base, double height) {
        System.out.println("Area of Triangle = " + 0.5 * base * height);
    }

    public void area(int length, int breadth) {
        System.out.println("Area of Rectangle = " + length * breadth);
    }
}

class Base {
    public static void main(String[] args) {
        Shapes circle = new Shapes();
        Shapes triangle = new Shapes();
        Shapes rectangle = new Shapes();

        circle.area(10);
        triangle.area(8.5, 10.23);
        rectangle.area(5, 3);
  }
}
```

#### In the above code, we have defined multiple overloading methods with the name area which differ in their parameters. We have also invoked the same method with different numbers or types of arguments.
#### Here, compile-time polymorphism occurs and the decision of which method to be invoked for which call is done in the compilation stage.


## 2.2 Runtime Polymorphism
A polymorphism that occurs during the execution stage is called Runtime polymorphism. Method overriding is an example of Runtime polymorphism.

```java
class Mammal {
    void eat() {
        System.out.println("Mammal is eating");
    }
}

class Dog extends Mammal {
    void eat() {
        System.out.println("Dog is eating");
    }
}

class Base {
    public static void main(String args[]) {
        Mammal mammal = new Dog();
        mammal.eat();
    }
}
```

1) In the above code, we have used the superclass reference variable mammal to refer to its subclass object. We also invoked eat() method using the reference variable mammal. The method invocations with objects are resolved (i.e., deciding which method should be called by the statement mammal.eat()) during the runtime.

2) During the runtime, the mammal refers to the Dog object and the method invocation is resolved and the eat() method of the Dog class has been invoked as it overrides the eat() method of the Mammal class.
