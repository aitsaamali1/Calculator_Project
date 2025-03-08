using System;

class Program
{
    static void Main()
    {
        // Declare two numbers
        int num1, num2, sum;

        // Ask user to enter the first number
        Console.Write("Enter the first number: ");
        num1 = Convert.ToInt32(Console.ReadLine());

        // Ask user to enter the second number
        Console.Write("Enter the second number: ");
        num2 = Convert.ToInt32(Console.ReadLine());

        // Perform the addition
        sum = num1 + num2;

        // Display the result
        Console.WriteLine("The sum of {0} and {1} is: {2}", num1, num2, sum);
    }
}
