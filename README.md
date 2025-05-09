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
        
