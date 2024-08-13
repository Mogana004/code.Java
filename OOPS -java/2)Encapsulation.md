```java
 class Student{
        private int age ;
        
        public int getAge(){
            return age ;
        }
        public void setAge(int age ){
            this.age = age ;
            
        }
    }
  class Main {
   
    public static void main(String[] args) {
        Student stu = new Student();
        stu.setAge(20) ;
        System.out.println(stu.getAge()) ;
    }
}
```

### Encapsulation refers to the bundling of attributes and methods inside a single class.
### Getter method returns the value of a particular non-static attribute of the class.
 ### Setter method sets a new value to a particular non-static attribute of the class.
### Getters and setters provide us with control over the data in our program.
