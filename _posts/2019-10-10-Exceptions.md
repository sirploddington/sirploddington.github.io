--- 
layout: post
title: Exceptions
categories: C# Programming Errors
---
 
 Runtime errors cause exceptions.
 
 They are lumps of data that describle something arroneus just happened and it can be used to see why to program has failed.
 
 If the exception is not caught, the program will fail.
 
 A program that will crash will look like this:
 
 ```csharp
 int i;
 i = Convert.ToInt32("one");
 
 ```
 
 To catch the error we use the try and catch method:
 
 ```csharp
 int i;
 try
 {
       i = Convert.ToInt32("one");
 }
 
 catch
 {
      Console.WriteLine("Invalid Entry");
 }
 
 Console.ReadLine();

 ```
 You wrap your potential problem code within the try command.
 
 If it causes an Exception the code within the catch command will be executed

 
 
