![image](https://github.com/Mogana004/code.Java/assets/92911280/6dc58bf2-88e8-4f65-80fe-31de4c83cdf6)

## code
```java
import java.util.Random;
public class generateRandom {
    public static void main(String[] args) {
        Random ran = new Random();
        int randomInt1 = ran.nextInt(6);
        int randomInt2 = ran.nextInt(50);
        System.out.println("Random Int value 1 =" +randomInt1);
        System.out.println("Random Int value 2 =" +randomInt2);
        
        
        
        
       double randomDouble1 = ran.nextDouble();
       double randomDouble2 = ran.nextDouble();
       System.out.println("Random double value 1 =" +randomDouble1);
       System.out.println("Random double value 2 =" +randomDouble1);
        
    }
}
```
