# Programming Language Resources

>The only way to learn a new programming language is by writing programs in it. - Dennis Ritchie

> What I cannot create, I do not understand. — Richard Feynman

>Use it or lose it.

**Content**

- <a name="lang_c" href="#lang_t">Programming Languages</a>
- <a name="nonturinglang_c" href="#nonturinglang_t">Non-Turing-Complete Languages</a>
- <a name="cpl_c" href="#cpl_t">Characteristics of Programming Languages</a>
- <a name="pgmprd_c" href="#pgmprd_t">Programming Paradigms</a>
- <a name="mfp_c" href="#mfp_t">Metaphors for Programming</a>
- <a name="mfpl_c" href="#mfpl_t">Metaphors for Programming Languages</a>

<br>

<h2><a name="lang_t" href="#lang_c">Programming Languages</a></h2>

<br>

### Operating-System & Performance

#### <img src="/assets/icon/programming-languages/C.svg" width="20px"/>C

Primary

- **The C Programming Language** (2nd, 1988) by Brian W. Kernighan, Denis M. Ritchie (**TCPL**)
- C Primer Plus (6th, 2013) by Stephen Prata
- [C-FAQ](https://c-faq.com/). comp.lang.c Frequently Asked Questions

Style Guide

- [C Style Guidelines](https://www.cs.umd.edu/~nelson/classes/resources/cstyleguide/)
- [Style Guide for C](https://cs50.readthedocs.io/style/c/)
- [c-code-style](https://github.com/MaJerle/c-code-style)

Project Structure

- [How to Structure C Projects: These Best Practices Worked for Me](https://www.lucavall.in/blog/how-to-structure-c-projects-my-experience-best-practices)

Modern C

- Modern C for Absolute Beginners: A Friendly Introduction to the C Programming Language (2021) by Slobodan Dmitrović

Advanced

- C Pointers
	- Pointers on C (1997) by Kenneth A·Reek 
	- Understanding and Using C Pointers: Core Techniques for Memory Management (2013) by Richard M Reese
- Deep Dive
	- Expert C Programming: Deep C Secrets (1994) by Peter van der Linden 
	- Extreme C: Taking you to the limit in Concurrency, OOP, and the most advanced capabilities of C (2019) by Kamran Amini
	- C in a Nutshell: The Definitive Reference (2nd, 2016) by Peter Prinz, Tony Crawford
	- Practical C Programming: Why Does 2+2 = 5986? (Nutshell Handbooks) (3rd, 1997) by Steve Oualline
	- Mastering Algorithms with C: Useful Techniques from Sorting to Encryption by Kyle Loudon
	- C Programming: A Modern Approach by K. N. King
- Fluent & Effective
	- C Traps and Pitfalls (1989) by Andrew Koenig
	- Effective C: An Introduction to Professional C Programming (2020) by Robert C. Seacord
	- Fluent C: Principles, Practices, and Patterns (2022) by Christopher Preschern
- Tips
	- 21st Century C: C Tips from the New School (2nd, 2014) by Ben Klemens

Network Programming

- Hands-On Network Programming with C: Learn socket programming in C and write secure and optimized network code (2019) by Lewis Van Winkle
- Beej's Guide to Network Programming: Using Internet Sockets by Brian "Beej Jorgensen" Hall
- TCP/IP Sockets in C: Practical Guide for Programmers by Michael J. Donahoo, Kenneth L. Calvert 

Embedded C Programming

- Bare-Metal Embedded C Programming: Develop high-performance embedded systems with C for Arm microcontrollers (2024) by Israel Gbati, Georgios Papanikolaou

<details>
    <summary>Open-source projects recommended reading (C)</summary>

- Systems Programming
	- [Linux Kernel](https://github.com/torvalds/linux). Learn low-level systems programming, memory management, process scheduling, drivers.
	- [Xv6](https://github.com/mit-pdos/xv6-public). A teaching operating system (re-implementation of Unix V6). Great for learning core OS concepts—syscalls, processes, file systems—in a small codebase.
- Networking / Servers
	- [Redis](https://github.com/redis/redis). High-performance key-value storage system, learning network programming and data structure optimization (such as skip lists and hash tables).
	- [Nginx](https://github.com/nginx/nginx). High-performance HTTP and reverse proxy server. Learning event-driven architecture, efficient I/O, memory management.
	- [libevent](https://github.com/libevent/libevent). Event notification library for high-performance network servers. Learning reactor pattern, select/poll/epoll abstractions.
	- [cURL](https://github.com/curl/curl). Tool and library for transferring data with URLs. Learning robust cross-platform network I/O, protocol implementations.
- Tools and Utilities
	- [Git](https://github.com/git/git). Version control system. Learning command line tool design and file version management.
	- [htop](https://github.com/htop-dev/htop). Interactive process viewer. Learning terminal UI, process querying, cross-platform code.
	- [SQLite](https://github.com/sqlite/sqlite). Self-contained, serverless SQL database engine. Excellent code quality, embedded systems focus, ACID-compliant design.
	- [FFmpeg](https://github.com/FFmpeg/FFmpeg). A collection of libraries and tools to process multimedia content such as audio, video, subtitles and related metadata.
- GUI / Desktop Apps
	- [mpv](https://github.com/mpv-player/mpv). A media player based on MPlayer/mplayer2. Learning multimedia processing, rendering, FFmpeg integration.
	- [GIMP](https://gitlab.gnome.org/GNOME/gimp). GNU Image Manipulation Program (like Photoshop). Learning plugin architecture, GUI (GTK), and bitmap/image editing algorithms.
- Educational / Beginner-Friendly Projects
	- [TinyCC](https://github.com/TinyCC/tinycc). A small and fast C compiler. Compact codebase, good for understanding compiler internals.
	- [Kilo Text Editor](https://github.com/antirez/kilo). A small, simple text editor (~1000 LOC). Easy to follow, terminal handling, file I/O.
	- [cJSON](https://github.com/DaveGamble/cJSON). Lightweight JSON parser in C. Clean, portable, focused on readability.
- Embedded / Bare-metal
	- [Micropython (C backend)](https://github.com/micropython/micropython). Python 3 interpreter for microcontrollers. Real embedded systems code in C, memory-constrained environments.
	- [OpenWRT](https://github.com/openwrt/openwrt). Embedded Linux distribution for routers. Learn build systems, networking protocols, firmware development. 
- Others
	- [Lua](https://github.com/lua/lua). Lightweight scripting language, learning virtual machine implementation and interpreter design.

</details>


#### <img src="/assets/icon/programming-languages/Cpp.svg" width="20px"/>C++

/cee plus plus/

**Beginner**

Introductory, no previous programming experience

- **C++ Primer** (5th, 2012) by Josée Lajoie and Stanley B. Lippman
- Programming: Principles and Practice Using C++ by Bjarne Stroustrup
- C++ Crash Course: A Fast-Paced Introduction (2019) by Josh Lospinoso 
- Starting Out with C++ from Control Structures to Objects (2023) by Tony Gaddis 
- C++ Without Fear: A Beginner's Guide That Makes You Feel Smart (3rd, 2015) by Brian Overland

Introductory, with previous programming experience

- **A Tour of C++** (3rd, 2022) by Bjarne Stroustrup
- Accelerated C++: Practical Programming by Example by Andrew Koenig
- Essential C++ by Stanley B. Lippman

Style Guide

- [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)

Project Structure

- [C++ Project Structure and Cross-Platform Build With CMake](https://medium.com/swlh/c-project-structure-for-cmake-67d60135f6f5)
- [What is a general C++ project structure like?](https://www.linkedin.com/pulse/what-general-c-project-structure-like-herbert-elwood-gilliland-iii/)
- [C++ application development ( Part 1 — Project structure )](https://medium.com/heuristics/c-application-development-part-1-project-structure-454b00f9eddc)

Modern C++

>C++11: Modern C++,  C++20: Contemporary C++, C++26: Post-Modern C++.

- C++20
	- Thriving in a Crowded and Changing World: C++ 2006–2020 by Bjarne Stroustrup [PDF](https://www.stroustrup.com/hopl20main-p5-p-bfc9cd4--final.pdf)
	- Modern C++ Programming Cookbook: Master C++ core language and standard library features, with over 100 recipes, updated to C++20 (2nd, 2020) by Marius Bancila
	- C++20 - The Complete Guide (2022) by Nicolai M. Josuttis
	- Beginning C++20: From Novice to Professional (2020) by Ivor Horton and Peter Van Weert
	- Discovering Modern C++ (2nd, 2021) by Peter Gottschling
	- 现代 C++ 教程：高速上手 C++ 11/14/17/20 (2nd) by 欧长坤 [eBook](https://changkun.de/modern-cpp/)
- C++23
	- Modern C++ for Absolute Beginners: A Friendly Introduction to the C++ Programming Language and C++11 to C++23 Standards (2nd, 2023) by Slobodan Dmitrović
	- Learn C++ by Example: Covers versions 11 to 23 (2024) by Frances Buontempo
	- Beginning C++23: From Beginner to Pro (2023) by Ivor Horton, Peter Van Weert
	- C++23 STL Cookbook: Master the latest C++ STL features with practical recipes for modern C++ development (2nd, 2026) by Bill Weinman

Best practices

- **Effective C++** (3rd, 2005) by Scott Meyers
- Effective Modern C++ (2014) by Scott Meyers
- Effective STL (2001) by Scott Meyers
- [C++ Core Guidelines](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines) by Bjarne Stroustrup and Herb Sutter

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
  - C++ Memory Management: Write leaner and safer C++ code using proven memory-management techniques by Patrice Roy 
  - C++ Software Design: Design Principles and Patterns for High-Quality Software (2022) by Klaus Iglberger 
  - STL源码剖析 by 侯捷
- Object-Oriented
	- Object-Oriented Software Design in C++ (2024) by Ronald Mak
- Asynchronous Programming
	- Asynchronous Programming with C++: Build blazing-fast software with multithreading and asynchronous programming for ultimate efficiency (2024) by Javier Reguera-Salgado, Juan Antonio Rufes
- Concurrency
  - C++ Concurrency in Action: Practical Multithreading by Anthony Williams
- Network Programming
  - C++ Network Programming, Volume I: Mastering Complexity with ACE and Patterns
    by Douglas C. Schmidt, Stephen D. Huston
  - C++ Network Programming, Volume 2: Systematic Reuse with Ace and Frameworks
    by Douglas C. Schmidt, Stephen D. Huston
- Efficient
  - C++ High Performance: Master the art of optimizing the functioning of your C++ code (2nd, 2020) by Bjorn Andrist, Viktor Sehr
  - The Art of Writing Efficient Programs: An advanced programmer's guide to efficient hardware utilization and compiler optimizations using C++ examples by Fedor G. Pikus 
- Embedded Systems
	- C++ in Embedded Systems: A practical transition from C to modern C++ (2025) by Amar Mahmutbegović


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

Directions

<details>
    <summary>C/C++的大体方向</summary>
<br>

主要方向：

1. 图形图像/QT。
2. 音视频。实际上也是要分开，比如音频主要代表的有声网，科大讯飞等。
3. 网络。虚拟化，网络安全等。
4. 功能开发。一些原来是 C/C++架构的成熟产品，迭代开发。
5. 嵌入式。嵌入式分得领域非常多，存储，单片机，车载，机械。
6. 医疗。医疗可以单独拿出来，算一个分类。
7. 金融。要求高，不好进。
8. 游戏。游戏分前端 u3d 之类，与图形图像有关联。服务器后端，主要就是高并发网络通信，与金融相关。

C++ 不像 Java 那样 Spring 技术框架一统天下。意思就是方向非常专一，同样是 C++，你在某个圈子深耕三年，换个方向相当于从零开始。

C++ 不是特殊场景，一般不会用它。1. 它太难掌握，对开发要求高，出一个难以复现的问题，定位解决起来半年都是可能的。2. 因为1的原因，变相的导致对开发人员素质要求高，从而推高用人成本高，同时开发效率和稳定性也不如 java 尤其是脚本语言，从公司运营成本角度，就没有意愿选择 C++。

目前坑位多的就是 QT 客户端，音视频，服务器。再者就是嵌入式，偏硬件。高阶的就是存储，量化。高阶的没经验肯定是进不去的。C++没三五年经验可以说是语法都掌握不全。

就业方面，现在大中小公司能不用 C++，他们是绝对不用 C++的，所以坑位最多的 QT 客户端份额逐渐被套壳 js 侵蚀，坑位越来越少。

建议：

图形图像算是不错的一个分类。

游戏，建议不要入。1. 因为太累，版本更新，熬夜加班太正常了。2. 游戏和金融一样，压力大，服务器一秒钟都不能停，有 bug ，一群人盯着不断问。3. 游戏行业并不是需求大的方向，头部效应非常明显，底下的完全喝不到汤。

</details>

<details>
    <summary>Open-source projects recommended reading (C++)</summary>

- Systems / Performance-Oriented
	- [LevelDB](https://github.com/google/leveldb). a fast key-value storage library.
	- [LLVM](https://github.com/llvm/llvm-project). A modular compiler infrastructure with tools like Clang. Learning high-performance code, modern C++, compiler design, ASTs, IR, optimization.
- Game
	- [Godot Engine](https://github.com/godotengine/godot). A feature-rich, open-source game engine. Learning real-time rendering, memory management, custom scripting language (GDScript), large-scale architecture.
	- [raylib](https://github.com/raysan5/raylib). A simple and easy-to-use library to learn game programming. Clean, readable code. Good for beginners in graphics/game dev.
- Libraries & Toolkits
	- [Catch2](https://github.com/catchorg/Catch2). A modern, header-only testing framework for C++. Learn testing best practices, templates, macros.
	- [fmt](https://github.com/fmtlib/fmt). A fast and safe formatting library (used by `std::format`). Learning template metaprogramming, performance-oriented C++.
	- [Range-v3](https://github.com/ericniebler/range-v3). The basis for C++20 ranges. Learning cutting-edge modern C++ idioms (concepts, ranges, views).
- GUI Applications
	- [Notepad++](https://github.com/notepad-plus-plus/notepad-plus-plus). Popular text editor for Windows. Learning Windows API, plugin architecture, GUI management.
	- [MuseScore](https://github.com/musescore/MuseScore). Sheet music editor. Qt-based GUI app, good for learning complex GUI app architecture.
- Networking / Server-side
	- [uWebSockets](https://github.com/uNetworking/uWebSockets). Ultra-fast WebSocket and HTTP server. Learning performance tuning, async I/O, event loops, epoll/kqueue.
	- [Seastar](https://github.com/scylladb/seastar). A high-performance, future-based framework for server apps. Learning asynchronous programming, modern C++ (coroutines, futures).
- Educational / Learning-focused Projects
	- [The Cherno’s Hazel Game Engine](https://github.com/TheCherno/Hazel). Custom game engine by popular C++ YouTuber "The Cherno". Step-by-step game engine building. Great for learning engine design.
	- [Cxxopts](https://github.com/jarro2783/cxxopts). Lightweight C++ command-line option parser. Small project, clean use of modern C++.

</details>


#### <img src="/assets/icon/programming-languages/Rust.svg" width="20px"/>Rust

/rʌst/

Primary

- Documentation
  - [The Rust Programming Language - doc]( https://doc.rust-lang.org/1.30.0/book/first-edition/documentation.html )
  - [Rust Documentation - doc]( https://doc.rust-lang.org/beta/ )
  - [Learn Rust - doc](https://rust-lang.org/learn)
- Online Tutorials
  - [Learn X in Y minutes - Rust](https://learnxinyminutes.com/docs/rust/)
  - [Rust Tutorial - Tutorialspoint](https://www.tutorialspoint.com/rust/)
- **The Rust Programming Language** (2nd, 2023) by Carol Nichols and Steve Klabnik
- **Rust for Rustaceans: Idiomatic Programming for Experienced Developers** (2021) by Jon Gjengset
- **Programming Rust: Fast, Safe Systems Development** (2021) by Jason Orendorff and Jim Blandy
- Rust Programming By Example: Enter the World of Rust by Building Engaging, Concurrent, Reactive, and Robust Applications by Antoni Boucher and Guillaume Gomez
- Rust in Action by Tim McNamara

Style Guide

- [The Rust Style Guide](https://doc.rust-lang.org/nightly/style-guide/index.html)

Project Structure

- [Package Layout](https://doc.rust-lang.org/cargo/guide/project-layout.html#package-layout)
- [Rust: Project structure example step by step](https://dev.to/ghost/rust-project-structure-example-step-by-step-3ee)

Advanced

- Concurrency
  - **Rust Atomics and Locks: Low-Level Concurrency in Practice** (2023) by Mara Bos
  - Hands-On Concurrency with Rust: Confidently Build Memory-Safe, Parallel, and Efficient Software in Rust by Brian L Troutwine
- Effective
	- Effective Rust: 35 Specific Ways to Improve Your Rust Code (2024) by David Drysdale
- Idiomatic Rust: Code like a Rustacean (2024) by Brenden Matthews
- Command-Line Rust: A Project-Based Primer for Writing Rust CLIs (2022) by Ken Youens-Clark

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


### Infrastructure & Balanced

#### <img src="/assets/icon/programming-languages/Go.svg" width="20px"/>Go [📈](https://www.tiobe.com/tiobe-index/go/)

Refer to [Go Resources](../directions/go-resources.md)

### Application & Productivity

#### <img src="/assets/icon/programming-languages/Java.svg" width="20px"/>Java

/ˈdʒɑːvə/

Refer to [Java Resources](../directions/java-resources.md)

#### <img src="/assets/icon/programming-languages/Kotlin.svg" width="20px"/>Kotlin 📈

/ˈkɒtlɪn/

- Documentation
  - [Kotlin Reference - doc]( https://kotlinlang.org/docs/reference/ )
- Online Tutorials
  - [Learn X in Y minutes - Kotlin](https://learnxinyminutes.com/docs/kotlin/)
  - [Kotlin Tutorial - W3Schools](https://www.w3schools.com/kotlin/)
  - [Kotlin Tutorial - Tutorialspoint](https://www.tutorialspoint.com/kotlin/)
- Kotlin in Action by Dmitry Jemerov and Svetlana Isakova
- The Joy of Kotlin by Pierre Yves Saumont
- Kotlin for Android Developers by Antonio Leiva
- Head First Kotlin: A Brain-Friendly Guide by David Griffiths and Dawn Griffiths
- Fundamental Kotlin by Miloš Vasić

#### <img src="/assets/icon/programming-languages/C-sharp.png" width="20px"/>C#

/c sharp/

Refer to [C# Resources](../directions/c-sharp-resources.md)

#### <img src="/assets/icon/programming-languages/Python.svg" width="20px"/>Python 📈

/ˈpaɪθɑːn/

Refer to [Python Resources](../directions/python-resources.md)

#### <img src="/assets/icon/programming-languages/Ruby.svg" width="20px"/>Ruby 📉

/ˈruːbi/

- Documentation
  - [Ruby Documentation - doc]( https://www.ruby-lang.org/en/documentation/ )
- Online Tutorials
  - [Learn X in Y minutes - Ruby](https://learnxinyminutes.com/docs/ruby/)
  - [Ruby Tutorial - Tutorialspoint](https://www.tutorialspoint.com/ruby/)
  - [Learn Ruby](https://www.learnrubyonline.org/)
- The Well-Grounded Rubyist by David A. Black
- Programming Ruby: The Pragmatic Programmers' Guide by Dave Thomas, Chad Fowler, and Andy Hunt
- Eloquent Ruby by Russ Olsen
- Why's (Poignant) Guide to Ruby by Why The Lucky Stiff
- The Ruby Programming Language by David Flanagan, Yukihiro Matsumoto, Why The Lucky Stiff
- The Rails Way by Obie Fernandez
- Agile Web Development with Rails: A Pragmatic Guide by Dave Thomas
- Practical Object Oriented Design in Ruby by Sandi Metz

Style Guide

- [Ruby in Style](https://ruby.style/)
- [Ruby Style Guide](https://rubystyle.guide/)
- [Shopify Ruby Style Guide](https://ruby-style-guide.shopify.dev/#ruby-style-guide)

Project Structure

- [Project Etiquette](https://backend.turing.edu/module1/lessons/project_etiquette)
- [A guide to understanding Ruby on Rails directory structure](https://github.com/jwipeout/rails-directory-structure-guide)

Web Frameworks

- [Ruby on Rails](https://rubyonrails.org/)
- [Hanami](https://hanamirb.org/) - Simplicity.
- [Padrino](https://padrinorb.com/) - Elegant.
- [Sinatra](https://sinatrarb.com/) - Rapid development.

Application Projects

- [mastodon](https://github.com/mastodon/mastodon). Your self-hosted, globally interconnected microblogging community.
- [huginn](https://github.com/huginn/huginn). Create agents that monitor and act on your behalf. Your agents are standing by!
- [discourse](https://github.com/discourse/discourse). A platform for community discussion. Free, open, simple.
- [maybe](https://github.com/maybe-finance/maybe). The OS for your personal finances.
- [forem](https://github.com/forem/forem). For empowering community.
- [chatwoot](https://github.com/chatwoot/chatwoot). Open-source live-chat, email support, omni-channel desk. An alternative to Intercom, Zendesk, Salesforce Service Cloud etc.

Tools

- IDE: RubyMine, Visual Studio Code
- Package Management: [RubyGems](https://rubygems.org/)

#### <img src="/assets/icon/programming-languages/Php.svg" width="20px"/>PHP 📉

Primary

- Documentation
  - [PHP Documentation - doc]( https://www.php.net/docs.php )
- Online Tutorials
  - [Learn X in Y minutes - PHP](https://learnxinyminutes.com/docs/php/)
  - [PHP Tutorial - W3Schools](https://www.w3schools.com/php/)
  - [PHP Tutorial - Tutorialspoint](https://www.tutorialspoint.com/php/)
  - [Learn PHP](https://www.learn-php.org/)
- [PHP: The Right Way by Josh Lockhart](https://phptherightway.com/)
- PHP & MySQL: Server-side Web Development (2022) by Jon Duckett
- Programming PHP: Creating Dynamic Web Pages (4th, 2020) by Kevin Tatroe, Peter MacIntyre
- Learning PHP, MySQL & JavaScript: A Step-by-Step Guide to Creating Dynamic Websites (6th, 2021) by Robin Nixon
- Murach's PHP and MySQL (4th, 2022) by Joel Murach and Ray Harris
- PHP and MySQL Web Development (5th, 2016) by Welling Luke, Thomson Laura

Some more

- Head First PHP and MySQL by Lynn Beighley and Michael Morrison
- PHP for the Web: Visual QuickStart Guide by Larry Ullman
- PHP 6 and MySQL 5 for Dynamic Web Sites: Visual Quickpro Guide by Larry Ullman

Style Guide

- [PSR-2: Coding Style Guide](https://www.php-fig.org/psr/psr-2/)
- [PHP style guide with coding standards and best practices.](https://gist.github.com/ryansechrest/8138375)

Project Structure

- [How to choose a PHP project directory structure](https://docs.php.earth/faq/misc/structure/)
- [Laravel Directory Structure](https://laravel.com/docs/master/structure)


Modern PHP

- Modern PHP: New Features and Good Practices (2015) by Josh Lockhart

Advanced

- PHP 8 Objects, Patterns, and Practice: Mastering OO Enhancements, Design Patterns, and Essential Development Tools (6th, 2021) by Matt Zandstra
- PHP Cookbook: Modern Code Solutions for Professional Developers  (2023) by Adam Trachtenberg and David Sklar
- Best Practices
  - Clean Code in PHP: Expert tips and best practices to write beautiful, human-friendly, and maintainable PHP (2022) by Carsten Windler, Alexandre Daubois
  - PHP 8 Programming Tips, Tricks and Best Practices: A practical guide to PHP 8 features, usage changes, and advanced programming techniques (2021) by Doug Bierer
- Laravel
  - Laravel: Up & Running: A Framework for Building Modern PHP Apps (3rd, 2023) by Matt Stauffer


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

Framework / Library Projects

- [easywechat](https://github.com/w7corp/easywechat) 一个 PHP 微信 SDK

Application Projects

- [Faker](https://github.com/fzaninotto/Faker) Faker is a PHP library that generates fake data for you
- [monica](https://github.com/monicahq/monica) Personal CRM. Remember everything about your friends, family and business relationships
- [koel](https://github.com/koel/koel) A personal music streaming server that works.
- [flarum](https://github.com/flarum/flarum) Simple forum software for building great communities.
- [firefly-iii](https://github.com/firefly-iii/firefly-iii) Firefly III: a personal finances manager
- [grav](https://github.com/getgrav/grav) Modern, Crazy Fast, Ridiculously Easy and Amazingly Powerful Flat-File CMS powered by PHP, Markdown, Twig, and Symfony
- [BookStack](https://github.com/BookStackApp/BookStack) A platform to create documentation/wiki content built with PHP & Laravel
- [bagisto](https://github.com/bagisto/bagisto) Free and open source laravel eCommerce platform
- [voyager](https://github.com/thedevdojo/voyager) Voyager - The Missing Laravel Admin
- [laravel-admin](https://github.com/z-song/laravel-admin) Build a full-featured administrative interface in ten minutes
- [typecho](https://github.com/typecho/typecho) A PHP Blogging Platform. Simple and Powerful.
- [october](https://github.com/octobercms/october) Self-hosted CMS platform based on the Laravel PHP Framework.
- [wallabag](https://github.com/wallabag/wallabag) wallabag is a self hostable application for saving web pages: Save and classify articles. Read them later. Freely.
- [woocommerce](https://github.com/woocommerce/woocommerce) A customizable, open-source ecommerce platform built on WordPress. Build any commerce solution you can imagine.
- [FreshRSS](https://github.com/FreshRSS/FreshRSS) A free, self-hostable news aggregator
- [CRMEB](https://github.com/crmeb/CRMEB) CRMEB开源商城免费开源多语言商城系统，Tp6框架商城
- [ThinkAdmin](https://github.com/zoujingli/ThinkAdmin) 基于 ThinkPHP6 的极简后台管理系统

#### <img src="/assets/icon/frontend/Nodejs.svg" width="20px"/>Node.js (JavaScript)

Reference [Web Frontend Resources - Node.js](../directions/web-frontend-resources.md#nodejs)

### Client Application

#### <img src="/assets/icon/programming-languages/JavaScript.svg" width="20px"/>JavaScript 📈

Reference [Web Frontend Resources - JavaScript](../directions/web-frontend-resources.md#js_t)

#### <img src="/assets/icon/programming-languages/Android.svg" width="20px"/>Android

- [Android Documentation - doc](https://developer.android.com/docs)
- Android Programming: The Big Nerd Ranch Guide by Brian Hardy, Bill Phillips
- Head First Android Development: A Brain-Friendly Guide by DAVID GRIFFITHS and Dawn Griffiths
- The Busy Coder's Guide to Advanced Android Development by Mark Murphy
- Android Programming: Pushing the Limits by Erik Hellman
- Professional Android 4 Application Development by Reto Meier
- Learning Android by Marko Gargenta
- Programming Android: Java Programming for the New Generation of Mobile Devices by Zigurd Mednieks, Laird Dornin, G. Blake Meike, Masumi Nakamura

Android in Kotlin

- [Android Basics in Kotlin](https://developer.android.com/courses/android-basics-kotlin/course)

Android Studio

- [Android Studio User Guide](https://developer.android.com/studio/intro)




#### <img src="/assets/icon/programming-languages/Apple.svg" width="20px"/>Objective-C

- Documentation
  - [Programming with Objective-C - doc]( https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html )
  - [The Objective-C Programming Language - doc]( https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/ObjectiveC/Introduction/introObjectiveC.html )
  - [Apple Developer Documentation - doc]( https://developer.apple.com/documentation )
- Online Tutorials
  - [Learn X in Y minutes - Objective-C](https://learnxinyminutes.com/docs/objective-c/)
- [iOS Example](https://iosexample.com/)
- Programming in Objective-C by Stephen G. Kochan
- Objective-C Programming: The Big Nerd Ranch Guide by Aaron Hillegass and Mikey Ward
- Effective Objective-C 2.0: 52 Specific Ways to Improve Your IOS and OS X Programs by Matt Galloway
- iOS Programming: The Big Nerd Ranch Guide by Aaron Hillegass and Joe Conway
- Learning Cocoa with Objective-C: Developing for the Mac and IOS App Stores by Jon Manning and Paris Buttfield-Addison
- Learn Objective-C on the Mac by Mark Dalrymple, Scott Knaster

Courses

- [CS193p - Developing Apps for iOS](https://cs193p.sites.stanford.edu/) by Stanford University

#### <img src="/assets/icon/programming-languages/Swift.svg" width="20px"/>Swift

- Documentation
  - [Swift Documentation - doc]( https://swift.org/documentation/ )
- Online Tutorials
  - [Learn X in Y minutes - Swift](https://learnxinyminutes.com/docs/swift/)
  - [Swift Tutorial - Tutorialspoint](https://www.tutorialspoint.com/swift/)
- Swift in Depth by Tjeerd in 't Veen
- IOS 12 Programming for Beginners: An Introductory Guide to IOS App Development with Swift 4.2 and Xcode 10 (3rd, 2018) by Craig Clayton
- IOS 10 Programming Fundamentals with Swift: Swift, Xcode, and Cocoa Basics by Matt Neuburg
- Swift 5 for Absolute Beginners: Learn to Develop Apps for iOS by Stefan Kaczmarek, Brad Lees, Gary Bennett

#### <img src="/assets/icon/programming-languages/Delphi.svg" width="20px"/>Delphi

>Delphi is a high-level, compiled, object-oriented programming language and software development environment, based on the Object Pascal language.

>Delphi is primarily used in desktop application development.

- [Delphi](https://www.embarcadero.com/products/delphi). Native Apps For Any Device From One Codebase With Delphi! Build Apps 5x Faster for Windows, Android, iOS, macOS, and Linux.

#### <img src="/assets/icon/programming-languages/Windows.svg" width="20px"/>Windows Desktop Applications

- `C#` + [Windows Forms](https://learn.microsoft.com/en-us/dotnet/desktop/winforms/) or [WPF (Windows Presentation Foundation)](https://learn.microsoft.com/en-us/dotnet/desktop/wpf/)
- `C++` + [Win32 API](https://learn.microsoft.com/en-us/windows/win32/api/)、[MFC](https://learn.microsoft.com/en-us/cpp/mfc/mfc-desktop-applications) or Qt
- [Visual Basic .NET](https://learn.microsoft.com/en-us/dotnet/visual-basic/)

#### <img src="/assets/icon/programming-languages/Linux.svg" width="20px"/>Linux Desktop Applications

- C/C++
  - GTK+
  - Qt
- Python
  - GTK+
  - PyQt/PySide
  - Tkinter

#### Browser Plugins or Extensions

Google Chrome

- [Chrome Extensions - chrome for developers](https://developer.chrome.com/docs/extensions)
- [Chrome Extensions samples](https://github.com/GoogleChrome/chrome-extensions-samples)

#### Cross-Platform Applications

**One codebase for all platforms** (web, mobile, desktop)

- JavaScript/TypeScript
	- [React Native](https://reactnative.dev/) (2015) by Meta
	- [Tauri](https://tauri.app/) (2020)
	- [Ionic](https://ionicframework.com/) (2013)
	- [Progressive Web Apps (PWA)](https://web.dev/explore/progressive-web-apps) (2016) by Google
	- [Apache Cordova](https://cordova.apache.org/) / PhoneGap (2009)
	- [Quasar Framework](https://quasar.dev/) (2015)
- Dart
	- [Flutter](https://flutter.dev/) (2017) by Google
- C#
	- [Xamarin](https://dotnet.microsoft.com/en-us/apps/xamarin) (2011)
	- [Unity](https://unity.com/) (2005)
	- [.NET MAUI](https://dotnet.microsoft.com/en-us/apps/maui) (Multi-platform App UI) (2022) by Microsoft
	- [Avalonia](https://avaloniaui.net/) (2013)
- Java
	- [JavaFX](https://openjfx.io/) (2008) by Oracle
- Kotlin
	- [Kotlin Multiplatform](https://kotlinlang.org/docs/multiplatform.html) (2023) by JetBrains
- C++
	- [Qt](https://www.qt.io/) (1995)
- Python
	- [Qt](https://www.qt.io/) (1995)

**Mobile cross-platform** (Android, iOS)

- Ruby
	- [RubyMotion](http://www.rubymotion.com/) (2012)
- JavaScript/TypeScript
	- [NativeScript](https://nativescript.org/) (2014)

**Desktop cross-platform** (Windows, macOS, and Linux)

- JavaScript/TypeScript
	- [Electron](https://electronjs.org/) (2013)
- Java
	- [Swing](https://docs.oracle.com/javase/tutorial/uiswing/index.html) by Oracle
- GTK ([C++, Go, Python, Rust and more](https://www.gtk.org/docs/language-bindings/))

### Glue & Convenience

>Python, JavaScript, Ruby, Perl, Bash, Groovy, PHP, Lua, F# and Clojure.

#### <img src="/assets/icon/programming-languages/Perl.svg" width="20px"/>Perl

/pɜː(r)l/

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

#### <img src="/assets/icon/programming-languages/Groovy.svg" width="20px"/>Groovy

/ˈɡruːvi/

- Documentation
  - [Groovy Documentation - doc]( https://groovy-lang.org/documentation.html )
- Online Tutorials
  - [Learn X in Y minutes - Groovy](https://learnxinyminutes.com/docs/groovy/)
  - [Groovy Tutorial - Tutorialspoint](https://www.tutorialspoint.com/groovy/)
  - [Refcard Groovy A Rapid-Development JVM Language - DZone](https://dzone.com/refcardz/groovy). a cheat sheet.
- Groovy in Action by Dierk König, Andrew Glover, Paul King, Guillaume Laforge, Jon Skeet, James Gosling
- Programming Groovy 2: Dynamic Productivity for the Java Developer by Venkat Subramaniam
- Making Java Groovy by Kenneth A. Kousen
- Groovy 2 Cookbook by Andrey Adamovich and Luciano Fiandesio
- Grails in Action by Glen Smith, Peter Ledbrook
- The definitive guide to Grails by Graeme Keith Rocher

#### <img src="/assets/icon/programming-languages/Lua.svg" width="20px"/>Lua

/Loo-uh/

- Documentation
  - [Lua Documentation - doc]( https://www.lua.org/docs.html )
- Online Tutorials
  - [Learn X in Y minutes - Lua](https://learnxinyminutes.com/docs/lua/)
  - [Lua Tutorial - Tutorialspoint](https://www.tutorialspoint.com/lua/)
- Programming in Lua by Roberto Ierusalimschy
- Lua Programming Gems by Luiz Henrique de Figueiredo, Waldemar Celes, Roberto Ierusalimschy
- Beginning Lua programming by Kurt Jung
- Lua Quick Start Guide: The Easiest Way to Learn Lua Programming by Gabor Szauer
- Lua 5.2 Reference Manual by Luiz Henrique de Figueiredo, Roberto Ierusalimschy, and Waldemar Celes

### Minority programming languages

#### <img src="/assets/icon/programming-languages/Clojure.svg" width="20px"/>Clojure

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

#### <img src="/assets/icon/programming-languages/F-sharp.png" width="20px"/>F#

- [F# documentation](https://fsharp.org/learn/)
- F# in Action (2024) by Isaac Abraham
- Domain Modeling Made Functional: Tackle Software Complexity with Domain-Driven Design and F# (2018) by Scott Wlaschin
- Stylish F# 6: Crafting Elegant Functional Code for .NET 6 (2nd, 2021) by Kit Eason
- Get Programming with F#: A guide for .NET developers (2018) by Isaac Abraham
- Real-World Functional Programming: With Examples in F# and C# (2010) by Tomas Petricek, Jon Skeet
- The Book of F#: Breaking Free With Managed Functional Programming (2014) by Dave Fancher


### Big Data Field

#### <img src="/assets/icon/programming-languages/Scala.svg" width="20px"/>Scala

>Scala is widely used in fields that require scalable, high-performance applications, especially those that benefit from both object-oriented and functional programming paradigms. It’s popular for building big data systems, distributed applications, and backend services.

- Documentation
  - [Scala Documentation - doc]( https://docs.scala-lang.org/ )
- Online Tutorials
  - [Learn X in Y minutes - Scala](https://learnxinyminutes.com/docs/scala/)
  - [Scala Tutorial - Tutorialspoint](https://www.tutorialspoint.com/scala/)
  - [Learn Scala](https://www.learnscala.org/)
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

### Real-time systems

#### <img src="/assets/icon/programming-languages/Erlang.svg" width="20px"/>Erlang

>Erlang is primarily used in fields that require highly reliable, concurrent, and distributed systems, especially where fault tolerance and real-time performance are critical.

- [Erlang GETTING STARTED - doc](https://www.erlang.org/)

### Statistical analysis

#### <img src="/assets/icon/programming-languages/R.svg" width="20px"/>R

>R is primarily used in fields that require statistical analysis, data visualization, and data science. It is widely adopted by statisticians, data scientists, and researchers for handling complex data and creating insights.

- [R Getting Started - doc](https://www.r-project.org/)

### Industrial field

#### <img src="/assets/icon/programming-languages/VisualBasic.svg" width="20px"/>Visual Basic

>Visual Basic (VB) — especially Visual Basic for Applications (VBA) and Visual Basic .NET (VB.NET) — is primarily used in business software development, office automation, and internal enterprise tools, particularly within Windows environments.

- [Visual Basic language reference](https://docs.microsoft.com/en-us/office/vba/language/reference/user-interface-help/visual-basic-language-reference)

### Banking and financial services

#### <img src="/assets/icon/programming-languages/Cobol.svg" width="20px"/>COBOL

>COBOL (Common Business-Oriented Language) is primarily used in the field of business, finance, and administrative systems—especially those that require high-volume data processing and long-term reliability.

- [COBOL](https://developer.ibm.com/languages/cobol/). Run mission-critical processes on the modern mainframe with this business-oriented language that enterprises and developers continue to rely on.

### Academic research and education

#### <img src="/assets/icon/programming-languages/Fortran.svg" width="20px"/>Fortran

>Fortran (short for Formula Translation) is primarily used in fields that require high-performance numerical computing, especially those involving scientific, engineering, and mathematical computations.

- [Fortran](https://fortran-lang.org/). High-performance parallel programming language.

#### <img src="/assets/icon/programming-languages/Matlab.svg" width="20px"/>MATLAB

>MATLAB is widely used in fields that require mathematical modeling, data analysis, simulation, and algorithm development. It’s especially popular in engineering, science, and academia, as well as in industry applications that demand prototyping and high-performance computation.

- [MATLAB](https://www.mathworks.com/products/matlab.html). A programming and numeric computing platform used by millions of engineers and scientists to analyze data, develop algorithms, and create models.

#### <img src="/assets/icon/programming-languages/Lisp.svg" width="20px"/>Lisp

>Lisp (short for LISt Processing) is primarily used in fields that value symbolic computation, AI research, and metaprogramming. It’s one of the oldest high-level programming languages, known for its powerful macro system, code-as-data philosophy, and flexibility.

>屠龙之技厉害，奈何龙少。

- Documentation
  - [Common-Lisp Documentation - doc]( https://common-lisp.net/documentation )
- Practical Common Lisp by Peter Seibel
- Paradigms of AI Programming: Case Studies in Common Lisp by Peter Norvig
- Common LISP: A Gentle Introduction to Symbolic Computation by David S. Touretzky
- Structure and Interpretation of Computer Programs by Gerald Jay Sussman and Hal Abelson
- On Lisp by Paul Graham
- Land of Lisp: Learn to Program in Lisp, One Game at a Time! by Conrad Barski
- Common Lisp the Language by Guy L. Steele Jr.
- ANSI Common Lisp by Paul Graham
- The Little Schemer by Daniel P. Friedman and Matthias Felleisen

#### <img src="/assets/icon/programming-languages/Haskell.svg" width="20px"/>Haskell

>Haskell is primarily used in fields that require strong correctness guarantees, complex algorithmic logic, or robust concurrency — especially in academia, research, finance, and advanced software tooling. It's a purely functional programming language known for type safety, immutability, and mathematical elegance.

- [Haskell Documentation - doc]( https://www.haskell.org/documentation/ )
- Learn You a Haskell for Great Good!: A Beginner's Guide by Miran Lipovača [HTML](https://learnyouahaskell.github.io/chapters.html)
- Real World Haskell: Code You Can Believe In by Bryan O'Sullivan [HTML](https://book.realworldhaskell.org/read/)
- Learn Haskell by building a blog generator by Gil Mizrahi [HTML](https://learn-haskell.blog/)
- Programming in Haskell by Graham Hutton
- Haskell Programming From First Principles by Christopher Allen, Julie Moronuki
- Get Programming with Haskell by Will Kurt
- Thinking Functionally with Haskell by Richard S. Bird
- Haskell: The Craft of Functional Programming by Simon Thompson

Intermediate

- Developing Web Apps with Haskell and Yesod: Safety-Driven Web Development (2nd, 2015) by Michael Snoyman [HTML](https://www.yesodweb.com/book)
- Parallel and Concurrent Programming in Haskell: Techniques for Multicore and Multithreaded Programming by Simon Marlow
- Functional Design and Architecture: Examples in Haskell (2024) by Alexander Granin
- Haskell in Depth (2021) by Vitaly Bragilevsky
- Practical Haskell: A Real-World Guide to Functional Programming (2022) by Alejandro Serrano Mena
- Production Haskell: Succeeding in Industry with Haskell (2023) by Matt Parsons

Web Frameworks

- Full Stack
	- [Yesod](https://www.yesodweb.com/)
- API
	- [Servant](https://www.servant.dev/)

#### <img src="/assets/icon/programming-languages/Scratch.svg" width="20px"/>Scratch

>Scratch is primarily used in the field of education, especially for teaching programming and computational thinking to children and beginners.

- [Scratch](https://scratch.mit.edu/). Create stories, games, and animations. Share with others around the world.

### Others

#### Julia

- [Julia 1.4 Documentation](https://docs.julialang.org/en/v1/)
- [Julia learning resources](https://julialang.org/learning/)

#### D

- **D** is a general-purpose programming language with static typing, systems-level access, and C-like syntax. With the D Programming Language, write fast, read fast, and run fast.
- The D Programming Language by Andrei Alexandrescu

### Ranking

**Programming Languages Ranking**

- [TIOBE](https://www.tiobe.com/tiobe-index/)
- [Programming-Language-Benchmarks-Visualization](https://github.com/GoodManWEN/Programming-Language-Benchmarks-Visualization)
- [The Computer Language Benchmarks Game](https://benchmarksgame-team.pages.debian.net/benchmarksgame/index.html)

**Project Ranking**

- [GitHub Ranking](https://evanli.github.io/Github-Ranking/)

**Programming Language of the Year (TIOBE)**

>The programming language that has the highest rise in ratings in a year.

| Year | Winner       | Description                                                                                                                                                                                                                                                                                                                                                     |
| ---- | ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 2024 | Python       | 1. The explosion of artificial intelligence and large language models (**LLM**). 2. **Data science** and data engineering continue to grow.                                                                                                                                                                                                                     |
| 2023 | C#           | The .NET ecosystem continues to develop and its **cross-platform** capabilities are enhanced.                                                                                                                                                                                                                                                                   |
| 2022 | C++          | 1. C++20 and C++23 drive the **modernization** process and attract attention. 2. Game development and graphics programming still heavily rely on C++. 3. Fields such as financial engineering and high-frequency trading rely on C++. 4. Embedded systems and device drivers are still widely used. 5. The underlying layer of the AI toolchain is still C/C++. |
| 2021 | Python       | 1. The explosion of artificial intelligence (**AI**) and machine learning (**ML**). 2. **Data science** and data analysis widely use Python.                                                                                                                                                                                                                    |
| 2020 | Python       | 1. The explosion of artificial intelligence (**AI**) and machine learning (**ML**). 2. **Data science** and data analysis widely use Python.                                                                                                                                                                                                                    |
| 2019 | C            | The rapid growth of **embedded and IoT devices**.                                                                                                                                                                                                                                                                                                               |
| 2018 | Python       | 1. The explosion of artificial intelligence (**AI**) and machine learning (**ML**). 2. **Data science** and data analysis widely use Python.                                                                                                                                                                                                                    |
| 2017 | C            | The rapid growth of **embedded and IoT devices**.                                                                                                                                                                                                                                                                                                               |
| 2016 | Go           | 1. The wave of **cloud-native** is beginning to rise. 2. **Microservices architecture** is starting to become mainstream.                                                                                                                                                                                                                                       |
| 2015 | Java         | 1. The Mobile Internet Era. 2. **Android application** development mainly uses Java. 3. The main language for **enterprise-level backend development**.                                                                                                                                                                                                         |
| 2014 | JavaScript   | 1. MVVM frameworks: React, Angular and Vue. 2. Node.js. 3. npm. 4. Front-end engineering. Grunt and Webpack. 5. SPA. 6. Cross-platform application development with JS.                                                                                                                                                                                         |
| 2013 | Transact-SQL | 1. Widespread adoption of Microsoft SQL Server. 2. The demand for complex data processing and automation in enterprises is increasing. 3. The rise of **Business Intelligence (BI) and Data Warehousing**.                                                                                                                                                      |
| 2012 | Objective-C  | 1. The Mobile Internet Era. 2. iPhone 4 (2010) and iPhone 4S (2011) are big sellers. 3. App Store success.                                                                                                                                                                                                                                                      |
| 2011 | Objective-C  | 1. The Mobile Internet Era. 2. iPhone 4 (2010) and iPhone 4S (2011) are big sellers. 3. App Store success.                                                                                                                                                                                                                                                      |
| 2010 | Python       | 1. Simple and easy to learn, suitable for **rapid development**. 2. Scientific computing and data analytics at the start. 3. The **web development** ecosystem is rich. 4. **Automation and scripting** are widely used. 5. Adoption by large internet companies.                                                                                               |
| 2009 | Go           | 1. Google officially released Go in 2009. 2. **Google endorsement**, attracting attention.                                                                                                                                                                                                                                                                      |
| 2008 | C            | 1. The foundational language of operating systems and low-level software. 2. Embedded systems and hardware control are widely used.                                                                                                                                                                                                                             |
| 2007 | Python       | 1. Simple and easy to learn, suitable for **rapid development**. 2. Scientific computing and data analytics at the start. 3. **Web development** frameworks are growing rapidly. 4. **Automation and scripting** are widely used. 5. Adoption by large internet companies.                                                                                      |
| 2006 | Ruby         | 1. The rise of the **Ruby on Rails** framework. 2. Concise and elegant syntax design. 3. Suitable for startups and **rapid development**.                                                                                                                                                                                                                       |
| 2005 | Java         | 1. The main language for **enterprise-level application development**. 2. Stable and mature ecosystem and toolchain. 3. Support for mobile devices and embedded systems. 4. The widespread use of web application servers and middleware.                                                                                                                       |
| 2004 | PHP          | 1. The main programming language for **web application development**. 2. Many popular websites and content management systems (**CMS**) use PHP. 3. Open source, free, and cross-platform. 4. Rich extension libraries and frameworks 5. During the recovery period after the internet bubble, the number of websites grew rapidly.                             |
| 2003 | C++          | 1. Excellent performance, suitable for system-level development. 2. The main programming language in the field of game development.                                                                                                                                                                                                                             |

<br>

<h2><a name="nonturinglang_t" href="#nonturinglang_c">Non-Turing-Complete Languages</a></h2>

<br>

### SQL

"S-Q-L" /ˈɛs kjuː ˈɛl/ or "sequel" /ˈsiːkwəl/

Reference [CS Advanced Domains Resources - Database Systems](/_cs-advanced-domains-resources.md#dbms_t)

### Regular Expression

- Mastering Regular Expressions by Jeffrey Friedl
- Regular Expressions Cookbook by Jan Goyvaerts and Steven Levithan
- Regular Expression Pocket Reference: Regular Expressions for Perl, Ruby, PHP, Python, C, Java and .NET Book by Tony Stubblebine

Regex Examples

- [iHateRegex](https://ihateregex.io/)

Regex Tools

- https://regex101.com/

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

- <img src="/assets/icon/programming-languages/Markdown.svg" width="20px"/>Markdown

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

<h2><a name="cpl_t" href="#cpl_c">Characteristics of Programming Languages</a></h2>

<br>

**1\. Compiled vs Interpreted**

Core difference: how code is converted into machine instructions and executed.

**Compiled Languages**: Translated entirely into machine code before execution. For example: C, C++, Rust, Go.

Pros:

- Faster execution (no translation during runtime)
- More optimized performance
- Early detection of syntax/type errors

Cons:

- Slower development cycle (compile before run)
- Harder to debug without symbols

**Interpreted Languages**: Executed line-by-line by an interpreter at runtime. For example: Python, Ruby, JavaScript, PHP.

Pros:

- Easier to debug
- More flexibility (can be modified at runtime)
- Faster prototyping

Cons:

- Slower execution
- Errors may only appear at runtime

**2\. Static Typing vs Dynamic Typing**

Core difference: Whether type checking occurs at compile time or runtime.

**Static Typing**: Variable types are known at compile time. For example: Java, C, C++, Rust, Go.

Pros:

- Type errors caught early
- Better IDE support and tooling
- More optimizations possible

Cons:

- More boilerplate code
- Less flexibility (need to declare types)

```java
// Java（Static type）
int x = 10;  // Type determined at compile time
x = "hello"; // Compilation error: Type mismatch
```

**Dynamic Typing**: Variable types are determined at runtime. For example: Python, JavaScript, Ruby, PHP.

Pros:

- Easier and faster to write
- More flexible (can reuse variables of different types)

Cons:

- Type errors appear only at runtime
- Can be harder to maintain and debug in large codebases

```python
# Python（Dynamic type）
x = 10      # Inferred at runtime as int
x = "hello" # Legal: types can change dynamically
```

**3\. Strong Typing vs Weak Typing**

Core difference: Whether type conversion requires explicit operation (strictness).

**Strong Typing**: Types are strictly enforced; implicit conversions are limited. For example: Python, Java, Ruby.

Pros:

- Prevents unexpected behavior
- Forces clear type conversions

Cons:

- May require more explicit code
- Less flexible for quick-and-dirty scripting

```python
# Python（Strong type）
x = "1" + 1  # TypeError：Explicit conversion required `int("1") + 1`
```

**Weak Typing**: Allows implicit type conversions more freely. For example: JavaScript, PHP, Perl.

Pros:

- Convenient for simple scripts
- Less code to write for certain tasks

Cons:

- Can lead to subtle, hard-to-detect bugs
- Type coercion may cause confusing behavior (e.g., `'' == 0` is `true` in JS)

```javascript
// JavaScript（Weak type）
let x = "1" + 1; // Legal, the result is a string "11"（Implicit conversion）
let y = "1" - 1; // Legal, the result is the number 0.（Implicit conversion）
```

**Summary Table**

| Language            | Compiled / Interpreted                     | Static / Dynamic Typing   | Strong / Weak Typing |
| ------------------- | ------------------------------------------ | ------------------------- | -------------------- |
| C                   | Compiled                                   | Static                    | Weak                 |
| C++                 | Compiled                                   | Static                    | Weak                 |
| Rust                | Compiled                                   | Static                    | Strong               |
| Go                  | Compiled                                   | Static                    | Strong               |
| Java                | Compiled (to bytecode) + Interpreted (JIT) | Static                    | Strong               |
| Kotlin              | Same as Java (JVM Language)                | Static                    | Strong               |
| C#                  | Compiled + Interpreted                     | Static                    | Strong               |
| Python              | Interpreted                                | Dynamic                   | Strong               |
| Ruby                | Interpreted                                | Dynamic                   | Strong               |
| PHP                 | Interpreted                                | Dynamic                   | Weak                 |
| JavaScript          | Interpreted                                | Dynamic                   | Weak                 |
| Objective-C         | Compiled                                   | Static                    | Weak                 |
| Swift               | Compiled                                   | Static                    | Strong               |
| Perl                | Interpreted                                | Dynamic                   | Weak                 |
| Groovy              | Same as Java (JVM Language)                | Dynamic (optional static) | Strong               |
| Lua                 | Interpreted                                | Dynamic                   | Weak                 |
| Clojure             | Same as Java (JVM Language)                | Dynamic                   | Strong               |
| F#                  | Compiled (.NET)                            | Static                    | Strong               |
| Scala               | Same as Java (JVM Language)                | Static                    | Strong               |
| Erlang              | Compiled (BEAM VM)                         | Dynamic                   | Strong               |
| R                   | Interpreted                                | Dynamic                   | Weak                 |
| Visual Basic (.NET) | Compiled (to IL)                           | Static                    | Strong               |
| Lisp (Common Lisp)  | Interpreted / Compiled                     | Dynamic                   | Strong               |
| Haskell             | Compiled                                   | Static                    | Strong               |

<br>

<h2><a name="pgmprd_t" href="#pgmprd_c">Programming Paradigms</a></h2>

<br>

General

- Metaprogramming Ruby by Paolo Perrotta
- Concepts of Programming Languages by Robert W. Sebesta
- Seven More Languages in Seven Weeks by Bruce A. Tate, Ian Dees, Frederic Daoud
- 代码的未来 by [日] 松本行弘
- 松本行弘的程序世界 by [日] 松本行弘
- 冒号课堂：编程范式与OOP思想 by 郑晖
- 代码之髓 by [日] 西尾泰和

**Imperative programming / Procedural programming / structured programming**

>C (1972), Pascal (1970), Fortran (1957), BASIC (1964), Ada (1980), COBOL (1959)

>Structured programming consists of designing a set of procedures (or algorithms) to solve a problem.

>Algorithms come first, and data structures second.

**Object-Oriented Programming (OOP)**

> C++ (1985), C# (2000), Java (1995)

> Object-Oriented Programming (OOP) emerged as a response to the limitations of procedural programming and to address the growing complexity of software systems.

> OOP has become a dominant programming paradigm in software development because it helps to manage complexity, encourages good design practices, and facilitates collaboration among developers. As systems grew larger and more complex, the need for these benefits became more apparent, driving the adoption of OOP in both academic and commercial software development.

>Object-oriented programming is the opposite of procedural programming. OOP puts the data first, then looks at the algorithms to operate on the data.

>For small problems, the breakdown into procedures works very well. But objects are more appropriate for larger problems. Consider a simple web browser. It might require 2,000 procedures for its implementation, all of which manipulate a set of global data. In the object-oriented style, there might be 100 classes with an average of 20 methods per class. This structure is much easier for a programmer to grasp. It is also much easier to find bugs in.

>In a procedural program, you start the process at the top, with the main function. When designing an object-oriented system, there is no “top,” and newcomers to OOP often wonder where to begin. The answer is: Identify your classes and then add methods to each class. A simple rule of thumb in identifying classes is to look for nouns in the problem analysis. Methods, on the other hand, correspond to verbs.

- Design Patterns: Elements of Reusable Object-Oriented Software by Erich Gamma, Ralph Johnson, John Vlissides, Richard Helm
- Object-Oriented Software Construction by Bertrand Meyer
- The Object-Oriented Thought Process (5th, 2019) by Matt Weisfeld
- Elegant Objects by Yegor Bugayenko
- Head First Object-Oriented Analysis and Design: A Brain Friendly Guide to OOA&D (2006) by Brett McLaughlin, Gary Pollice, David West
- Object-Oriented Analysis and Design with Applications by Grady Booch
- Object Design Style Guide: Powerful techniques for creating flexible, readable, and maintainable object-oriented code in any OO language, from Python to PHP (2020) by Matthias Noback
- OOP Concepts Booster : Take Your Coding Skills to the Next Level by Rakesh Singh
- 面向对象是怎样工作的 by [日]平泽章

**Functional Programming (FP)**

> Haskell (2010), Scala (2004), Clojure (2007), F# (2005)

>While functional programming isn't universally applicable to all problems or scenarios, it provides powerful abstractions, promotes clarity of thought, and addresses many challenges faced by developers in the modern software landscape. As a result, many languages, such as JavaScript, Python, and even Java, have incorporated functional programming concepts alongside traditional paradigms.

- The Art of Functional Programming (2022) by Minh Quang Tran
- An Introduction to Functional Programming Through Lambda Calculus (2011) by Greg Michaelson
- Functional Design and Architecture: Examples in Haskell (2024) by Alexander Granin
- Functional Design: Principles, Patterns, and Practices (2023) by Robert Martin 
- Grokking Simplicity: Taming complex software with functional thinking (2021) by Eric Normand
- Grokking Functional Programming (2022) by Michal Plachta
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

**Parallel Programming**

> Clojure (2007), Go (2012)

Reference [CS Fundamentals Resources - Parallel](../%23cs-foundations.md#parallel)

**Garbage Collection**

> Java (1995), C# (2000)

- The Garbage Collection Handbook: The Art of Automatic Memory Management by Antony Hosking, Eliot Moss, and Richard Jones
- Garbage collection by Richard Jones
- Java Performance Companion by Charlie Hunt, Poonam Bajaj, Bengt Rutisson, Monica Beckwith, John Cuthbertson
- Java Performance Tuning by Jack Shirazi
- 垃圾回收的算法与实现 by 中村成洋, 相川光 

**Virtual Machine**

> Lisp (1960), Smalltalk (1980), Pascal (1970), Java (1995)

**Distributed computing**

> Erlang (1998)

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
