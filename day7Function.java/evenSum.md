![image](https://github.com/Mogana004/code.Java/assets/92911280/a58e95c6-a8f1-448c-88a9-2c0b4b61bd6c)
```java
// Online Java Compiler
import java.util.Scanner ;
class HelloWorld {
    
    public static int evenSum(int n ){
        int sum = 0 ;
       
        
        for ( int i=1 ; i <= n ; i++ ){
            if (i % 2 == 0){
                sum = sum + i ;
                
            }
        }
        return sum ;
    }
    public static void main(String[] args) {
         Scanner sc = new Scanner(System.in);
        System.out.print("Enter the range :");
        
        int range = sc.nextInt();
        System.out.print("The Sum is :" + evenSum(range));
        
    }
}
```
