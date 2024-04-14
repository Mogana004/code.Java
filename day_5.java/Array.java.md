``` java
import java.util.Scanner;
class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int size = sc.nextInt(); //getting the array size from the user 
        
        int[] num_seq = new int[size]; // creating an integer array with specified size
        int index= 0 ;
        while (index <size){
            num_seq[index] = sc.nextInt(); // storing the array elements 
            index = index+ 1 ;
            
        }
        for (int each_item : num_seq){
            int square = each_item * each_item ; // squaring each elements in the array 
            System.out.print(square + " "); // printing the squared array elements 
            
        }
        
    }
}

```

## input 
### 6
### 1 2 5 7 6 4



## output 
### 1 4 25 49 36 16 
