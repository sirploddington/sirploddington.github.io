--- 
layout: post
title: Parameter Passing 
categories: C# Programming
---
 
 By value: allows the variable to be used within the subroutine, however the final value will not be retained. The value will revert to the previous value from when the subroutine wasa called.
 
 
 This can be written like this:
 
 ```csharp
  static void SquareIt(int x)
        {         

            x *= x;
            Console.WriteLine("The value inside the method: {0}", x);

        }

static void Main()
        {
            int n = 5;
            Console.WriteLine("The value before calling: {0}", n);

            SquareIt(n);  
            Console.WriteLine("The value after calling: {0}", n);
            
            Console.ReadLine();
        }
 
 
 ```
 
 By reference: allows the variable to be used within the subroutine and the final value in the subroutine will be retained after the subroutine is completed. The value as the subroutine was called will be overwritten with the new value from the subroutine.
 
 This can be written like this:
 
 ```csharp
   static void SquareIt(ref int x)
        {        
            x *= x;
            Console.WriteLine("The value inside the method: {0}", x);

        }

static void Main()
        {
            int n = 5;
            Console.WriteLine("The value before calling: {0}", n);

            SquareIt(ref n);  
            Console.WriteLine("The value after calling: {0}", n);
            
            Console.ReadLine();
        }


 ```
