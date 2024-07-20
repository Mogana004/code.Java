### Sum of Digits
You're given an integer N. Write a program to calculate the sum of all the digits of N.

#### Input Format
The first line contains an integer T, the total number of testcases. Then follow T lines, each line contains an integer N.


```java
import java.util.*;
import java.lang.*;
import java.util.Scanner;

class Codechef {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int T = sc.nextInt();

        for (int i = 0; i < T; i++) {
           
            int n = sc.nextInt();
            
            int sum = 0; 

            
            while (n > 0) {
                sum += n % 10; 
                n /= 10; 
            }

            System.out.println(sum);
        }

    
    }
}
```
https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/FLOW006
