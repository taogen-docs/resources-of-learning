# <img src="/assets/icon/programming-languages/C.svg" width="24px"/> C Resources

**Content**

- C Fundamentals
- Libraries
- Data Access
- Web Development
    - Web Frameworks
    - Web Security
- Microservices
- C Tools
- Open-Source Projects
- Directions

## C Fundamentals

### Beginner

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

### Advanced

- C Pointers
    - Pointers on C (1997) by Kenneth A·Reek
    - Understanding and Using C Pointers: Core Techniques for Memory Management (2013) by Richard M Reese
- Deep Dive
    - Expert C Programming: Deep C Secrets (1994) by Peter van der Linden
    - Extreme C: Taking you to the limit in Concurrency, OOP, and the most advanced capabilities of C (2019) by Kamran
      Amini
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

- Hands-On Network Programming with C: Learn socket programming in C and write secure and optimized network code (2019)
  by Lewis Van Winkle
- Beej's Guide to Network Programming: Using Internet Sockets by Brian "Beej Jorgensen" Hall
- TCP/IP Sockets in C: Practical Guide for Programmers by Michael J. Donahoo, Kenneth L. Calvert

Embedded C Programming

- Bare-Metal Embedded C Programming: Develop high-performance embedded systems with C for Arm microcontrollers (2024) by
  Israel Gbati, Georgios Papanikolaou

Resources

## Libraries

### Basic

General Purpose

Logging

Unit Testing

JSON Parser

Document Processing

HTTP Client

### More Libraries

## Data Access

Database Connectivity APIs

Connection Pools

Persistence/ORM Frameworks

Redis clients

MongoDB clients

Elasticsearch clients

## Web Development

### Web Frameworks

Full Stack

Micro/Lightweight

Asynchronous

Web API

Others

Management System Scaffolds

### Web Security

## Microservices

## C Tools

IDE

Package Manager

## Open-Source Projects

**Recommended C open source projects to read**

<details>
    <summary>Click to expand!</summary>

- Systems Programming
    - [Linux Kernel](https://github.com/torvalds/linux). Learn low-level systems programming, memory management, process
      scheduling, drivers.
    - [Xv6](https://github.com/mit-pdos/xv6-public). A teaching operating system (re-implementation of Unix V6). Great
      for learning core OS concepts—syscalls, processes, file systems—in a small codebase.
- Networking / Servers
    - [Redis](https://github.com/redis/redis). High-performance key-value storage system, learning network programming
      and data structure optimization (such as skip lists and hash tables).
    - [Nginx](https://github.com/nginx/nginx). High-performance HTTP and reverse proxy server. Learning event-driven
      architecture, efficient I/O, memory management.
    - [libevent](https://github.com/libevent/libevent). Event notification library for high-performance network servers.
      Learning reactor pattern, select/poll/epoll abstractions.
    - [cURL](https://github.com/curl/curl). Tool and library for transferring data with URLs. Learning robust
      cross-platform network I/O, protocol implementations.
- Tools and Utilities
    - [Git](https://github.com/git/git). Version control system. Learning command line tool design and file version
      management.
    - [htop](https://github.com/htop-dev/htop). Interactive process viewer. Learning terminal UI, process querying,
      cross-platform code.
    - [SQLite](https://github.com/sqlite/sqlite). Self-contained, serverless SQL database engine. Excellent code
      quality, embedded systems focus, ACID-compliant design.
    - [FFmpeg](https://github.com/FFmpeg/FFmpeg). A collection of libraries and tools to process multimedia content such
      as audio, video, subtitles and related metadata.
- GUI / Desktop Apps
    - [mpv](https://github.com/mpv-player/mpv). A media player based on MPlayer/mplayer2. Learning multimedia
      processing, rendering, FFmpeg integration.
    - [GIMP](https://gitlab.gnome.org/GNOME/gimp). GNU Image Manipulation Program (like Photoshop). Learning plugin
      architecture, GUI (GTK), and bitmap/image editing algorithms.
- Educational / Beginner-Friendly Projects
    - [TinyCC](https://github.com/TinyCC/tinycc). A small and fast C compiler. Compact codebase, good for understanding
      compiler internals.
    - [Kilo Text Editor](https://github.com/antirez/kilo). A small, simple text editor (~1000 LOC). Easy to follow,
      terminal handling, file I/O.
    - [cJSON](https://github.com/DaveGamble/cJSON). Lightweight JSON parser in C. Clean, portable, focused on
      readability.
- Embedded / Bare-metal
    - [Micropython (C backend)](https://github.com/micropython/micropython). Python 3 interpreter for microcontrollers.
      Real embedded systems code in C, memory-constrained environments.
    - [OpenWRT](https://github.com/openwrt/openwrt). Embedded Linux distribution for routers. Learn build systems,
      networking protocols, firmware development.
- Others
    - [Lua](https://github.com/lua/lua). Lightweight scripting language, learning virtual machine implementation and
      interpreter design.

</details>

**Application Projects**

## Directions

> C is a foundational programming language widely used in fields that demand direct hardware control, high performance,
> and predictable resource usage. It’s the backbone of much of the modern computing world, especially in systems
> programming, embedded systems, and firmware development.

| Field                    | Example Use Cases                              |
|--------------------------|------------------------------------------------|
| Operating Systems        | Kernels, system calls, drivers                 |
| Embedded Systems & IoT   | Firmware, bare-metal programming               |
| Compilers & Interpreters | GCC, CPython, language VMs                     |
| Databases & Servers      | MySQL, PostgreSQL, NGINX, Redis                |
| Automotive & Medical     | Real-time controllers, safety-critical systems |
| Game & Graphics Engines  | Rendering libraries, graphics APIs             |
| Networking & Protocols   | Network device software, TCP/IP stack          |
| Scientific Computing     | Simulation and math libraries                  |
