--- 
layout: post
title: 
categories: C# Programming Data-Storage
---
 
 
 creating writing file:
 
 ```csharp
 
  BinaryWriter bw = new BinaryWriter(new FileStream("mydata", FileMode.Create));
 
 ```
 
 writing to file
 
 ```csharp
 
bw.Write(k);

 ```
 
 closing file:
 
 ```csharp
 
bw.Close();

 ```
 
 creating reading file:
 
```csharp

BinaryReader br = new BinaryReader(new FileStream("mydata", FileMode.Open));

```
 
reading file; 
 
```csharp

i = br.ReadInt32();
Console.WriteLine("Integer data: {0}", i);
 d= br.ReadDouble();
 Console.WriteLine("Double data: {0}", d);
 b = br.ReadBoolean();
Console.WriteLine("Boolean data: {0}", b);
s = br.ReadString();
Console.WriteLine("String data: {0}", s);

```
 
 close file:
 
```csharp

br.Close();
```
