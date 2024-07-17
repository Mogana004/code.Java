## Bull or Bear 
Chef is on his way to become the new big bull of the stock market but is a bit weak at calculating whether he made a profit or a loss on his deal.

Given that Chef bought the stock at value 
𝑋
 and sold it at value 
𝑌
. Help him calculate whether he made a profit, loss, or was it a neutral deal.


```java
import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		{   Scanner sc = new Scanner(System.in) ;
		int T = sc.nextInt() ;
		
        for ( int i= 0 ; i < T ; i++){
            int X = sc.nextInt() ;
            int Y = sc.nextInt() ;
            if ( X > Y){
                System.out.println("LOSS") ;
                
            }
            else if (X == Y ){
                System.out.println("NEUTRAL") ;
            }
            else{
                System.out.println("PROFIT") ;
            }
        }
	}
}
}```

https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/BULLBEAR
