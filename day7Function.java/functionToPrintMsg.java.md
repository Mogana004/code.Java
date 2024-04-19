```java
import java.util.Scanner;
class Main {

    static String message(String name)
    {
        return "Welcome " + name;
    }

    public static void main(String[] args) {
        
        Scanner sc = new Scanner(System.in);

        String name = sc.nextLine();
        // Call the function
         String reply = message(name);
        System.out.print(reply);
        
        sc.close();
    }
    
}
```
