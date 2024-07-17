## Battery Health
Apple considers any iPhone with a battery health of 

80% or above, to be in optimal condition.

#### Given that your iPhone has 

X% battery health, find whether it is in optimal condition.

#### Input Format
The first line of input will contain a single integer 

T, denoting the number of test cases.
The first and only line of each test case contains an integer 

X — the battery health.
#### Output Format
For each test case, output on a new line, YES, if the battery is in optimal condition, and NO otherwise.

```java
import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{   Scanner sc = new Scanner(System.in) ;
		int T = sc.nextInt() ;
		
        for ( int i= 0 ; i < T ; i++){
            int X = sc.nextInt() ;
            if ( X >= 80){
                System.out.println("YES") ;
                
            }
            else{
                System.out.println("NO") ;
                
                
            }
            
        }
        
	}
}
```
https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/BTRYHLTH
