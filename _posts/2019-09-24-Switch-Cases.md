--- 
layout: post
title: Switch Cases
categories: C# Programming
---
 
 Switch/case allows you to make a program do different things depending on the value of a variable. To do this we type:
 
 ```csharp
   Console.WriteLine("Enter a number from 1-3");
            int x = Convert.ToInt32(Console.ReadLine());

            switch (x)
            {
                case 1:
                    Console.WriteLine("You selected number 1");
                    break;

                case 2:
                    Console.WriteLine("You selected number 2");
                    break;

                case 3:
                    Console.WriteLine("You selected number 3");
                    break;
            }

            Console.ReadLine();
 
 ```
 To deal with options that havent been accounted for, we use the keyword default,
 
 ```csharp 

default:
        Console.WriteLine("The number entered was not ONEEEEEE, TWOOOOOOOOO or THREEEEEEEEEEEEEE");
        break;

 ```
