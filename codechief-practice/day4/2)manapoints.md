```java
import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		Scanner sc = new Scanner(System.in);
		int T = sc.nextInt() ;
		for ( int i = 0 ; i < T ;  i++){
		    int x = sc.nextInt() ;
		    int y = sc.nextInt() ;
		    int attack = y / x ;
		    if (attack == 0) {
		        System.out.println(0) ;
		    }
		  else{
		      System.out.println(attack) ;
		  } 
		}
		}
	}

```

## question 
https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/MANAPTS
