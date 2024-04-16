
```java
import java.util.Scanner;
class Array{
    public static void main(String[] args){
         Scanner sc = new Scanner(System.in);
         int m = sc.nextInt();
         int n = sc.nextInt();
         int x = sc.nextInt();
         int y = sc.nextInt();
         
         
         int arr[][] = new int[m][n];
         for (int i= 0 ; i< m ; i++){
             for (int j=0 ; j<n ; j++){
                 arr[i][j] = sc.nextInt();
                 
             }
         }
         System.out.println(arr[x][y]);
         sc.close();
         
    }
}
```
## output
![image](https://github.com/Mogana004/code.Java/assets/92911280/aa0d9968-7f55-43c9-837d-c17930cf72b0)
