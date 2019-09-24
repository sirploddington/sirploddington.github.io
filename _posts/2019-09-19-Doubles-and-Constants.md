--- 
layout: post
title: Doubles and Constants
categories: C# Programming
---
 Doubles are used to represent decimal numbers.
 To create a double we use the command 'double'
 
 ```csharp
 Console.WriteLine("Enter number of cenitmetres");
 int cm = Convert.ToInt32(Console.ReadLine());
 double feet;
 feet = cm / 30.48;
 Console.WriteLine(cm + " centimetres is the same as " + feet + " feet.");
 Console.ReadLine();
 
 ```
 Constants are not changed and usually displayed in capitals.
 To create a constant we use the command 'const'
 
 ```csharp
 Console.WriteLine("Enter the radius in cms");
const double PI = 3.14159;
double radius = Convert.ToDouble(Console.ReadLine());
double area = PI * radius * radius;
Console.WriteLine("The area of the cirlce is " + area + "cm squared");
Console.ReadLine();

 ```
 
