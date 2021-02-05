using System;

namespace MyApplication
{
  class Program
  {
    static void Main(string[] args)
    {
      try
      {
        int[] myNumbers = {1, 2, 3};
        Console.WriteLine(myNumbers[10]);
      }
      catch (Exception e)
      {
        Console.WriteLine("Something went wrong.");
      }  
      finally
      {
        Console.WriteLine("The 'try catch' is finished.");
      }  
    }
  }
}