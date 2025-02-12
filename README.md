# Visual-studio-
This is lab1
This is an example of of reqired user Input and Output from a question.
Essentially this is practise for me as a beginner.
===================================================================================================================


using System.Diagnostics.CodeAnalysis;
using System.Numerics;

namespace Lab1
{
    internal class Program
    {
        static void Main(string[] args)
        {

            {
                

                Console.WriteLine("After surveying a number of new-home electrical installations, Kelly Builder’s Inc. " +
                "has worked out what the\r\nlength of wire a typical house would require. Write a program that will prompt " +
                "the user for the average\r\nlength required for a home and the number of houses to wire. The program will " +
                "then calculate and display\r\nthe total length of wire required for the specified number of houses.");

                Console.WriteLine();
                Console.WriteLine();
                Console.WriteLine();

                Console.WriteLine("------------------------------------------------------------------------------------------------------------------------");

                Console.WriteLine("For this question, I'll break it down by the number in meter of wire the user needs and the number of houses" +
                Environment.NewLine + "the user is building");
                Console.Write("Wire * houses will get us the total we need");
                Console.WriteLine();
                Console.WriteLine();
                Console.Write("INPUTS" + Environment.NewLine + "-Average Length of wire for an house " + Environment.NewLine + "-How many houses");
                Console.WriteLine();
                Console.Write("OUTPUTS" + Environment.NewLine + "-Total Length of wire needed");                

                Console.WriteLine();
                Console.WriteLine(new string('-', 120));

                Console.WriteLine("How much wire do you need in Meters: ");

                double wire = Convert.ToDouble(Console.ReadLine());
                Console.WriteLine();

                Console.WriteLine("How many houses will you be working on? ");
                int houses = Convert.ToInt32(Console.ReadLine());
                Console.WriteLine();

                double amount = wire * houses;

                Console.WriteLine();

                Console.WriteLine($"The user/worker will need approximately {amount}m of wire needed for {houses} homes  ");





            }
        }
    }
}


















