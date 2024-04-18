```java
import java.util.Scanner;
import java.util.Arrays;
class Array{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        long N = sc.nextInt();
        int times = sc.nextInt();
        long[] repeatedArray = new long[times];
       Arrays.fill(repeatedArray , N);
       System.out.println(Arrays.toString(repeatedArray));
       
    }
}
```
