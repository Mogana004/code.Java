![image](https://github.com/Mogana004/code.Java/assets/92911280/c5b9caee-ec4f-411e-bf70-bde98044f672)

## Code
```java
import java.util.Scanner;

class HelloWorld {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
       
        System.out.print("Enter Your Name:");
        String name = sc.nextLine(); 
        
        String[] parts = name.split(" ");
        
       
        String firstName = parts[0];
        String lastName = parts[parts.length - 1];
        
        
        System.out.println("First Name: " + firstName);
        System.out.println("Last Name: " + lastName);
       
        sc.close();
    }
}

```
