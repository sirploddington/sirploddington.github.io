--- 
layout: post
title: String Manipulation
categories: C# Programming
---
 
 Concatenation joins two strings together.
 
 We do this by:
 
 ```csharp
 string greeting = "Hello";
 string name = "Bob";
 string full = greeting+" "+name;
 Console.WriteLine(full);
 
 ```
 
 To convert strings into all upper case we use:
 
 ```csharp
 
 string upper = "meow";
 upper = upper.ToUpper();
 Console.WriteLine(upper);
 Console.ReadLine();


 ```
 
 
 To convert strings into all lower case we use:
 
 ```csharp
 
 string lower = "MEOW";
 lower = lower.ToLower();
 Console.WriteLine(lower);
 Console.ReadLine();
 
 ```
 
 To show the lengh of a string we use:
 
 ```csharp
 string lengh = "meooooooooooooooow";
            int size = lengh.Length;
            Console.WriteLine("meooooooooooooooow is " + size + " letters long");
            Console.ReadLine();
 
 ```

To create a substring we do

The (3,4) represents the positioning in the string.

```csharp

string greeting = "Hello Bob";
            string extract = greeting.Substring(3, 4);
            Console.WriteLine(extract);
            Console.ReadLine();
```




















