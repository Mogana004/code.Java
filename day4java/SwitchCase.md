
```java
import java.util.Scanner;

class HelloWorld {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter number1 :");
        int a = sc.nextInt();
     
         System.out.print("Enter number2 :");
        int b = sc.nextInt();
     
        System.out.print("Enter you choice(+,-, *, /, ):");
        char choice = sc.next().charAt(0);
        switch (choice) {
            case '+' :
                int add = a+b;
                System.out.print("addision value is :" + add);
                break;
             case '-' :
                 int sub= a-b;
                 System.out.print("subtraction value is :" + sub);
                 break;
                 
            case '*' :
                int multiply = a* b ;
                System.out.print("multiplication value is :" + multiply); 
                break;
            case '/' :
                int division = a /b;
                System.out.print("division value is :" + division);
                break;
            default:
            System.out.print("Invalid");
            break;
        }
   
    }
}
```


![image](https://github.com/Mogana004/code.Java/assets/92911280/3aaf89c0-82f7-492c-acc4-64a75a059d50)
