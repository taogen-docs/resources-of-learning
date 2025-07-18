# <img src="/assets/icon/programming-languages/C-sharp.png" width="24px"/> C# Resources

**Content**

- C# Fundamentals
- Utility Libraries
- Data Access
- Web Frameworks
- Web Security
- Microservices
- C# Tools
- Open-Source Projects
- Directions

## C# Fundamentals

Beginner

- Documentation
    - [C# documentation - doc]( https://docs.microsoft.com/en-us/dotnet/csharp/ )
- Online Tutorials
    - [Learn X in Y minutes - C#](https://learnxinyminutes.com/docs/csharp/)
    - [C# Tutorial - W3Schools](https://www.w3schools.com/cs/index.php)
    - [C# Tutorial - Tutorialspoint](https://www.tutorialspoint.com/csharp/index.htm)
    - [Learn C#](https://www.learncs.org/)
- **Head First C#** (4th, 2021) by Andrew Stellman
- **Learn C# in One Day and Learn It Well: C# for Beginners with Hands-on Project** by Jamie Chan
- **The C# Player's Guide** (5th, 2022) by RB Whitaker
- C# 10 Pocket Reference: Instant Help for C# 10 Programmers (2022) by Joseph Albahari, Ben Albahari
- C# 12 Pocket Reference: Instant Help for C# 12 Programmers (2023) by Joseph Albahari and Ben Albahari
- Pro C# 10 with .NET 6: Foundational Principles and Practices in Programming (11th, 2022) by Andrew Troelsen, Phil Japikse
- Professional C# and .NET (2021) by Christian Nagel

<details>
    <summary>C# vs .NET</summary>

C# is a programming language, .NET is a blanket term that tends to cover both the .NET Framework (an application framework library) and the Common Language Runtime which is the runtime in which .NET assemblies are run.

Microsoft's implementation of C# is heavily integrated with the .NET Framework so it is understandable that the two concepts would be confused.

-- 

You usually write C# code that runs on .NET.
.NET makes C# code portable, secure, and easier to build for various platforms.

C# is a language. .NET is the platform you use to run and develop C# applications.
You can’t really use C# without .NET (or at least some implementation of .NET).

</details>

Style Guide

- [Common C# code conventions](https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions)
- [C# at Google Style Guide](https://google.github.io/styleguide/csharp-style.html)

Project Structure

- [My Favorite C# Features - Part 4: Project Structure](https://dev.to/dotnet/my-favorite-c-features-part-4-project-structure-454p)
- [Common Practices In .NET Project Structure](https://www.c-sharpcorner.com/article/common-practices-in-net-project-structure/)

Advanced

- Dive into
    - **C# in Depth** (4th, 2019) by Jon Skeet. (C# 6 and 7)
    - C# 10 in a Nutshell: The Definitive Reference (2022) by Joseph Albahari, Ben Albahari
    - C# 12 in a Nutshell: The Definitive Reference (2023) by Joseph Albahari
    - CLR VIA C# (4th, 2012) by Jeffrey Richter. (C# 9 and .NET 5)
- Concurrency
    - Concurrency in C# Cookbook: Asynchronous, Parallel, and Multithreaded Programming (2nd, 2019) by Stephen Cleary
    - Concurrency in .NET: Modern patterns of concurrent and parallel programming by Riccardo Terrell
- Effective
    - Effective C#: 50 Specific Ways to Improve Your C# (3rd, 2016) by Bill Wagner. (C# 6)
    - More Effective C#: 50 Specific Ways to Improve Your C# (2nd, 2017) by Bill Wagner (C# 7)


## Utility Libraries

### Basic Utilities

General Purpose

--

Logging

- [Microsoft.Extensions.Logging](https://learn.microsoft.com/en-us/dotnet/core/extensions/logging?tabs=command-line)
- [Serilog](https://serilog.net/). Simple .NET logging with fully-structured events. Flexible, structured events — log file convenience.
- [Nlog](https://nlog-project.org/). Flexible and Structured Logging for various .NET Platforms. Flexible & free open-source logging for .NET
- Some more
  - ZLogger
  - Log4net
  - ELMAH

Unit Testing

- [xUnit.net](https://xunit.net/). A free, open source, community-focused unit testing tool for .NET.
- [NUnit](https://nunit.org/)
- [MSTest](https://learn.microsoft.com/en-us/dotnet/core/testing/unit-testing-csharp-with-mstest)
- [Moq](https://github.com/devlooped/moq). The most popular and friendly mocking framework for .NET
- [FluentAssertions](https://github.com/fluentassertions/fluentassertions). A very extensive set of extension methods that allow you to more naturally specify the expected outcome of a TDD or BDD-style unit tests.

JSON Parser

- [System.Text.Json](https://learn.microsoft.com/en-us/dotnet/api/system.text.json?view=net-9.0) (Built-in)
- [Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json). Popular high-performance JSON framework for .NET

Document Processing

- Microsoft documents
  - [IronWord](https://ironsoftware.com/csharp/word/). The C# DOCX Library.
  - [Microsoft Office Interop Word](https://learn.microsoft.com/en-us/dotnet/api/microsoft.office.interop.word?view=word-pia)
  - [Aspose.Words](https://products.aspose.com/words/). A family of native APIs for developers working in Python, .NET, C++, Node.js and Java
  - [DocX](https://github.com/xceedsoftware/DocX). Fast and easy to use .NET library that creates or modifies Microsoft Word files without installing Word.
  - Some more
    - FileFormat.Words
    - OfficeIMO
- CSV
  - [CsvHelper](https://joshclose.github.io/CsvHelper/). A .NET library for reading and writing CSV files. Extremely fast, flexible, and easy to use. Library to help reading and writing CSV files

HTTP Client

- [HttpClient](https://learn.microsoft.com/en-us/dotnet/api/system.net.http.httpclient?view=net-7.0) (Built-in)
- [Refit](https://reactiveui.github.io/refit/). The automatic type-safe REST library for .NET Core, Xamarin and .NET.
- [RestSharp](https://restsharp.dev/). Simple REST and HTTP API Client for .NET
- [Flurl](https://flurl.dev/). a modern, fluent, asynchronous, testable, portable, buzzword-laden URL builder and HTTP client library for .NET. Fluent URL builder and testable HTTP client for .NET

### More Utilities

Object mapping

- [AutoMapper](https://automapper.io/). The convention-based object-object mapper. Enforce naming conventions and optimize complex object and LINQ mapping to simple DTOs.

Date time handling

- [NodaTime](https://nodatime.org/). A better date and time API for .NET.

Data Handling

- [Humanizer](https://github.com/Humanizr/Humanizer). Humanizer meets all your .NET needs for manipulating and displaying strings, enums, dates, times, timespans, numbers and quantities

Crypto

- Bcrypt.net

Scheduling tasks

- [FluentScheduler](https://github.com/fluentscheduler/FluentScheduler). Automated job scheduler with fluent interface for the .NET platform.

Web scraping / HTML Parsing

- [AngleSharp](https://github.com/AngleSharp/AngleSharp). The ultimate angle brackets parser library parsing HTML5, MathML, SVG and CSS to construct a DOM based on the official W3C specifications.

Browser automation

- [Puppeteer Sharp](https://github.com/hardkoded/puppeteer-sharp). Headless Chrome .NET API

Resilience and transient-fault-handling

- [Polly](https://github.com/App-vNext/Polly). Polly is a .NET resilience and transient-fault-handling library that allows developers to express policies such as Retry, Circuit Breaker, Timeout, Bulkhead Isolation, and Fallback in a fluent and thread-safe manner.

## Data Access

Database Connectivity APIs

- [MySqlConnector](https://mysqlconnector.net/)

Connection Pools


Persistence/ORM Frameworks

- [Entity Framework Core (EF Core)](https://github.com/dotnet/efcore)
- [Dapper](https://www.learndapper.com/)
- [NHibernate](https://nhibernate.info/)
- Some more
    - [Marten](https://martendb.io/). .NET Transactional Document DB and Event Store on PostgreSQL
    - [PetaPOCO](https://github.com/CollaboratingPlatypus/PetaPoco). Official PetaPoco, A tiny ORM-ish thing for your POCO's
    - [RepoDB](https://github.com/mikependon/RepoDB). A hybrid ORM library for .NET.

Redis clients

- [CacheManager](https://github.com/MichaCo/CacheManager). CacheManager is an open source caching abstraction layer for .NET written in C#. It supports various cache providers and implements many advanced features.

MongoDB clients

- [mongo-csharp-driver](https://github.com/mongodb/mongo-csharp-driver). The Official C# .NET Driver for MongoDB.

Elasticsearch clients

- [elasticsearch-net](https://github.com/elastic/elasticsearch-net). This strongly-typed, client library enables working with Elasticsearch. It is the official client maintained and supported by Elastic.


## Web Frameworks

Books & Tutorials

- Programming C# 10: Build Cloud, Web, and Desktop Applications by Ian Griffiths

Web Frameworks

- [ASP.NET Core](https://dotnet.microsoft.com/en-us/apps/aspnet)

Web Development Libraries

- [FluentValidation](https://docs.fluentvalidation.net/en/latest/). A popular .NET validation library for building strongly-typed validation rules.
- [SignalR](https://dotnet.microsoft.com/en-us/apps/aspnet/signalr). Incredibly simple real-time web for .NET
- [SaaSKit](https://github.com/saaskit/saaskit). A developer toolkit for building SaaS applications
- [Swashbuckle](https://github.com/domaindrivendev/Swashbuckle.AspNetCore). Swagger tools for documenting API's built on ASP.NET Core.

Management System Scaffolds


## Web Security


## Microservices

API Gateway

- [Ocelot](https://github.com/ThreeMammals/Ocelot). .NET API Gateway

## C# Tools

IDE

- Rider
- Visual Studio Code

Package Manager

- [NuGet](https://www.nuget.org/)


## Open-Source Projects

**Recommended C# open source projects to read**

<details>
    <summary>Click to expand!</summary>

- Web Frameworks / Web APIs
  - [ASP.NET Core](https://github.com/dotnet/aspnetcore). Microsoft’s modern, cross-platform web framework. Learn middleware pipelines, dependency injection, routing, and asynchronous programming.
  - [Orchard Core](https://github.com/OrchardCMS/OrchardCore). Modular and multi-tenant CMS built on ASP.NET Core. Shows plugin architecture, extensibility, Razor views.
- Game Engines / Graphics
  - [MonoGame](https://github.com/MonoGame/MonoGame). Framework for making cross-platform games. Great for learning rendering, input handling, and game loops in C#.
  - [Ryujinx](https://github.com/Ryujinx/Ryujinx) (Nintendo Switch Emulator). Nintendo Switch emulator written in C#. High-performance computing, low-level CPU/GPU emulation, multithreading.
- Desktop Applications
  - [Avalonia](https://github.com/AvaloniaUI/Avalonia). A cross-platform WPF-style UI framework. Learn MVVM pattern, control templating, platform abstraction.
  - [Fluent Terminal](https://github.com/felixse/FluentTerminal). A beautiful terminal emulator for Windows. Learn UWP/WinUI design, async/await usage, and terminal integration.
- Libraries / Utilities
  - [Serilog](https://github.com/serilog/serilog). Structured logging library. Learn plug-in architecture, logging best practices, sinks and enrichers.
  - [Polly](https://github.com/App-vNext/Polly). Resilience and transient-fault-handling library. Learn fluent API design, retry/circuit breaker patterns.
  - [AutoMapper](https://github.com/AutoMapper/AutoMapper). Object-to-object mapper. Learn convention over configuration, use of generics, expression trees.
- Testing and Analysis Tools
  - [NUnit](https://github.com/nunit/nunit). Popular testing framework. Learn test runners, attribute-based design, assertions.
  - [coverlet](https://github.com/coverlet-coverage/coverlet). Cross-platform code coverage tool for .NET. Learn integration with MSBuild, instrumentation logic.
- Compilers / Language Tools
  - [Roslyn](https://github.com/dotnet/roslyn) (C# Compiler). The .NET compiler platform (C# and VB.NET). Learn ASTs, analyzers, code refactoring, language services.
  - [ILSpy](https://github.com/icsharpcode/ILSpy). .NET assembly browser and decompiler. Learn IL parsing, GUI app, plugin architecture.
- Dev Tools / CLI
  - [PowerShell (Core)](https://github.com/PowerShell/PowerShell). Cross-platform shell and scripting language. Learn scripting engine, .NET interoperability, command parsing.
  - [NuGet Client](https://github.com/NuGet/NuGet.Client). CLI and libraries for interacting with NuGet packages. Learn about package management, dependency resolution.

</details>

**Application Projects**


## Directions

>C# (pronounced "C-sharp") is a modern, object-oriented programming language developed by Microsoft. It’s widely used in Windows application development, game development, web backends, and increasingly in cross-platform mobile and cloud-based solutions via the .NET ecosystem.

| Field                | Example Use Cases                               |
| -------------------- | ----------------------------------------------- |
| Windows Desktop Apps | WPF, WinForms, internal tools                   |
| Web Development      | ASP.NET Core websites and APIs                  |
| Game Development     | Unity 2D/3D games, VR/AR                        |
| Mobile Development   | Xamarin, .NET MAUI cross-platform apps          |
| Enterprise Software  | CRM, ERP, business automation                   |
| Cloud Services       | Azure cloud-native services and serverless apps |
| IoT                  | Smart devices, Windows IoT Core projects        |
| Data & AI            | ML.NET, AI services integration                 |


### Cross-Platform Application Development

- C# 10 and .NET 6 – Modern Cross-Platform Development by Mark J. Price

