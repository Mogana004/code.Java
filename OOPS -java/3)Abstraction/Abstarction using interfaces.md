1) We learned to use abstract classes to achieve abstraction.In this , we'll learn Interfaces.
2) syntax :
 interface InterfaceName {
    // body of the interface
}

```java
//inplementing abstraction using interfaces 

interface Vehicle{
    int maxSpeed = 150 ; // attribute 
    void start() ; //abstract method with only declaration 
    void stop() ; //abstract method with only declaration
    
}
class Car implements Vehicle {
    public void start(){ //implementation of abstract menthod 
        System.out.println("Car Strated") ; 
        
    }
    public void stop(){ //implementation of abstract menthod 
        System.out.println("Car stopped") ;
        
    }
}
class Main {
    public static void main(String[] args) {
        Car c = new Car() ;
        System.out.println(c.maxSpeed) ;
        c.start() ;
        c.stop() ;
        
    }
}
```

### inheritace amoung intefaces
```java
```java
interface CricketPlayer {
    void run();
    void field();
}

interface Wicketkeeper extends CricketPlayer {  // interface extending another interface
    void wicketkeeping();
}

class Person implements Wicketkeeper {
    public void field() {
        System.out.println("Fielding");
    };

    public void wicketkeeping() {
        System.out.println("Wicketkeeping");
    }

    public void run() {
        System.out.println("Running");
    };
}

class Base {
    public static void main(String[] args) {
        Person person = new Person();

        person.field();
        person.wicketkeeping();
        person.run();
    }
}
```
![image](https://github.com/user-attachments/assets/1910620a-6018-4253-8cee-4f19aeda20d1)

### 4. Multiple Inheritance
In multiple inheritance, a single class/interface can inherit multiple interfaces.
```java
interface InswingBowler {
    void inswing();
}

interface OutswingBowler {
    void outswing();
}

class BowlerA implements InswingBowler, OutswingBowler {  // a class implementing multiple interfaces
    public void inswing() {
        System.out.println("Inswing bowling");
    }

    public void outswing() {
        System.out.println("Outswing bowling");
    }
}

class Base {
    public static void main(String[] args) {
        BowlerA bowler = new BowlerA();
        bowler.inswing();
        bowler.outswing();
    }
}```
