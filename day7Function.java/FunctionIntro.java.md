
## passing parameters to the method 
```java
class Main {
    static void introduction(String name, int height, double weight) {
        // name, height and weight are greet method parameters.
        System.out.println(name + " weighs " + weight + " kg and is " + height + " cm tall.");
    }

    public static void main(String[] args) {
        String name = "Rohit";
        int height = 168;
        double weight = 70.5;

        introduction(name, height, weight);
    }
```


## method overloading 
If a class has multiple methods having same name but different in parameters, it is known as Method Overloading.

There are two ways to overload the method in java

####  By changing the data type of Parameters
#### By changing the number of Parameters


### By changing the data type of Parameters
```java
class Main {
    static void addition(int a, int b) {
        // a and b  are called method parameters

        int sum = a + b;
        System.out.println("The sum of 2 int numbers " + a + " and " + b + " is " + sum);
    }

    static void addition(double a, double b) {
        // a and b are called method parameters

        double sum = a + b;
        System.out.println("The sum of 2 float numbers " + a + " and " + b + " is " + sum);
    }

    public static void main(String[] args) {
        int value1 = 20;
        int value2 = 34;
        double value3 = 45.6;
        double value4 = 32.3;

        addition(value1, value2);
        addition(value3, value4);
    }
}
```

### Method Overloading by changing the number of Parameters

```java
class Main {
    static void addition(int a, int b) {
        // a and b are called method parameters

        int sum = a + b;
        System.out.println("The sum of 2 numbers " + a + " and " + b + " is " + sum);
    }

    static void addition(int a, int b, int c) {
        // a, b and c are called method parameters

        int sum = a + b + c;
        System.out.println("The sum of 3 numbers " + a + ", " + b + " and " + c + " is " + sum);
    }

    public static void main(String[] args) {
        int value1 = 20;
        int value2 = 34;
        int value3 = 45;

        addition(value1, value2);
        addition(value1, value2, value3);
    }
}
```

##  passing Mutable objects
Similar to Python, when mutable objects are passed as method arguments, the changes done to the object inside the method will affect the original object.
```java
import java.util.Arrays;

class Main {
   static void twice(int[] arr2 ) {
       int n = arr2.length;

       for(int i = 0; i < n ; i++){
           arr2[i] = 2 * arr2[i];
       }
   }

   public static void main(String[] args) {
       int[] arr1 = {36,43,10,112,66,18};

       System.out.println("Before modifying: " + Arrays.toString(arr1));

       twice(arr1);

       System.out.println("After modifying: " +  Arrays.toString(arr1));
   }
}
```

## passing immutable objects 
```java

class Main {
   static void fullName(String str2) {
       str2 = "William Smith";

       System.out.println("Inside fullName() method: " + str2);
   }

   public static void main(String[] args) {
       String str1 = "William";

       fullName(str1);

       System.out.println("Inside main() method: " + str1);
    }
}
```

## RECURSION 
Recursion is a process in which a method calls itself in the process of its execution.

A recursive method terminates when a condition is met. This condition is also called Base Case

Recursion makes a program compact and small.
```java
class Main {
    static int factorial(int num) {  // recursive function
        if (num == 1) {  // base case
            return 1;
        }

        return num * factorial(num - 1);  // recursion
    }

    public static void main(String[] args) {
        int num = 5;
        int result = factorial(num);

        System.out.println(result);
    }
}
```
