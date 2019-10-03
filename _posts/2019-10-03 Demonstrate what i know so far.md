---
Layout: Post
Tile: What I Know So Far/Switch Case
categories: C# Programming
---

In todays lesson i was tested on what i know so far and this included the ability to demonstrate:
-Declaring Variables
-Writing To The Screen
-Reading Input From The User
-Converting From One Data Type To Another
-If Statements & Switch Case Statements
When i was first showed this i had identified that i had not done anything on switch case so i had to learn it alongside demonstrating what i know.

Using switch/case allows you to make a program do different things depeendings on the value of a variable. It sometimes can be used as an alternative to if statements.

```csharp
            String Y;
            Console.WriteLine("Hello user can you please tell me your name?:");
            Y = Console.ReadLine();
            Console.WriteLine("Hi " + Y + " Im a currency converter. Can you please enter how much you want to convert from pound to dollars and vice versa.Please enter your currency as well 1 is for dollars and 2 is for pounds.");
            double a = Convert.ToDouble(Console.ReadLine());
            int b = Convert.ToInt32(Console.ReadLine());
            if (b < 2)
            {
                double c = a * 0.59;
                Console.WriteLine( Y + " You wanted to convert " + a + " dollars and that is " + c + " pounds.");
            }
            else
            {
                double d = a * 1.67;
                Console.WriteLine( Y + " You wanted to convert " + a + " pounds and that is " + d + " dollars.");
            }
            Console.ReadLine();

            String X;
            Console.WriteLine("Hello user can you please tell me your name?:");
            X = Console.ReadLine();
            Console.WriteLine("Hi " + X + " Im a currency converter. Can you please enter how much you want to convert from pound to dollars and vice versa.Please enter your currency as well 1 is for dollars and 2 is for pounds.");
            double A = Convert.ToDouble(Console.ReadLine());
            int B = Convert.ToInt32(Console.ReadLine());
            switch (B)
            {
                case 1:
                    Console.WriteLine("Your choice of currency was dollars and $" + A + " is £" + A*0.59 + ".");
                    break;
                case 2:
                    Console.WriteLine("Your choice of currency is pounds and £" + A + " is $" + A*1.67 + ".");
                    break;
                default:
                    Console.WriteLine("You did not choose a valid currency");
                    break;
                
            }
            Console.ReadLine();
```


