```java
import java.util.Arrays;
class HelloWorld {
  
    public static void main(String[] args) {
        
       int[] arr = {1 , 2 , 3 ,4 , 5 };
       System.out.print(Arrays.toString(arr));
       change(arr);
       System.out.print(Arrays.toString(arr));
    }
    
    
    static void change(int[] arr){
        arr[0] =99 ;
      arr[1] = 99999;
        
    }
}
```

![image](https://github.com/Mogana004/code.Java/assets/92911280/7198ca3b-1e34-4bec-bb25-2a29203443bc)
