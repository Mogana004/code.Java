problem link : https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/PROINC
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
	for ( int i = 0 ; i < T ; i++){
	    int X = sc.nextInt() ;
	    int Y = sc.nextInt() ;
	    
	    double inc = 1.10 *  X ;
	    int BP = X - Y ;
	   double newprofit = inc - BP ;
	    System.out.println((int)newprofit) ;
	}

	}
}
```
