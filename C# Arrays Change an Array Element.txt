using System;

namespace MyApplication
{
  class Program
  {
    static void Main(string[] args)
    {
      string[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
      cars[0] = "Opel";
      Console.WriteLine(cars[0]);    
    }
  }
}