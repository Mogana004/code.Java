```java
import java.util.Scanner ;
class HelloWorld {
    public static void main(String[] args) {
        System.out.print("Enter a String :");
        Scanner sc = new Scanner(System.in);
        String str = sc.next();
        String reverse ="" ; 
        for (int  i = str.length()- 1; i >=0 ; i-- ){
            reverse += str.charAt(i);
            
        }
        System.out.print(reverse);
        
    }
}
```
