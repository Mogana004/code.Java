```java
import java.util.InputMismatchException;
import java.util.Scanner;
class reverse {
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        int N;
       N = sc.nextInt();
       
        sc.nextLine();
        String[] array = new String[N];
        for (int i =0 ; i < N ; i++){
            array[i] =sc.nextLine();
        }    
        for (int i = N-1 ; i >= 0 ; i--){
            System.out.println(array[i]);
            
        }
        sc.close();
        }
    }
```
