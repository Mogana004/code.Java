
```java
import java.util.Scanner;

class Main {
    static int countTheVowels(String s)
    {
       int  c= 0 ;
       s = s.toLowerCase();
        for (int i = 0 ; i< s.length() ;i++){
            char ch = s.charAt(i);
            if ( ch== 'a' || ch== 'e' || ch== 'i' || ch== 'o' || ch=='u'){
                c++  ;
            }
        }
       return c;
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String s = sc.nextLine();
         System.out.print(countTheVowels(s));
        sc.close();
    }
}
```
