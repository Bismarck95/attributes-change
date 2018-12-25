# attributes-change
for knowledge
using System;

namespace de
{
    class MainClass
    {
        public static void Main(string[] args)
        {
        
            Console.WriteLine("Please give a number as 1st variable:");
            int a = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Please give a number as 2st variable:");
            int  b = Convert.ToInt32(Console.ReadLine());
            a = a + b;
            b = a - b;
            a = a - b;
            Console.WriteLine("Please give a number as 1st variable:"+a);
            Console.WriteLine("Please give a number as 2st variable:" + b);


        }
     
    }
}
