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
