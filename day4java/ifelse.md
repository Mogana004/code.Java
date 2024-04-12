![image](https://github.com/Mogana004/code.Java/assets/92911280/1f5b7ff0-eba9-4e53-8110-b8faf8d15116)

## Question
Get age from user and if the age is below 15 print “give Chocolate!”. Finally print “bye”.

Sample Output1:
	Enter Your Age : 12
	Give Chocolate!
	Bye
Sample Output2:
	Enter Your Age : 20
	Bye



## code
```java
import java.util.Scanner;

class HelloWorld {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
       
        System.out.print("Enter Your age:");
        int age = sc.nextInt(); 
        if (age<=15){
            System.out.println("Give Chocolate!");
        }
        System.out.print("Bye");
    }
}
```
