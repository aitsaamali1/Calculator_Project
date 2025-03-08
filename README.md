using System;

class Program
{
    static void Main()
    {
        // Declare two numbers
        double num1, num2, product;

        // Ask user to enter the first number
        Console.Write("Enter the first number: ");
        num1 = Convert.ToDouble(Console.ReadLine());

        // Ask user to enter the second number
        Console.Write("Enter the second number: ");
        num2 = Convert.ToDouble(Console.ReadLine());

        // Perform the multiplication
        product = num1 * num2;

        // Display the result
        Console.WriteLine("The product of {0} and {1} is: {2}", num1, num2, product);
    }
}
