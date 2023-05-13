# Experiment-2

# Compare Numbers

# Aim:
  To write a Java program to perform comparisons on the given numbers.
# Algorithm:
Step 1 : Open Intelli J application or any other code editor.

Step 2 : Create a class and name it CompareNumbers.

Step 3 : Using Scanner, we can input numbers from the user.

Step 4 : Write the logic for the program using comparing operators.

Step 5 : Display the operations done the input numbers in the terminal.

# Program:
```
Program developed by: SOMEASVAR.R
Register No: 212221230103
```
```
import java.util.Scanner;
public class compare
{
    public static void main(String[]args)
    {
        Scanner cs=new Scanner(System.in);
        System.out.println("Enter the value for number 1:");
        int a=cs.nextInt();
        System.out.println("Enter the value for number 2:");
        int b= cs.nextInt();
        System.out.println("Comparing are as follows:");
        System.out.println(" ");
        if(a==b)
        {
            System.out.println("Given two numbers are equal");
        }
        if(a!=b)
        {
            System.out.println("Given two numbers are not equal");
        }
        if(a>b)
        {
            System.out.println("Number 1 is greater than Number 2");
        }
        if(a<b)
        {
            System.out.println("Number 2 is greater than Number 1");
        }
    }
}

```
# Output:
![image](https://github.com/SOMEASVAR/compare/assets/93434149/8b1a316b-ed6d-455a-bb74-01f0edf34e53)


# Result:
  We have successfully created a Java program to display the comparisons on input numbers.
