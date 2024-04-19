```java


import java.util.Scanner;
class Main {
    static String divisibleBySeven(int a)
    {
        int n = a % 7; 
        if (n== 0) {
            return "True";
        
        }
        else  {
            return "False";
        }
    }

    public static void main(String[] args) { 
        Scanner sc = new Scanner(System.in);
        int a = sc.nextInt();
        // Call the function
        System.out.print( divisibleBySeven(a));
        sc.close();
    }
}

'''
