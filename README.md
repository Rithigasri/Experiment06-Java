# EXPERIMENT 06: CREATE A METHOD TO CALCULATE POWER OF A NUMBER RAISED TO OTHER
## AIM:
To create a method to calculate power of a number raised to other using java programming language.

## PROCEDURE:
1. Import required packages.
2. Declare main method with the signature "public static void main(String[] args)".
3. Get the inputs from the user.
4. Create a recursive function that returns a number raised to other.
5. Display the result.
6. End the program.

## PROGRAM:
```
import java.util.Scanner;
public class Power {
    public static void main(String[] args)
    {
        Scanner scan=new Scanner(System.in);
        System.out.print("Enter the first number: ");
        int a=scan.nextInt();
        System.out.print("Enter the second number: ");
        int b=scan.nextInt();
        int result=recursion(a,b);
        System.out.println("Answer: "+result);

    }
    static int recursion(int a,int b)
    {

       if(b==0)
           return 1;
       else
           return a*(recursion(a,b-1));
    }
}

```

## OUTPUT:
![image](https://github.com/Rithigasri/Experiment06-Java/assets/93427256/1bf1c233-0147-4194-94fd-7150044e63dd)
## RESULT:
Hence, a program to calculate power of a number raised to other was created and executed successfully.
