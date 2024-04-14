
```java
import java.util.Scanner;
class trianglepattern{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        int N = sc.nextInt();
        for (int i = 1 ; i<= N ; i++){
            for (int j= 1 ; j <=i ; j++){
                System.out.print("*" +" ");
            }
            System.out.println();
        }
    }
}
```

![image](https://github.com/Mogana004/code.Java/assets/92911280/5d5298d3-e0a1-48ff-99e4-ca06a88ee47f)
