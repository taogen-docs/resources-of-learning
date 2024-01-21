# Programming Language Resources

**Content**

- <a name="lang_c" href="#lang_t">Programming Languages</a>
- <a name="nonturinglang_c" href="#nonturinglang_t">Non-Turing-Complete Languages</a>
- <a name="pgmprd_c" href="#pgmprd_t">Programming Paradigms</a>
- <a name="mfp_c" href="#mfp_t">Metaphors for Programming</a>
- <a name="mfpl_c" href="#mfpl_t">Metaphors for Programming Languages</a>

<br>

<h2><a name="lang_t" href="#lang_c">Programming Languages</a></h2>

<br>

### C

Primary

- **The C Programming Language** (2nd, 1988) by Brian W. Kernighan, Denis M. Ritchie (**TCPL**)
- C Primer Plus (6th, 2013) by Stephen Prata

Advanced

- Pointers on C (1997) by Kenneth A·Reek 
- Expert C Programming: Deep C Secrets (1994) by Peter van der Linden 
- C Traps and Pitfalls (1989) by Andrew Koenig

### C++

**Primary**

Introductory, no previous programming experience

- **C++ Primer** (5th, 2012) by Josée Lajoie and Stanley B. Lippman
- Programming: Principles and Practice Using C++ by Bjarne Stroustrup

Introductory, with previous programming experience

- **A Tour of C++** (3rd, 2022) by Bjarne Stroustrup
- Accelerated C++: Practical Programming by Example by Andrew Koenig
- Essential C++ by Stanley B. Lippman

Best practices

- **Effective C++** (3rd, 2005) by Scott Meyers
- Effective Modern C++ (2014) by Scott Meyers
- Effective STL (2001) by Scott Meyers

**Intermediate**

- More Effective C++ (1996) by Scott Meyers
- Exceptional C++: 47 Engineering Puzzles, Programming Problems, and Solutions by Herb Sutter
- More Exceptional C++ by Herb Sutter
- Exceptional C++ Style: 40 New Engineering Puzzles, Programming Problems, and Solutions by Herb Sutter
- C++ Coding Standards: 101 Rules, Guidelines, and Best Practices by Herb Sutter, Andrei Alexandrescu
- C++ Templates: The Complete Guide by David Vandevoorde, Nicolai M. Josuttis
- C++ 17 The Complete Guide by Nicolai M. Josuttis
- C++ In Action: Industrial Strength Programming Techniques by Bartosz Milewski
- Functional Programming in C++ by Ivan Čukić
- Professional C++ by Marc Gregoire, Nicholas A. Solter, Scott J. Kleper

**Advanced**

- Dive into
  - Modern C++ Design: Generic Programming and Design Patterns Applied by Andrei Alexandrescu, Scott Meyers, John Vlissides
  - C++ Template Metaprogramming: Concepts, Tools, and Techniques from Boost and Beyond by David Abrahams, Aleksey Gurtovoy
  - Advanced C++ Metaprogramming by Davide Di Gennaro
  - Large-Scale C++ Volume I: Process and Architecture by John S. Lakos
  - The C++ Standard Library  (2nd, 2012) by Nikolai Josuttis
  - STL源码剖析 by 侯捷
- Concurrency
  - C++ Concurrency in Action: Practical Multithreading by Anthony Williams
- Network
  - C++ Network Programming, Volume I: Mastering Complexity with ACE and Patterns
    by Douglas C. Schmidt, Stephen D. Huston
  - C++ Network Programming, Volume 2: Systematic Reuse with Ace and Frameworks
    by Douglas C. Schmidt, Stephen D. Huston
- Efficient
  - C++ High Performance: Master the art of optimizing the functioning of your C++ code (2nd, 2020) by Bjorn Andrist, Viktor Sehr
  - The Art of Writing Efficient Programs: An advanced programmer's guide to efficient hardware utilization and compiler optimizations using C++ examples by Fedor G. Pikus 


Reference Style - All Levels

