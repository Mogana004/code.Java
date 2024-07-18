```java

//super class - product 
class product {
    // instance attributes

    String name ;
    int price ;
    float rating ;

    // consturctor method to access the values 
    product (String name , int price , float rating ){
        this.name = name ;
        this.price = price ;
        this.rating = rating ;
        
    }
    // instance method 
    void displayValues(){
        System.out.printf("product name : %s\n" , this.name);
        System.out.printf("product price : %d\n" , this.price);
        System.out.printf("rating : %.1f\n",  this.rating) ;
    }
    
}

// sub class (or) child class - grocery 
class grocery extends product{ // extend - keyword to extend the super class (parent class)
    grocery(String name , int price , float rating ){
        super(name , price , rating ) ; // super keyword - used to extend the contructor methods defined in parent class .
    } 
    
    // method overriding - bcoz its same as defined in the super class 
    void displayValues(){
        System.out.printf("product name : %s\n" , this.name);
        System.out.printf("product price : %d\n" , this.price);
        System.out.printf("rating : %.1f\n",  this.rating) ;
    }
    
}
class Main {
    public static void main(String[] args) {
        // creating object to define the values 
        product p1 = new product("milk packet" , 105 , 5);
        p1.displayValues() ;
        // creating object for the sub class - grocery 
        grocery g1 = new grocery("biscket" , 23 , 5);
        g1.displayValues() ;
    }
}
```

## inheritance 
Inheritance in Java allows a new class to inherit fields and methods from an existing class, promoting code reusability and establishing a hierarchical relationship between classes. The existing class is called the superclass (or parent class), and the new class is called the subclass (or child class).

## method overriding 
Method overriding in Java occurs when a subclass provides a specific implementation of a method that is already defined in its superclass. The method in the subclass must have the same name, return type, and parameters as the method in the superclass. Method overriding allows a subclass to offer its own version of a method, providing specific behavior for subclass instances.
