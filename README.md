# Integer-to-Hex-and-Binary
Just another repository
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Integer_to_Hex_and_Binary
{
    class Program
    {
        static void Main(string[] args)
        {
            int num = int.Parse(Console.ReadLine());

            string hexadecimal = Convert.ToString(num, 16).ToUpper();
            string binary = Convert.ToString(num, 2);

            Console.WriteLine(hexadecimal);
            Console.WriteLine(binary);
        }
    }
}
