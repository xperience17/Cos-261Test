# Cos-261Test

public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");// print hello word
    }
}

String a = new String("hi");
String b = new String("hi");
System.out.println(x == y);        // false: compares references
System.out.println(x.equals(y));   // true: compares string contents


public class Addintegers{
    public static void main(String[] args) {
        int Sum=0;
        Scanner input = new Scanner(System.in);
        System.out.print("Enter first number: ");// input first number
        int num1= input.nextInt();
        System.out.print("Enter second number: ");// input second number
        int num2 = input.nextInt();
        Sum = num1 + num2;
        System.out.println("Sum is " +Sum);// display the sum of the two numbers 
    }
}


int n = 20;
          if (n % 2 == 0) {
              System.out.println(n + " is       even");// display if n is even
         } else {
    System.out.println(n + " is odd");//  display if n is odd
}


int a = 4, b = 6, c = 10;
           int max = a;
          if (b > max) max = b;
          if (c > max) max = c;
        System.out.println("Largest is " + max);// display the largest number 


import java.util.Scanner;
public class MultiplicationTable {
    public static void main(String[]args){
        int n = 2;
for (int i = 1; i <= 12; i++) {
    System.out.println(n + " x " + i + " = " + (n * i));
}

    }
}


public class Student {
 private String name;
    private String matricNo;
 private double score;

    public Student(String name, String matricNo, double score) {       this.name = name;
    this.matricNo = matricNo;
      this.score = score;
    }

    public void displayInfo() {       System.out.println("Name: " + name);
     System.out.println("Matric No: " + matricNo);
       System.out.println("Score: " + score);
    }
}
// Usage:
// Student s = new Student("Alice", "A1234", 88.5);
// s.displayInfo();


