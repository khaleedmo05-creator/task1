namespace ConsoleApp1
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Number of small carpets: ");
            int n1 = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Number of large carpets: ");
            int n2 = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Price per small room: $25");
            Console.WriteLine("Price per large room: $35");
            double cost = n1 * 25 + n2 * 35;
            double tax = 0.06 * cost, te = cost + tax;
            Console.WriteLine($"Cost : ${cost}\nTax: ${tax}\nTotal estimate: ${te}");
            Console.WriteLine("This estimate is valid for 30 days");
        }
    }
}
