```java
import java.util.Scanner;
class Array{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        int N = sc.nextInt();
        String[] array = {"Python" ,"Java" ,"Ruby" , "C" , "C++","Go" ,"R" ,"JavaScript" ,"Swift" ,"PHP","Kotlin"
,"Perl"};        
        for (int i=0 ; i < N ; i++ ){
            int sc1 = sc.nextInt();
            
            System.out.println(array[sc1]);
        }
    }
}
```
## Question 
Write a prgm to read N and print the elements at the index location represented by those numbers 
