---
Layout: Post
Tile: Calculations
categories: C# Programming
---
Calculations are good as they can make hard numbers easy as long as it is a whole number however learning new things like:

|Symbol|Meaning |
|------|--------|
|  +   |Add     |
|  -   |Subtract|
|  *   |Multiply|
|  /   |Divide  |

Using the + we can now connect two pieces of string together. In this lesson we also made it so the program remembers and interprets
something such as integers but we can also do this with string to connect a sentence together with personalised information. We achieve
this through using the line of code:

```csharp
int a = Convert.ToInt32(Console.ReadLine());
```

This is great for making big calculations very fast. This is all the code i did for the calculations lesson:

```csharp
            int a = 1;
            a = a + 1;
            Console.WriteLine("A is " + a);
            Console.ReadLine();

            Console.WriteLine("Enter a number A:");
            int B = Convert.ToInt32(Console.ReadLine());
            int C = B + 2;
            Console.WriteLine(B + " plus two is " + C);
            Console.ReadLine();

            Console.WriteLine("Enter the height:");
            int b = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Enter the width:");
            int c = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Enter the length:");
            int d = Convert.ToInt32(Console.ReadLine());
            int e = b * c * d;
            Console.WriteLine("The volume of your cuboid is " + e + " centimetres cubed");
            Console.ReadLine();

            Console.WriteLine("Enter a number");
            int D = Convert.ToInt32(Console.ReadLine());
            int E = D * 1;
            int F = D * 2;
            int G = D * 3;
            int H = D * 4;
            int I = D * 5;
            Console.WriteLine("1 times " + D + " is " + E);
            Console.WriteLine("2 times " + D + " is " + F);
            Console.WriteLine("3 times " + D + " is " + G);
            Console.WriteLine("4 times " + D + " is " + H);
            Console.WriteLine("5 times " + D + " is " + I);
            Console.ReadLine();
 ```
            
The last bit of code was my attempt at a challenge by using a short of formula to work out this problem that was proposed
to it.
if statements is the next thing...
