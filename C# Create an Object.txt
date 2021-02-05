using System;

namespace MyApplication
{
  class Car
  {
    string color = "red";

    static void Main(string[] args)
    {
      Car myObj = new Car();
      Console.WriteLine(myObj.color);
    }
  }
}