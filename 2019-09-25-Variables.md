---
Layout: Post
Tile: Variables
categories: C# Programming
---

Variables is a basic start to programming through command promt, and this meant that i could give the system a sequence to run with 
different variables and putting them together to make a sentence this is then recognised then displayed on screen i used different things
such as bool to decide whether something is true or false, i used int for something like age as this my integer (number) and i used string 
for letters in this case my name.

```csharp
int age = 16;
bool glasses = false;
string name = "Kyle";
Console.WriteLine("Hello my name is " + name + " and i am " + age + " years old and it is " + glasses + " that i wear glasses.");
Console.ReadLine();
```
i put this withing the curly brackets of  ```static void Main(string[] args)```

I also found out how to make note on how ive done something so someone else can understand what ive done and get into my mind set.
This is done by doing // to write 1 line of notes or you can do /* to write multiple lines of notes or hints this is great so that if
something is wrong at the end of writing a lot of code then you know what you did and how to change it.

This lesson everything i did is below, each excersise if you require additional help, even program them again:

```csharp
 static void Main(string[] args)
        {
            int age = 16;
            bool glasses = false;
            string name = "Kyle";
            Console.WriteLine("Hello my name is " + name + " and i am " + age + " years old and it is " + glasses + " that i wear glasses.");
            Console.ReadLine();

            int Age = 10;
            bool Glasses = false;
            string Names = "Admins Programme";
            Console.WriteLine("Hello my name is " + Names + " and i am " + Age + " minutes old and it is " + Glasses + " that i wear glasses.");
            Console.ReadLine();

            string Name;
            Console.WriteLine("Please enter your name");
            Name = Console.ReadLine();
            Console.WriteLine("\nHello " + Name + ". Nice to meet you!");
            Console.ReadLine();

            string Surname;
            Console.WriteLine("\nWhat is your second name?");
            Surname = Console.ReadLine();
            Console.WriteLine("\nIt's nice to meet you " +  Name  + " " +  Surname  + ". I am Admins programme!");
            Console.ReadLine();

            String Y;
            String X;
            Console.WriteLine("So " + name + ", what is your favourite movie and how many times have you seen it?");
            X = Console.ReadLine();
            Y = Console.ReadLine();
            Console.WriteLine("Nice to know that your favourite movie is " + X + " and you have seen it " + Y + " times.");
            Console.ReadLine();

            /*
             HelloWorld Program by J.Pitt 2007
             This program is designed to print the words
             Hello World! on the screen
             */

            Console.WriteLine("Hello World!"); //this
            Console.ReadLine(); //this

            /*
             * Program to demonstrate adding numbers.
             * By J.Pitt
             * */

            // Declare Variables
            int a = 20;
            int b = 25;
            int c;
            c = a + b; // make c into a plus b

            //show the values on screen
            Console.WriteLine("A is " + a);
            Console.WriteLine("B is " + b);
            Console.WriteLine("A plus B is " + c);
            Console.ReadLine(); //stops the program from finishing

            // Declare Variables
            int d = 81;
            int e = 9;
            int f;
            f = d / e; // make c into a plus b

            //show the values on screen
            Console.WriteLine("D is " + d);
            Console.WriteLine("E is " + e);
            Console.WriteLine("D minus E is " + f);
            Console.ReadLine(); //stops the program from finishing

            string temp; //used to store strings until they are converted

            //get the numbers from the user 
            Console.WriteLine("Enter number A:");
            temp = Console.ReadLine();
            int A = Convert.ToInt32(temp);
            Console.WriteLine("Enter another number B:");
            temp = Console.ReadLine();
            int B = Convert.ToInt32(temp);

            int C = A + B;

            //display result
            Console.WriteLine(A + " plus " + B + " equals " + C);
            Console.ReadLine();

            //To make the last string of code smaller you can
            Console.WriteLine("Enter number A:");
            int D = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Enter another number B:");
            int E = Convert.ToInt32(Console.ReadLine());
            int F = D * E;
            Console.WriteLine(D + " multiply " + E + " equals " + F);
            Console.ReadLine();

            //Class program excersise 3.2 3 multiplication
            Console.WriteLine("Enter number A:");
            int G = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Enter another number B:");
            int H = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Enter the final number C:");
            int I = Convert.ToInt32(Console.ReadLine());
            int J = G * H * I;
            Console.WriteLine(G + " multiply " + H + " multiply " + I + " equals " + J);
            Console.ReadLine();
       
