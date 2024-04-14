```java
import java.util.Scanner;
class SumofN{
    public static void main(String[] args){
        Scanner sc= new Scanner(System.in);
        int N = sc.nextInt();
        long Sum= 0;
        for (int i= 1 ; i <=N ; i++){
            int inputs = sc.nextInt();
            Sum= Sum+ inputs ;
            
        }
        System.out.println(Sum);
        
    }
}
```

### Question 
Read N inputs from the user and print its Sum 
