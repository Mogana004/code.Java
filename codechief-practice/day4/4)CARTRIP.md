```java
import java.util.* ;

import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
	   Scanner sc = new Scanner(System.in);
        int T = sc.nextInt();
        for (int i = 0; i < T; i++) {
            
            int X = sc.nextInt();
            int cost ;
            if (X < 300){
                cost = 300 * 10 ;
            }else{
                cost = X * 10;
            }
           
            System.out.println(cost);
        }
        sc.close();

	}
}```
## Question 
https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/CARTRIP

```
