### First and Last Digit
Given an integer N . Write a program to obtain the sum of the first and last digits of this number.

#### Input Format
The first line contains an integer T, the total number of test cases. Then follow T lines, each line contains an integer N.
```java
import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{ Scanner sc = new Scanner(System.in) ;
	
	 int T = sc.nextInt() ;
	 for (int i = 0 ; i < T ; i++){
	     int n = sc.nextInt() ;
	     int lastDigit = n % 10 ;
	     
	      int firstDigit = n;
        while (firstDigit >= 10) {
            firstDigit /= 10;
        }
        int sum = firstDigit + lastDigit ;
        System.out.println(sum) ;
	 }
	 
	 

	}
}
```

https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/FLOW004
### output
![image](https://github.com/user-attachments/assets/fb298e0f-43c8-495a-9991-e16d76a9dc07)

```
