```java
import java.util.Scanner;

class Main {
    static void sumOfCubesMToN(int a, int b) {
        int sum  = 0 ;
        for (int i= a ; i <=b ; i++){
            int cubes = i*i*i;
            sum = sum + cubes ;
       }
        System.out.print(sum);

    }


    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int a = sc.nextInt();

        int b = sc.nextInt();
        sumOfCubesMToN(a , b);
        sc.close();
    }
    
}
```
![image](https://github.com/Mogana004/code.Java/assets/92911280/0e6e224c-b6fe-4040-999c-021b15aa0fe9)

