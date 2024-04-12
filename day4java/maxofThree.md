![image](https://github.com/Mogana004/code.Java/assets/92911280/259cfd79-20b2-4816-9c41-228913d8482d)
## code
```java
import java.util.Scanner;

class HelloWorld {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
       
        System.out.print("Enter number1:");
        int num1= sc.nextInt();
        System.out.print("Enter number2:");
        int num2= sc.nextInt();
        System.out.print("Enter number3:");
        int num3 =sc.nextInt();
        int  max = num1;
        if (num2 >num1) {
            max= num2;
        } if (num3 >num2){
            max= num3; 
        }
        System.out.print("Maximum :" + max);
        
       
        
    }
}
```
