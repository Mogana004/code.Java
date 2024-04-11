![image](https://github.com/Mogana004/code.Java/assets/92911280/a1e6ac47-cd12-455f-9400-cf22daf60f26)

## code
```java
import java.util.Scanner;
class Average {
    public static void main(String[] args){
       
        Scanner nc = new Scanner(System.in);
        
        System.out.println("Enter the 1st number:");
        int number1 = nc.nextInt();
        
        System.out.println("Enter the 2nd number:");
        int number2 = nc.nextInt();
        
        System.out.println("Enter the 3rd number:");
        int number3 = nc.nextInt();
        nc.close();
        
        float avg ;
        int sum ;
        sum = number1 + number2 + number3 ;
        avg = sum / 3 ;
        System.out.println("The Average of three numbers is :"+ avg);
    }
}
  ```
