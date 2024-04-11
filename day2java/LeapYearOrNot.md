![image](https://github.com/Mogana004/code.Java/assets/92911280/163a4785-a082-46a4-ac73-d7afeb5452c2)

## code
```java

import java.util.Scanner;
class Average {
    public static void main(String[] args){
       
        Scanner nc = new Scanner(System.in);
        
        System.out.print("Enter the year:");
        int year = nc.nextInt();
        if ((year % 4 == 0) && (year %100  != 0)){
             System.out.println("Its a leap year");
        }else{
             System.out.print("Not a Leap Year");
         }
        
       
    }
}
```
