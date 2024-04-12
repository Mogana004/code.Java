![image](https://github.com/Mogana004/code.Java/assets/92911280/152f81e7-05b3-4766-8f79-53f17792c726)
### CODE 
```java
import java.util.Scanner;
class HelloWorld {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
       
        System.out.print("Enter Your Name:");
        String Name = sc.next();
        
        
        System.out.print("Enter Your Initial:");
        String Initial = sc.next();
        
        
        System.out.print("Enter Your Dept:");
        String Dept = sc.next();
        
        System.out.print("Enter Your Age:");
        int Age = sc.nextInt();
        
        System.out.print("Enter Your CGPA:");
        double CGPA = sc.nextDouble();
        
       System.out.println("Details You Entered:");
        System.out.println("Your Name: " + Name);
        System.out.println("Your Initial: " + Initial);
        System.out.println("Your Dept: " + Dept);
        System.out.println("Your Age: " + Age);
        System.out.println("Your CGPA: " + CGPA);

        sc.close();
       
    }
    
}
```
