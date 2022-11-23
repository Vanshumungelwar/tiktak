2.Write a program in java to implement a calculator with simple arithmetic operations 
package constructoroverloading; 
import java.util.Scanner; 
public class Calculator { 
 public static void main(String[] args) { 
 Double a, b, result; 
 Scanner input = new Scanner(System.in);
 System.out.println("Enter an operator: +, -, *, or /"); 
 String operator = input.next(); 
 
 System.out.println("Enter first number"); 
 a = input.nextDouble(); 
 System.out.println("Enter second number"); 
 b = input.nextDouble(); 
 switch (operator) { 
 
 case "+": 
 result = a + b;System.out.println(a + " + " + b + " = " + result); 
 break; 
 case "-":
 result = a - b;
 System.out.println(a + " - " + b + " = " + result); 
 break; 
 case "*": 
 result = a * b; 
 System.out.println(a + " * " + b + " = " + result); 
 break; 
 case "/": 
 result = a / b; 
 System.out.println(a + " / " + b + " = " + result); 
 break; 
 default: 
 System.out.println("Invalid operator!"); 
 break; 
 } 
 } 
 
 }
