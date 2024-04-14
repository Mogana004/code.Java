## Question 
printing pattern with M number of Rows and N number of Columns 
## code 

```java
import java.util.Scanner;
class rectangle{
    public static void main(String[] args){
      Scanner sc = new Scanner(System.in);
      int M = sc.nextInt();
      int N = sc.nextInt();
      for (int i = 1 ; i <= M ; i++){
          for (int j = 1 ; j <= N ; j++){
              System.out.print("*" + " ");
              
          }
          System.out.println();
      }
    }
    
}
```
## output
![image](https://github.com/Mogana004/code.Java/assets/92911280/f8a30b54-4bbf-425a-913a-ba94873fa405)
