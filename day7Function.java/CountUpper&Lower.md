```java
import java.util.Scanner ;
class Main {

    static void CountOfLowercaseAndUppercaseLetters(String str)
    { int upperCaseCount = 0 ;
    int  lowerCaseCount = 0 ;
    
        for (int i = 0 ; i < str.length() ; i++){
          char c =   str.charAt(i) ;
           if (Character.isUpperCase(c)) {
                upperCaseCount++;
            }
            // Check if the character is a lowercase letter
            else if (Character.isLowerCase(c)) {
                lowerCaseCount++;
            }
        }
        System.out.println(upperCaseCount);
        System.out.println(lowerCaseCount);
   
    }

    public static void main(String[] args) {
        
        Scanner sc = new Scanner(System.in);      
        String chars= sc.nextLine();
        
         CountOfLowercaseAndUppercaseLetters(chars );
         
        sc.close();
    }
    
}
```
