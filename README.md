using System;

class Program
{
    static void Main()
    {
        // Declare two numbers
        double num1, num2, result;

        // Ask user to enter the first number
        Console.Write("Enter the first number: ");
        num1 = Convert.ToDouble(Console.ReadLine());

        // Ask user to enter the second number
        Console.Write("Enter the second number: ");
        num2 = Convert.ToDouble(Console.ReadLine());

        // Check for division by zero
        if (num2 == 0)
        {
            Console.WriteLine("Error! Division by zero is not allowed.");
        }
        else
        {
            // Perform the division
            result = num1 / num2;

            // Display the result
            Console.WriteLine("The result of {0} divided by {1} is: {2}", num1, num2, result);
        }
    }
}
