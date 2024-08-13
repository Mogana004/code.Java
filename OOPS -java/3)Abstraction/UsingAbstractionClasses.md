# Abstraction using abstract classes 
```java
abstract class Vehicle{ 
    int speed = 20 ;
    abstract void displayspeed() ;  // Abstarct method with only declaration 
}
class car extends Vehicle{ //subclass inherites abstract class Vehicle 
    void displayspeed(){
        System.out.print(this.speed) ;
    }
}

class Main {
   
    public static void main(String[] args) {
        car c = new car();
        c.displayspeed() ;
    }
}
```

# Key Points 
### Abstraction is the process of hiding certain details and showing only essential information to the user.
### Abstraction can be achieved with,

1) Abstract classes
2)  Interfaces

### A class which is declared with the abstract keyword is known as an abstract class.
however ,
1) Abstract classes cannot be instantiated i.e., we cannot create objects using the abstract classes.
2) Abstract classes can have abstract methods.
3) Abstract classes cannot be declared as final.

### Abstract Methods
A method which is declared with the abstract keyword is known as an abstract method.
* The abstract methods don't contain any implementation .
* The implementation of the abstract methods should be provided by its subclasses.
* Abstract methods cannot be private, final, etc which cannot be overridden.

 ```java
 abstract class Vehicle { // abstract class
    abstract void start(); // abstract method
    abstract void stop();  // abstract method
}
```
## 3. Implementing Abstract Classes and Methods
### 3.1 Inheriting Abstract Classes
As we cannot create objects using an abstract class, to access the members of an abstract class we have to inherit the class from another class.

```java

abstract class Vehicle {  // abstract class
    abstract void start();  // abstract method
    abstract void stop();  // abstract method
}

class Car extends Vehicle {
    void start() {  // overriding abstract method
        System.out.println("Car started");
    };

    void stop() {  // overriding abstract method
        System.out.println("Car stopped");
    };
}

class Base {
    public static void main(String[] args) {
        Car car = new Car();
        car.start();
        car.stop();
    }
}
```
### 3.2 Multilevel Inheritance with Abstraction
If the subclass of an abstract class is also an abstract class, then the subclass may or may not implement the abstract methods of its superclass.

```java
abstract class Vehicle {  // abstract class
    abstract void start();  // abstract method
    abstract void stop();  // abstract method
}

abstract class Car extends Vehicle {  // abstract class
    boolean areHeadlightsOn;

    Car() {
        areHeadlightsOn = false;
    }

    void turnOnHeadlights() {  // non-abstract method
        areHeadlightsOn = true;
    }

    void turnOffHeadlights() {  // non-abstract method
        areHeadlightsOn = false;
    }

    abstract void applyHandbrake();  // declared another abstract method

}

class Ferrari extends Car {
    void start() {  // implementing start() method
        System.out.println("Ferrari started");
    }

    void stop() {  // implementing stop() method
        System.out.println("Ferrari stopped");
    }

    void applyHandbrake() {  // implementing applyHandbrake() method
        System.out.println("Ferrari handbrake applied");
    }
}

class Base {
    public static void main(String[] args) {
        Ferrari ferrari = new Ferrari();
        ferrari.start();
        ferrari.stop();
        ferrari.turnOnHeadlights();
        System.out.println("Are headlights turned on: " + ferrari.areHeadlightsOn);
        ferrari.applyHandbrake();
    }
}
```
### output 
- Ferrari started
- Ferrari stopped
- Are headlights turned on: true
- Ferrari handbrake appl
