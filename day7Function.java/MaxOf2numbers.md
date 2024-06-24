###  Write a function that takes 2 numbers as input and the function should return the maximum of the 2 numbers
```java

import java.util.Scanner ;

class max{
    static int maximum( int a , int b ){
        int max = a ;
        if (b > a) {
            max = b ;
            
        }
        return max ; 
    }
    public static void main( String[] args){
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter two numbers a & b:");
        int a = sc.nextInt();
        int b = sc.nextInt();
        System.out.print ("The maximum is :" + maximum(a , b));
        
        
    }
}
```
