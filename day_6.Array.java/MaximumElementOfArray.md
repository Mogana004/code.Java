```java
import java.util.Scanner;

class HelloWorld {
    public static void main(String[] args) {
       Scanner sc = new Scanner(System.in);
       int N = sc.nextInt();
       int[] array = new int[N];
       
       // Input elements into the array
       for (int i = 0; i < N; i++) {
           array[i] = sc.nextInt();
       }
       
       // Find the maximum element in the array
       int max = array[0];  // Initialize max with the first element
       for (int i = 1; i < N; i++) {
           if (array[i] > max) {
               max = array[i];
           }
       }
       
       // Print the maximum element
       System.out.println("Maximum Element: " + max);
    }
}
```
