# C# Programming in Easy Steps

## Get started with .NET in 10 minutes

download and install the Microsoft .NET Core SDK   
(https://www.microsoft.com/net/learn/get-started/windows)

verify (at command prompt)   
`dotnet --version`

Hello World! console application

``` cmd

cd C:\apps
dotnet new console -o DotNetHello
cd DotNetHello
code .

```

open "Integrated Terminal" (from Visual Studio Code)   
`dotnet run`

create .exe   
`dotnet publish -c Release -r win10-x64`

## Get started with ASP.NET in 10 minutes (Web)
(https://www.microsoft.com/net/learn/apps/web/get-started/windows)

## First program (file Program.cs)

``` c#
using System;

namespace DotNetHello
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello World!");
            Console.ReadKey();
        }
    }
}

```

## C# Reserved Keywords

(https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/)  
