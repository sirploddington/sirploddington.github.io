--- 
layout: post
title: Text Files
categories: C# Programming
---
 
 To use StreamWriter to open and write to text files, an extra line of code in the library section at the top.
 
 The one used is;
 
 ```csharp
 using System.IO
 
 ```
 
 To open a text file you write:
 
 ```csharp
 
sing (StreamWriter sw = new StreamWriter("TestFile.txt"))

 ```
  
 To add text to a text file you write:
 
 ```csharp
 
sw.WriteLine("Hello World");

 ```
