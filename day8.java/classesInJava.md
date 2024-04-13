
```java
class Rectangle{ //defining a class
    int width;
    int height;
    Rectangle (int width , int height){ //constructor method 
        this.width = width; //accessing instances and assigning values to the class variables
        this.height= height ;
        
    }
}
class Main {
    public static void main(String[] args) {
        Rectangle rect = new Rectangle(20 , 30); // type of the variable "rect" is the class name itself.
        System.out.println(rect.width);
        System.out.println(rect.height);
    }
}
```
