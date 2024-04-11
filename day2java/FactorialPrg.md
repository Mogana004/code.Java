![image](https://github.com/Mogana004/code.Java/assets/92911280/279fbc03-4ebf-4926-9822-9401c897de45)

## code 
```java
import java.util.Scanner;
class Average {
    public static void main(String[] args){
        Scanner nc = new Scanner(System.in);
        System.out.print("Enter a positive number :");
        int n = nc.nextInt();
        int factorial = 1;
        if (n>0){
            for (int i = 1 ; i <= n; i++){
                factorial *= i;
        }
        System.out.println("Factorial:" + factorial);
    }
        else{
            System.out.println("plz enter positive int");
        }
    }
}
```
