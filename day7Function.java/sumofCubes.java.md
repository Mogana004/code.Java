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
        int a = sc.nextInt();![WhatsApp Image 2024-04-28 at 5 18 20 PM](https://github.com/Mogana004/code.Java/assets/92911280/ee470c12-c143-4b74-a255-bd7d9a81320a)

        int b = sc.nextInt();
        sumOfCubesMToN(a , b);![WhatsApp Image 2024-04-28 at 5 18 20 PM](https://github.com/Mogana004/code.Java/assets/92911280/c28e3f69-cb88-4688-8166-9684e54fe0a6)

        sc.close();
    }
    
}
```
