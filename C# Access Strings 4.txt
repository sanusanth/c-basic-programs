using System;

namespace GetLastName
{
  class Program
  {
    static void Main()
    {
      // Full name
      string name = "John Doe";

      // Location of the letter D
      int charPos = name.IndexOf("D");

      // Get last name
      string lastName = name.Substring(charPos);

      // Print the result
      Console.WriteLine(lastName);
    }
  }
}