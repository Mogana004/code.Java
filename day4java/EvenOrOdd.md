```java
import java.util.Scanner;

class HelloWorld {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
       
        System.out.print("Enter a number:");
        int num= sc.nextInt(); 
        if (num%2 ==0){
            System.out.println("Even");
        }else{
            System.out.println("Odd");
        }
        
    }
}
```
