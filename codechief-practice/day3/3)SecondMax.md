![image](https://github.com/Mogana004/code.Java/assets/92911280/f90f27af-e46d-4861-811d-4237e6c26b6d)

```java
import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		Scanner sc = new Scanner(System.in) ;
		int N = sc.nextInt();
		 for (int i = 0 ; i< N ; i++){
		     int x = sc.nextInt() ;
		     int y = sc.nextInt() ;
		     int z = sc.nextInt() ;
		    
		
		int[] arr = {x , y , z} ;
		Arrays.sort(arr) ;
		int Secondmax = arr[1] ;
		System.out.println(Secondmax) ;
		 }
	}
}
```