- **The C++ Programming Language** (4th, 2013) by Bjarne Stroustrup

  [Where do I find the current C or C++ standard documents?](https://stackoverflow.com/questions/81656/where-do-i-find-the-current-c-or-c-standard-documents)

- C++ Standard Library: A Tutorial and Reference by Nicolai M. Josuttis

- Standard C++ Iostreams and Locales: Advanced Programmer's Guide and Reference by Klaus Kreft

- [C++ reference - DOC](https://en.cppreference.com/w/)

Classics / Older

- The Design and Evolution of C++ by Bjarne Stroustrup
- Ruminations on C++: A Decade of Programming Insight and Experience by Andrew Koenig, Barbara E. Moo
- Advanced C++ Programming Styles and Idioms by James O. Coplien
- Large-Scale C++ Software Design (1996)  by John Lakos
- **Inside the C++ Object Model** (1996) by Stanley B. Lippman
- Thinking in C++, Vol. 1: Introduction to Standard C++ (2nd, 2000)  by Bruce Eckel 
- Thinking in C++, Volume 2: Practical Programming by Bruce Eckel and Chuck Allison
- Scientific and Engineering C++: An Introduction with Advanced Techniques and Examples by John J. Barton
- Generic Programming and the STL: Using and Extending the C++ Standard Template Library by Matthew H. Austern


Courses

- C++面向对象开发 by 侯捷
- STL 标准库与泛型编程 by 侯捷
- C++新标准 C++11/14 by 侯捷
- C++ 内存管理机制 by 侯捷
- C++ Startup 揭秘 by 侯捷

Web Frameworks

- [Crow](https://crowcpp.org/master/) - Fast and easy. Microframework.
- [Oat++](https://oatpp.io/) - Highly scalable and resource-efficient.
- [Drogon](https://drogon.org/) - Fast.
- [POCO](https://pocoproject.org/) - Simple.

Tools

- IDE: CLion, Visual Studio Code
- Package Management: [Conan](https://conan.io/)

### Go [📈](https://www.tiobe.com/tiobe-index/go/)

Primary

- [Go Documentation - doc](https://golang.org/doc/)
- **The Go Programming Language** (2015) by Alan A. A. Donovan and Brian W. Kernighan
- **Learning Go: An Idiomatic Approach to Real-World Go Programming** (2nd, 2024) by Jon Bodner
- **Head First Go** (2019) by Jay McGavren
- An Introduction to Programming in Go by Caleb Doxsey
- Introducing Go: Build Reliable, Scalable Programs by Caleb Doxsey
- Go Programming Blueprints by Mat Ryer
- Go in Action by William Kennedy, Brian Ketelsen
- Go in Practice by Matt Butcher

Advanced

- Concurrency
  - **Concurrency in Go: Tools and Techniques for Developers** (2017) by Katherine Cox-Buddy
- Efficient
  - Efficient Go: Data-Driven Performance Optimization by Bartlomiej Plotka
  - 100 Go Mistakes and How to Avoid Them (2022) by Teiva Harsanyi

Application Development

<details>
    <summary>关于 Go Web 框架 - Click to expand!</summary>
不建议用 Go 写 Web ，可以用来完成一些基础设施类工作。Go 这边的 Web 框架，比如 gin 那种，其实都是非常轻量级的，属于 http 增强库，和 spring 全家桶不是一回事。Go 这边我觉得可以认为不具有诞生 springboot 类的土壤。

Go 的 Web 框架基本都是标准库套壳。也可以看看 fiber 这种用 fasthttp 的。

Go 是用来写底层服务的，不适合写应用层面的东西。

gin，其他想要什么组件可以自己加上去。

可以自己试着用用，组合出一套顺手的技术栈。
</details>

- **Cloud Native Go: Building Reliable Services in Unreliable Environments** (2021) by Matthew Titmus
- Go Web Programming by Chang Sau Sheong

Tutorials

- [go dev](https://go.dev/)
- [Go Tutorial - tutorialspoint](https://www.tutorialspoint.com/go/)
- [Go by Example](https://gobyexample.com/)
- [gotraining - GitHub](https://github.com/ardanlabs/gotraining/tree/master/topics/go)
- [awesome-go - GitHub](https://github.com/avelino/awesome-go)
- [project-layout - Standard Go Project Layout](https://github.com/golang-standards/project-layout)

Guidance

- [golang-developer-roadmap - GitHub](https://github.com/Alikhll/golang-developer-roadmap)

Projects

- [Projects - go Wiki](https://github.com/golang/go/wiki/Projects)

Web Frameworks

- [Gin](https://gin-gonic.com/)
- [FastHTTP](https://github.com/valyala/fasthttp)
- [Echo](https://echo.labstack.com/) - High-performance.
- [Beego](https://github.com/beego/beego) - High-performance.
- [Fiber](https://gofiber.io/) - Rapid development.

Tools

- IDE: GoLand, Visual Studio Code
- Package Management: [Go Modules](https://go.dev/ref/mod)

### Rust

Primary

- [The Rust Programming Language - doc]( https://doc.rust-lang.org/1.30.0/book/first-edition/documentation.html )
- [Rust Documentation - doc]( https://doc.rust-lang.org/beta/ )
- [Learn Rust - doc](https://rust-lang.org/learn)
- **The Rust Programming Language** (2nd, 2023) by Carol Nichols and Steve Klabnik
- **Rust for Rustaceans: Idiomatic Programming for Experienced Developers** (2021) by Jon Gjengset
- **Programming Rust: Fast, Safe Systems Development** (2021) by Jason Orendorff and Jim Blandy
- Command-Line Rust: A Project-Based Primer for Writing Rust CLIs by Ken Youens-Clark
- Rust Programming By Example: Enter the World of Rust by Building Engaging, Concurrent, Reactive, and Robust Applications by Antoni Boucher and Guillaume Gomez
- Rust in Action by Tim McNamara

Advanced

- Concurrency
  - **Rust Atomics and Locks: Low-Level Concurrency in Practice** (2023) by Mara Bos
  - Hands-On Concurrency with Rust: Confidently Build Memory-Safe, Parallel, and Efficient Software in Rust by Brian L Troutwine

Application Development

- **Zero To Production In Rust: An introduction to backend development** (2022) by Luca Palmieri
- Programming WebAssembly with Rust: Unified Development for Web, Mobile, and Embedded Applications by Kevin Hoffman

Web Frameworks

- [Actix](https://actix.rs/)
- [Rocket](https://rocket.rs/) - Simple.
- [Axum](https://github.com/tokio-rs/axum) - Ergonomic and modular.
- [Warp](https://github.com/seanmonstar/warp) - Easy, composable.

Tools

- IDE: RustRover, Visual Studio Code
- Package Management: [Cargo](https://doc.rust-lang.org/cargo)


### Julia

- [Julia 1.4 Documentation](https://docs.julialang.org/en/v1/)
- [Julia learning resources](https://julialang.org/learning/)

### D

- **D** is a general-purpose programming language with static typing, systems-level access, and C-like syntax. With the D Programming Language, write fast, read fast, and run fast.
- The D Programming Language by Andrei Alexandrescu

### Lua

- [Lua Documentation - doc]( https://www.lua.org/docs.html )
- Programming in Lua by Roberto Ierusalimschy
- Lua Programming Gems by Luiz Henrique de Figueiredo, Waldemar Celes, Roberto Ierusalimschy
- Beginning Lua programming by Kurt Jung
- Lua Quick Start Guide: The Easiest Way to Learn Lua Programming by Gabor Szauer
- Lua 5.2 Reference Manual by Luiz Henrique de Figueiredo, Roberto Ierusalimschy, and Waldemar Celes

### Visual Basic

- [Visual Basic language reference](https://docs.microsoft.com/en-us/office/vba/language/reference/user-interface-help/visual-basic-language-reference)

### C#

Primary

- [C# documentation - doc]( https://docs.microsoft.com/en-us/dotnet/csharp/ )
- **Head First C#** (4th, 2021) by Andrew Stellman
- **Learn C# in One Day and Learn It Well: C# for Beginners with Hands-on Project** by Jamie Chan
- **The C# Player's Guide** (5th, 2022) by RB Whitaker
- C# 10 Pocket Reference: Instant Help for C# 10 Programmers (2022) by Joseph Albahari, Ben Albahari
- C# 12 Pocket Reference: Instant Help for C# 12 Programmers (2023) by Joseph Albahari and Ben Albahari
- Pro C# 10 with .NET 6: Foundational Principles and Practices in Programming (11th, 2022) by Andrew Troelsen, Phil Japikse
- Professional C# and .NET (2021) by Christian Nagel

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

Applications Development

- Programming C# 10: Build Cloud, Web, and Desktop Applications by Ian Griffiths
- C# 10 and .NET 6 – Modern Cross-Platform Development by Mark J. Price

Web Frameworks

- [ASP.NET Core](https://dotnet.microsoft.com/en-us/apps/aspnet)

Tools

- IDE: Rider, Visual Studio Code
- Package Management: [NuGet](https://www.nuget.org/)

### JavaScript 📈

Reference [Web Frontend Resources - JavaScript](../directions/web-frontend-resources.md#js_t)


### Java

Reference [Java Resources](../directions/java-resources.md)

### Ruby 📉

- [Ruby Documentation - doc]( https://www.ruby-lang.org/en/documentation/ )
- The Well-Grounded Rubyist by David A. Black
- Programming Ruby: The Pragmatic Programmers' Guide by Dave Thomas, Chad Fowler, and Andy Hunt
- Eloquent Ruby by Russ Olsen
- Why's (Poignant) Guide to Ruby by Why The Lucky Stiff
- The Ruby Programming Language by David Flanagan, Yukihiro Matsumoto, Why The Lucky Stiff
- The Rails Way by Obie Fernandez
- Agile Web Development with Rails: A Pragmatic Guide by Dave Thomas
- Practical Object Oriented Design in Ruby by Sandi Metz

Web Frameworks

- [Ruby on Rails](https://rubyonrails.org/)
- [Hanami](https://hanamirb.org/) - Simplicity.
- [Padrino](https://padrinorb.com/) - Elegant.
- [Sinatra](https://sinatrarb.com/) - Rapid development.

Tools

- IDE: RubyMine, Visual Studio Code
- Package Management: [RubyGems](https://rubygems.org/)

### PHP 📉

- [PHP Documentation - doc]( https://www.php.net/docs.php )
- [PHP: The Right Way by Josh Lockhart](https://phptherightway.com/)
- Learning PHP, MySQL, JavaScript, CSS & HTML5: A Step-by-Step Guide to Creating Dynamic Websites by Robin Nixon
- Head First PHP and MySQL by Lynn Beighley and Michael Morrison
- PHP and MySQL Web Development by Luke Welling
- Modern PHP: New Features and Good Practices by Josh Lockhart
- Murach's PHP and MySQL by Joel Murach and Ray Harris
- PHP Cookbook by Adam Trachtenberg and David Sklar
- Programming PHP by Rasmus Lerdorf, Kevin Tatroe, Peter MacIntyre
- PHP Objects, Patterns, and Practice by Matt Zandstra
- PHP for the Web: Visual QuickStart Guide by Larry Ullman
- PHP 6 and MySQL 5 for Dynamic Web Sites: Visual Quickpro Guide by Larry Ullman

Web Frameworks

- [Laravel](https://laravel.com/) - Elegant.
- [Symfony](https://symfony.com/) - High performance.
- [Codeigniter](https://www.codeigniter.com/) - Lightweight.
- [Yii](https://www.yiiframework.com/) - Fast, secure, and efficient.
- [Laminas (Zend Framework)](https://getlaminas.org/) - Secured.
- [Phalcon](https://phalcon.io/en-us) - High performance.
- [CakePHP](https://cakephp.org/) - Rapid development.

Tools

- IDE: PhpStorm, Visual Studio Code
- Package Management: [Composer](https://getcomposer.org/)

### Python 📈

Prime

- [The Python Tutorial - doc](https://docs.python.org/3/tutorial/)
- [Python Documentation](https://www.python.org/doc/)
- [Beginner's Guide to Python](https://wiki.python.org/moin/BeginnersGuide)
- [Learn Python in Y minutes](https://learnxinyminutes.com/docs/python/)
- [Python Tutorial - w3c schools](https://www.w3schools.com/python/default.asp)
- [Python Tutorial - tutorialspoint](https://www.tutorialspoint.com/python/)
- [Python Tutorial](https://www.pythontutorial.net/)
- [learnpython.org](https://www.learnpython.org/)
- [Real Python](https://realpython.com/)
- **Learning Python** (5th, 2013) by David Ascher and MARK LUTZ
- Learn Python 3 the Hard Way: A Very Simple Introduction to the Terrifyingly Beautiful World of Computers and Code by Zed Shaw
- A Byte of Python by Swaroop C.H. [LINK](https://python.swaroopch.com/)
- **Automate the Boring Stuff with Python: Practical Programming for Total Beginners** (3rd, 2024) by Al Sweigart
- **Python Crash Course: A Hands-On, Project-Based Introduction to Programming** (3rd, 2023) by Eric Matthes
- **Python Pocket Reference: Python In Your Pocket** (5th, 2014) by Mark Lutz 
- **Think Python** (2nd, 2016) by Allen B. Downey
- **Dive into Python 3** (2009) by Mark Pilgrim
- Python Essential Reference by David M. Beazley
- Introducing Python: Modern Computing in Simple Packages (2nd, 2019) by Bill Lubanovic
- Core Python Programming by Wesley J. Chun
- Python Basics: A Practical Introduction to Python 3 (2021) by David Amos, Dan Bader
- Python Tricks: A Buffet of Awesome Python Features (2017) by Dan Bader
- The Quick Python Book (3rd, 2018) by Naomi Ceder

Advanced

- Dive into
  - Python Cookbook: Recipes for Mastering Python 3 by Brian K. Jones and David M. Beazley
  - **Fluent Python** (2nd, 2022) by Luciano Ramalho
  - The Hacker's Guide to Python by Julien Danjou
  - CPython Internals: Your Guide to the Python 3 Interpreter by Anthony Shaw
  - Cython: A Guide for Python Programmers (2015) by Kurt W Smith
  - Classic Computer Science Problems in Python (2019) by David Kopec
  - Pro Python by Marty Alchin
  - Expert Python Programming by Tarek Ziadé
- Effective
  - Effective Python: 59 Specific Ways to Write Better Python by Brett Slatkin
  - High Performance Python: Practical Performant Programming for Humans by Ian Ozsvald and Micha Gorelick
  - The Hitchhiker's Guide to Python: Best Practices for Development by Kenneth Reitz, Tanya Schlusser
- Object-Oriented
  - **Programming Python: Powerful Object-Oriented Programming** (4th. 2011) by Mark Lutz


New Books

- Python Workout: 50 ten-minute exercises (2020) by Reuven M. Lerner
- Tiny Python Projects: 21 small fun projects for Python beginners designed to build programming skill, teach new algorithms and techniques, and introduce software testing (2020) by Ken Youens-Clark 
- Classic Computer Science Problems in Python (2019) by David Kopec 
- Beyond the Basic Stuff with Python: Best Practices for Writing Clean Code (2020) by Al Sweigart
- Python for Excel: A Modern Environment for Automation and Data Analysis (2021) by Felix Zumstein
- Architecture Patterns with Python: Enabling Test-Driven Development, Domain-Driven Design, and Event-Driven Microservices (2020) by Harry Percival, Bob Gregory
- Python for DevOps: Learn Ruthlessly Effective Automation (2020) by Noah Gift, Kennedy Behrman, Alfredo Deza, Grig Gheorghiu
- Using Asyncio in Python: Understanding Python's Asynchronous Programming Features (2020) by Caleb Hattingh 
- Mastering Large Datasets with Python: Parallelize and Distribute Your Python Code (2020) by John T. Wolohan 
- Practices of the Python Pro (2020) by Dane Hillard
- Real-World Python: A Hacker's Guide to Solving Problems with Code (2020) by Lee Vaughan
- Python One-Liners: Write Concise, Eloquent Python Like a Professional (2020) by Christian Mayer
- Cracking Codes with Python: An Introduction to Building and Breaking Ciphers (2018) by Al Sweigart
- Impractical Python Projects: Playful Programming Activities to Make You Smarter (2018) by Lee Vaughan
- Serious Python: Black-Belt Advice on Deployment, Scalability, Testing, and More (2018) by Julien Danjou


Some More

- Python Tricks: A Buffet of Awesome Python Features by Dan Bader
- Crawler
  - Reference [CS Advanced Domains Resources - Crawler and Anti-Crawler](../_cs-advanced-domains-resources.md#crawler)
- Data Science
  - Python for Data Analysis by Wes McKinney
  - Intro to Python for Computer Science and Data Science by Paul Deitel, Harvey Deitel
- AI
  - Machine Learning (TensorFlow)
    - Introduction to Machine Learning with Python: A Guide for Data Scientists by Andreas C. Müller and Sarah Guido
    - Machine Learning Pocket Reference: Working with Structured Data in Python (2019) by Matt Harrison 
    - Hands-On Machine Learning with Scikit-Learn, Keras, and Tensorflow: Concepts, Tools, and Techniques to Build Intelligent Systems by Aurélien Géron
    - TensorFlow 2 Pocket Reference: Building and Deploying Machine Learning Models by KC Tung 
  - Deep Learning (PyTorch)
    - Deep Learning with Python by François Chollet
    - Deep Learning with PyTorch: Build, train, and tune neural networks using Python tools by Eli Stevens, Luca Antiga, Thomas Viehmann
    - Deep Learning for Coders with Fastai and PyTorch: AI Applications Without a PhD by Jeremy Howard, Sylvain Gugger
    - PyTorch Pocket Reference: Building and Deploying Deep Learning Models by Joe Papa
  - NLP (Transformers)
    - Natural Language Processing in Action: Understanding, analyzing, and generating text with Python (2019) by Hobson Lane, Hannes Hapke, Cole Howard
    - Natural Language Processing with Transformers by Lewis Tunstall, Leandro von Werra, Thomas Wolf

Resources

- [Python Challenge](http://www.pythonchallenge.com/)
- [awesome-python - GitHub](https://github.com/vinta/awesome-python)
- [Python Tips](https://pythontips.com/)
- [Full Stack Python](https://www.fullstackpython.com/)

Web Frameworks

- Full Stack
  - [Django](https://www.djangoproject.com/) - Rapid development.
  - [Web2Py](http://www.web2py.com/) - Rapid development.
  - [Pyramid](https://trypyramid.com/) - Scalable. Start small, finish big.
  - [Turbo Gears](https://turbogears.org/) - Scalable. Start small, finish big.
- Micro/Lightweight
  - [Flask](https://flask.palletsprojects.com/)
  - [CherryPy](https://docs.cherrypy.dev/en/latest/) - Minimalist.
  - [Bottle](https://bottlepy.org/docs/dev/) - Fast, simple and lightweight.
  - [Falcon](https://falcon.readthedocs.io/en/stable/) - Fast, minimalist.
- Asynchronous
  - [Sanic](https://sanic.dev/en/)
  - [AIOHTTP](https://docs.aiohttp.org/en/stable/)
  - [Tornado](https://www.tornadoweb.org/en/stable/)
- Web API
  - [FastAPI](https://fastapi.tiangolo.com/)
- Others
  - [CubicWeb](https://www.cubicweb.org/)

Tools

- IDE: PyCharm, Visual Studio Code
- Package Management: [pip](https://pypi.org/project/pip/)

### Android

- [Android Documentation - doc](https://developer.android.com/docs)
- Android Programming: The Big Nerd Ranch Guide by Brian Hardy, Bill Phillips
- Head First Android Development: A Brain-Friendly Guide by DAVID GRIFFITHS and Dawn Griffiths
- The Busy Coder's Guide to Advanced Android Development by Mark Murphy
- Android Programming: Pushing the Limits by Erik Hellman
- Professional Android 4 Application Development by Reto Meier
- Learning Android by Marko Gargenta
- Programming Android: Java Programming for the New Generation of Mobile Devices by Zigurd Mednieks, Laird Dornin, G. Blake Meike, Masumi Nakamura

#### Android in Kotlin

- [Android Basics in Kotlin](https://developer.android.com/courses/android-basics-kotlin/course)

#### Android Studio

- [Android Studio User Guide](https://developer.android.com/studio/intro)


### Kotlin 📈

- [Kotlin Reference - doc]( https://kotlinlang.org/docs/reference/ )
- Kotlin in Action by Dmitry Jemerov and Svetlana Isakova
- The Joy of Kotlin by Pierre Yves Saumont
- Kotlin for Android Developers by Antonio Leiva
- Head First Kotlin: A Brain-Friendly Guide by David Griffiths and Dawn Griffiths
- Fundamental Kotlin by Miloš Vasić

### Objective-C

- [Programming with Objective-C - doc]( https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html )
- [The Objective-C Programming Language - doc]( https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/ObjectiveC/Introduction/introObjectiveC.html )
- [Apple Developer Documentation - doc]( https://developer.apple.com/documentation )
- [iOS Example](https://iosexample.com/)
- Programming in Objective-C by Stephen G. Kochan
- Objective-C Programming: The Big Nerd Ranch Guide by Aaron Hillegass and Mikey Ward
- Effective Objective-C 2.0: 52 Specific Ways to Improve Your IOS and OS X Programs by Matt Galloway
- iOS Programming: The Big Nerd Ranch Guide by Aaron Hillegass and Joe Conway
- Learning Cocoa with Objective-C: Developing for the Mac and IOS App Stores by Jon Manning and Paris Buttfield-Addison
- Learn Objective-C on the Mac by Mark Dalrymple, Scott Knaster

Courses

- [CS193p - Developing Apps for iOS](https://cs193p.sites.stanford.edu/) by Stanford University

### Swift

- [Swift Documentation - doc]( https://swift.org/documentation/ )
- Swift in Depth by Tjeerd in 't Veen
- IOS 12 Programming for Beginners: An Introductory Guide to IOS App Development with Swift 4.2 and Xcode 10 (3rd, 2018) by Craig Clayton
- IOS 10 Programming Fundamentals with Swift: Swift, Xcode, and Cocoa Basics by Matt Neuburg
- Swift 5 for Absolute Beginners: Learn to Develop Apps for iOS by Stefan Kaczmarek, Brad Lees, Gary Bennett

### Lisp

- [Lisp Documentation - doc]( https://common-lisp.net/documentation )
- Practical Common Lisp by Peter Seibel
- Paradigms of AI Programming: Case Studies in Common Lisp by Peter Norvig
- Common LISP: A Gentle Introduction to Symbolic Computation by David S. Touretzky
- Structure and Interpretation of Computer Programs by Gerald Jay Sussman and Hal Abelson
- On Lisp by Paul Graham
- Land of Lisp: Learn to Program in Lisp, One Game at a Time! by Conrad Barski
- Common Lisp the Language by Guy L. Steele Jr.
- ANSI Common Lisp by Paul Graham
- The Little Schemer by Daniel P. Friedman and Matthias Felleisen


### Haskell

- [Haskell Documentation - doc]( https://www.haskell.org/documentation/ )
- Real World Haskell: Code You Can Believe In by Bryan O'Sullivan
- Programming in Haskell by Graham Hutton
- Learn You a Haskell for Great Good! by Miran Lipovača
- Parallel and Concurrent Programming in Haskell: Techniques for Multicore and Multithreaded Programming by Simon Marlow
- Haskell Programming From First Principles by Christopher Allen, Julie Moronuki
- Get Programming with Haskell by Will Kurt
- Thinking Functionally with Haskell by Richard S. Bird
- Learn You a Haskell for Great Good!: A Beginner's Guide by Miran Lipovača
- Haskell: The Craft of Functional Programming by Simon Thompson

Web Frameworks

- Full Stack
	- [Yesod](https://www.yesodweb.com/)
- API
	- [Servant](https://www.servant.dev/)

### Clojure

- [Clojure Documentation](https://clojure.org/guides/getting_started)
- Clojure for the Brave and True: Learn the Ultimate Language and Become a Better Programmer (2015) by Daniel Higginbotham
- Programming Clojure (3rd, 2018) by Alex Miller, Stuart Halloway, Aaron Bedra
- Getting Clojure: Build Your Functional Skills One Idea at a Time (2018) by Russ Olsen
- The Joy of Clojure (2nd, 2014) by Michael Fogus, Chris Houser
- Living Clojure: An Introduction and Training Plan for Developers (2015) by Carin Meier
- Elements of Clojure (2019) by Zachary Tellman
- Clojure Programming: Practical Lisp for the Java World (2012) by Chas Emerick, Christophe Grand, Brian Carper
- Clojure Applied: From Practice to Practitioner (2015) by Ben Vandgrift, Alex Miller
- Mastering Clojure Macros: Write Cleaner, Faster, Smarter Code (2014) by Colin Jones
- Clojure in Action (2nd, 2016) by Amit Rathore, Francis Avila

Web Development

- Web Development with Clojure (3rd, 2021) by Dmitri Sotnikov and Scot Brown
- Clojure Web Development Essentials (2015) by Ryan Baldwin

Web Frameworks

> The majority of web development in Clojure is done with a collection of libraries chosen by the development team, depending on their preferences and their needs, rather than frameworks.

- [Luminus](https://luminusweb.com/) - micro-framework
- Coast
- Biff

Dependency Management

- [Leiningen](https://leiningen.org/)

### Perl

- [Perl 5.30.0 documentation]( https://perldoc.perl.org/ )
- [Perl Docs]( https://www.perl.org/docs.html )
- Learning Perl by Randal L. Schwartz
- Beginning Perl by Curtis 'Ovid' Poe
- Programming Perl by Tom Christiansen
- Perl Cookbook by Tom Christiansen, Nathan Torkington
- Modern Perl by chromatic
- Intermediate Perl by Randal L. Schwartz, Brian D. Foy, Tom Phoenix
- Perl Best Practices: Standards and Styles for Developing Maintainable Code by Damian Conway
- Mastering Perl by Brian D. Foy
- Higher-Order Perl: Transforming Programs with Programs by Mark Jason Dominus
- Object Oriented Perl: A Comprehensive Guide to Concepts and Programming Techniques by Damian Conway, Randal L. Schwartz

### Groovy

- [Groovy Documentation - doc]( https://groovy-lang.org/documentation.html )
- [Learn Groovy in Y minutes](https://learnxinyminutes.com/docs/groovy/)
- [Refcard Groovy A Rapid-Development JVM Language - DZone](https://dzone.com/refcardz/groovy). a cheat sheet.
- Groovy in Action by Dierk König, Andrew Glover, Paul King, Guillaume Laforge, Jon Skeet, James Gosling
- Programming Groovy 2: Dynamic Productivity for the Java Developer by Venkat Subramaniam
- Making Java Groovy by Kenneth A. Kousen
- Groovy 2 Cookbook by Andrey Adamovich and Luciano Fiandesio
- Grails in Action by Glen Smith, Peter Ledbrook
- The definitive guide to Grails by Graeme Keith Rocher

### Scala

- [Scala Documentation - doc]( https://docs.scala-lang.org/ )
- Programming in Scala by Bill Venners and Martin Odersky
- Functional Programming in Scala by Paul Chiusano and Rúnar Bjarnason
- Scala for the Impatient by Cay S. Horstmann
- Scala in Depth by Joshua D. Suereth
- Scala Cookbook: Recipes for Object-Oriented and Functional Programming by Alvin Alexander
- Programming Scala: Scalability = Functional Programming + Objects by Alex Payne and Dean Wampler
- Scala in Action by Nilanjan Raychaudhuri
- Functional Programming, Simplified: (Scala Edition) by Alvin Alexander
- Learning Scala: Practical Functional Programming for the JVM by Jason Swartz
- Scala Puzzlers by Andrew Phillips and Nermin Serifovic

### Erlang

- [Erlang GETTING STARTED - doc](https://www.erlang.org/)

### R

- [R Getting Started - doc](https://www.r-project.org/)

### Others

Programming Languages Ranking

- [TIOBE](https://www.tiobe.com/tiobe-index/)
- [Programming-Language-Benchmarks-Visualization](https://github.com/GoodManWEN/Programming-Language-Benchmarks-Visualization)
- [The Computer Language Benchmarks Game](https://benchmarksgame-team.pages.debian.net/benchmarksgame/index.html)

<br>

<h2><a name="nonturinglang_t" href="#nonturinglang_c">Non-Turing-Complete Languages</a></h2>

<br>

### SQL

Reference [CS Advanced Domains Resources - Database Systems](/_cs-advanced-domains-resources.md#dbms_t)

### Regular Expression

- Mastering Regular Expressions by Jeffrey Friedl
- Regular Expressions Cookbook by Jan Goyvaerts and Steven Levithan
- Regular Expression Pocket Reference: Regular Expressions for Perl, Ruby, PHP, Python, C, Java and .NET Book by Tony Stubblebine

### XML

- [Namespaces in XML](https://www.w3.org/TR/xml-names/)

### HTML & CSS

Reference [Web Frontend Resources - HTML & CSS](../directions/web-frontend-resources.md#htmlcss_t)


### JSON

### YAML

<br>

### Markup Languages

<br>

Prime

- Markdown

Some More

- LaTex
- Asciidoc
- KaTeX
- reStructuredText (rst, reST)
- Wikipedia Wikitext / Wikicode
- Creole
- Textile
- BBCode
- Pendown

<br>

<h2><a name="pgmprd_t" href="#pgmprd_c">Programming Paradigms</a></h2>

<br>

General

- 代码的未来 by [日] 松本行弘
- 松本行弘的程序世界 by [日] 松本行弘
- Metaprogramming Ruby by Paolo Perrotta
- 冒号课堂：编程范式与OOP思想 by 郑晖
- 代码之髓 by [日] 西尾泰和
- Concepts of Programming Languages by Robert W. Sebesta
- Seven More Languages in Seven Weeks by Bruce A. Tate, Ian Dees, Frederic Daoud

Object-Oriented Programming (OOP)

> C++, C#, Java

- Design Patterns: Elements of Reusable Object-Oriented Software by Erich Gamma, Ralph Johnson, John Vlissides, Richard Helm
- Object-Oriented Software Construction by Bertrand Meyer
- The Object-Oriented Thought Process (5th, 2019) by Matt Weisfeld
- Elegant Objects by Yegor Bugayenko
- Head First Object-Oriented Analysis and Design: A Brain Friendly Guide to OOA&D (2006) by Brett McLaughlin, Gary Pollice, David West
- Object-Oriented Analysis and Design with Applications by Grady Booch
- Object Design Style Guide: Powerful techniques for creating flexible, readable, and maintainable object-oriented code in any OO language, from Python to PHP (2020) by Matthias Noback
- OOP Concepts Booster : Take Your Coding Skills to the Next Level by Rakesh Singh
- 面向对象是怎样工作的 by [日]平泽章

Functional Programming

> Haskell, Scala, Clojure

- Introduction to Functional Programming by Richard S. Bird, Philip Wadler
- Real World Haskell by Bryan O'Sullivan, Don Stewart, and John Goerzen
- Thinking Functionally with Haskell by Richard S. Bird
- Programming in Haskell by Graham Hutton
- Functional Programming in Scala by Paul Chiusano and Rúnar Bjarnason
- Functional Programming, Simplified  (Scala Edition) by Alvin Alexander
- Programming Clojure by Stuart Halloway, Susannah Davidson Pfalzer
- Functional Programming In Java: How Functional Techniques Improve Your Java Programs
  by Pierre-Yves Saumont
- Real-world Functional Programming: With Examples in F# and C# by Jon Skeet and Tomas Petricek
- Functional Programming in JavaScript by Luis Atencio

Parallel Programming

> Clojure, Go

Reference [CS Fundamentals Resources - Parallel](../%23cs-foundations.md#parallel)

Garbage Collection

> Java, C#

- The Garbage Collection Handbook: The Art of Automatic Memory Management by Antony Hosking, Eliot Moss, and Richard Jones
- Garbage collection by Richard Jones
- Java Performance Companion by Charlie Hunt, Poonam Bajaj, Bengt Rutisson, Monica Beckwith, John Cuthbertson
- Java Performance Tuning by Jack Shirazi
- 垃圾回收的算法与实现 by 中村成洋, 相川光 

Virtual Machine

> Lisp, Smalltalk, Pascal, Java

<br>

<h2><a name="mfp_t" href="#mfp_c">Metaphors for Programming</a></h2>

<br>

**Metaphor 1**

Six months ago I'd never written a single line of code in my life. I applied to the Coding House dev bootcamp, got accepted and will be graduating next month. I feel super confident about my programming skills now and pumped to put them to work.

Learning to code is like learning a foreign language. You start out with a few basic words and phrases. Then you learn some grammar. Then you learn more words and phrases. Then you learn some more grammar. Then you learn some colloquialisms and slang. Then you learn some more words and phrases. Then you learn some more grammar. Rinse and repeat forever (because "fluency" is a nebulous concept).

When you learn to code, it's the exact same thing. You're learning the language to communicate with technology. Unfortunately, your computer is generally less forgiving than the locals. When you don't know how to ask for another drink at the bar, you can usually get by with "biru" in your funny foreigner accent and one finger held up in the air. When you throw some imperfect code at your machine, though, it'll throw an error in your face at best, or just stare condescendingly at you until you find your mistake (an hour later) and fix it.

When you learn to code, like when you learn a foreign language, you have to adapt your way of thinking to this new environment of communication. In Japanese, the verb comes last, so you start to put more thought into receiver of the action in your communication. In Javascript, the code executes logically, in order, line by line from the top, so you also have to think logically, in order, step by step through your code. And of course, there are always exceptions to the rules (async operations woo!).

Probably the most important parallel, though, is the persistence required to get good at a foreign language, or at coding. You're going to fail. A lot. Then you're going to get a little better. Then you're going to fail even more. You have to accept this constant state of not knowing and the possibility of failure if you want to improve. Eventually you'll look back and realize that you're having a conversation with that bartender now and getting her number. Eventually you'll realize you can spin up a server, design a website or make an app, despite how much you thought you sucked at all this and probably should've just given up a long time ago.

So dive in and get your hands dirty! Break your machine, then learn how to put it all back together again. The journey of a thousand miles and all that jazz.

by [Patrick Shaughnessy](https://qr.ae/pKNpiv)

**2. How to explain coding concepts like streams, promises, linting, and declarative programming to a 5-year-old**

I love thinking about coding concepts by comparing them to familiar things we know in life. There are so many analogies out there about coding concepts. Some of them are good while others are confusing, mainly because they focus on partial aspects of a concept while ignoring many others. This article will summarize some of the analogies that I think best fit a few coding concepts in complete ways.

I will start with simple concepts and move on to harder ones. Let’s start with coding itself. Coding can be compared to writing cooking recipes. A recipe in this analogy is the program and the cook is the computer. A recipe is a list of instructions for a cook to follow and a program is a list of instructions for a computer to execute.

This is a very simple analogy given that a recipe is written in a human language and a program is written in a computer language and those are very different languages (unless your recipes have closures and promises!). There are also not a lot of unexpected things to plan for in a recipe while a computer program will have many. Regardless of its simplicity, it is a good way to show how a computer carries out a list of instructions sequentially. It also shows where one instruction line can use any result from executing prior instruction lines.

Some recipes will even have if-statements: if cooking for 2, 4 or 8! Some recipes will have loops: keep beating that mix until…

I also like this analogy because of all the ready items and tools that you can use in your recipes — like the cake mix that you can use to make cupcakes and that specially-shaped pan that makes it so much easier to create cupcakes.

The use of ready items and tools is like including and using a package of code written by others in your own code.

```
// The making of a cupcake// First steps:
```

```
$ npm install cake-mix $ npm install cupcake-pan
```

NPM is the package manager for Node.js, which a very popular framework for writing JavaScript applications. In this analogy, Node.js is like the kitchen itself. It allows you to execute lines in your recipes by using built-in modules like your oven and sink.

Speaking of unhealthy food, this next analogy is for learning how to code and is compared to eating habits. I particularly LOVE this analogy and what it conveys because it helps me to stay on track in my code learning journey. For me, this began in high school and will continue until my brain reaches its last instruction: die();

by [Samer Buna](https://www.freecodecamp.org/news/hard-coding-concepts-explained-with-simple-real-life-analogies-280635e98e37)

<br>

<h2><a name="mfpl_t" href="#mfpl_c">Metaphors for Programming Languages</a></h2>

<br>

**1. Think of Programming Languages as Workshops**

Python, all the latest power tools, including a few that might not work perfectly, but they're new and nothing is going to cut your hand off or give you tetanus.

C/C++, this is grandpa's barn. All the tools are there, somewhere, but watch out for the black widows and rusted nails sticking up. Oh yeah, everything is hand powered, even the drill and metal lathe.

Rust, the above minus all the old, broken and dirty cruft. Very useful when the power goes out.

FORTRAN, the ultimate high power assembly line. Great for crunching numbers. Heaven help you if you want to do anything else.

Haskell, every CNC machine ever made, clean, works great, totally dust, dirt and grime free. No manuals or displays, however. Those would create side effects.

Erlang, all kinds of little workers in cubicles only able to do one job each. Lots of fun watching stuff being shuttled through old style vacuum transportation tubes.

LISP, a furnace, anvil, crucible, ingot mold, hammer, tongs, pile of coal and pile of scrap metal. Make your own bleeding tools!

Assembly, a hole in the ground containing ore. Get digging, after you make a shovel, of course.

This is actually a lot of fun to do and really points out weaknesses and strengths of different languages.

by [Andrew Olson](https://qr.ae/pKNpgP)

## References

[1] [The Definitive C++ Book Guide and List](https://stackoverflow.com/questions/388242/the-definitive-c-book-guide-and-list)
