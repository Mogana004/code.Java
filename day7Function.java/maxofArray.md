```java
import java.util.Arrays ;
import java.util.Scanner ;

class max{
   
    public static void main( String[] args){
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter the range :");
        int n = sc.nextInt() ;
        int[] array = new int[n];
        
        
        for (int i = 0 ; i < n ; i++){
            array[i] = sc.nextInt();
            
         
        }
        System.out.println(arrayMax(array));
    }
    static  int arrayMax(int[] array){
        int max = array[0];
        
        for (int  j : array){
            if (max < j ){
                max = j;
                
            }
        }
       return max;
        
    }
}

```
![image](https://github.com/Mogana004/code.Java/assets/92911280/e3686872-d0ea-42ec-afb8-139e4df8da43)
