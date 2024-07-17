## Who is taller!
Alice and Bob were having an argument about which of them is taller than the other. Charlie got irritated by the argument, and decided to settle the matter once and for all.

Charlie measured the heights of Alice and Bob, and got to know that Alice's height is 

X centimeters and Bob's height is 

Y centimeters. Help Charlie decide who is taller.


```java
import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		 Scanner sc = new Scanner(System.in) ;
		int T = sc.nextInt() ;
		
        for ( int i= 0 ; i < T ; i++){
            int X = sc.nextInt() ;
            int Y = sc.nextInt() ;
            if ( X > Y){
                System.out.println("A");
            }
            else{
                  System.out.println("B");
            }
        }
	}
}
```
