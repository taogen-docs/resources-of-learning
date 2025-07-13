# <img src="/assets/icon/programming-languages/Go.svg" width="24px"/> Go Resources

**Content**

- Go Fundamentals
- Utility Libraries
- Data Access
- Web Frameworks
- Web Security
- Microservices
- Go Tools
- Open-Source Projects
- Directions

## Go Fundamentals

Guidance & Roadmap

- [Go Developer Roadmap](https://roadmap.sh/golang)
- [golang-developer-roadmap - GitHub](https://github.com/Alikhll/golang-developer-roadmap)

Beginner

- Documentation
  - [Go Documentation - doc](https://go.dev/doc/)
  - [**Tour of Go**](https://go.dev/tour/welcome/1)
  - [Go by Example](https://gobyexample.com/)
  - [**Effective Go**](https://go.dev/doc/effective_go)
  - [The Go Blog](https://go.dev/blog/all)
- Online Tutorials
  - [Learn X in Y minutes - Go](https://learnxinyminutes.com/docs/go/)
  - [Go Tutorial - W3Schools](https://www.w3schools.com/go/)
  - [Go Tutorial - Tutorialspoint](https://www.tutorialspoint.com/go/)
  - [Learn Golang](https://www.learn-golang.org/)
  - [Learn Go with Tests](https://quii.gitbook.io/learn-go-with-tests)
- **The Go Programming Language** (2015) by Alan A. A. Donovan and Brian W. Kernighan
- **Learning Go: An Idiomatic Approach to Real-World Go Programming** (2nd, 2024) by Jon Bodner
- **Head First Go** (2019) by Jay McGavren
- An Introduction to Programming in Go by Caleb Doxsey [HTML](https://www.golang-book.com/books/intro), [PDF](https://www.golang-book.com/public/pdf/gobook.pdf)
- Go 101 [HTML](https://go101.org/)
- Introducing Go: Build Reliable, Scalable Programs by Caleb Doxsey
- Go Programming Blueprints by Mat Ryer
- Go in Action by William Kennedy, Brian Ketelsen
- Go in Practice (2nd, 2025) by Matt Butcher
- Go Programming - From Beginner to Professional: Learn everything you need to build modern software using Go (2nd, 2024) by Samantha Coyle

Style Guide

- [project-layout - Standard Go Project Layout](https://github.com/golang-standards/project-layout)
- [The Uber Go Style Guide](https://github.com/uber-go/guide)
- [Go Code Review Comments](https://go.dev/wiki/CodeReviewComments)
- [Standard Go Project Layout](https://github.com/golang-standards/project-layout)

<details>
    <summary>对Go的理解</summary>

个人以为，Golang 是类型安全的 C ，仅此而已。Go 的编写负担会比 C 低很多，同时也还有不错的执行效率。但是和其他高级语言比，语法上几乎没什么优越性，在不使用 CGO 的情况下，能够非常方便的跨平台编译，勉强能算一个。

--

服务器用 Go 最省钱, 举个例子,一个后台用 Go 写 6MB, Node 60MB, Java 300MB。

--

go 在 devops 工具开发这个领域没什么对手。

--

golang 就是屎味的巧克力，它的 native 、并发、内存占用低、交叉编译等都是巧克力。但你想吃这个巧克力，就得忍受它语法简陋和各个奇怪的设计（如 if err 、2006-01-02 15:04:05 等）的屎，我用 golang 一般都是一边捏着鼻子一边写的。

--

go 就是一帮写 c 语言的搞出来的云原生时代的 better C ，虽然有很多缺点但是是实实在在的解决了他们最关心的几个痛点，你们在乎的恰恰是他们不太在乎的。

--

Go 的标准库对于业务来说支持的方法是挺简陋的，现在要需要引入三方库，好在生态已经逐渐完善，有很多库可用。go 对于 java 的优势应该主要是原生协程、编译型语言。也确实没有一个特别好用的 orm 库（现在的 goframe 的 orm 组件还行 >> gorm ）。怎么说，要一个开发效率与性能齐驱的语言，目前还是没看到的。  
对于 Java ，个人很讨厌其语法上的臃肿。
rust 其实能够做到开发效率与性能齐驱，无奈上手成本过高，只能覆盖小众方向。
Golang 的定位就是 better C ，我司（某所）在嵌入式 CPU 上运行 web server ，拿 C 开发 web 后端就是折磨，Golang 是从众多语言中被筛选出来的，兼顾运行速度，平台兼容性，交叉编译工具链，库丰富度，内存安全，离线开发等特性，作为一名从 C 里解脱出来的开发人员已经非常知足且感激 Google 了。

--

项目原因,我只能选 go ： 

1. 运行在客户端的,而 go 可以直接生成二进制,不用考虑加密。  
2. 不依赖环境,运行方便  
3. 性能,才 17mb,还是用来 beego 框架,cpu 基本是 0%

--

在主流语言中，Go 是在开发效率，运行效率，还有运维成本三个方面做到了最好的平衡，再吐槽也没用，这个生态位只有 Go 一个选择。

</details>

Advanced

- Go Cookbook: Expert Solutions for Commonly Needed Go Tasks (2023) by Sau Sheong Chang
- Mastering Go: Leverage Go's expertise for advanced utilities, empowering you to develop professional software (4th, 2024) by Mihalis Tsoukalos
- Go for DevOps: Learn how to use the Go language to automate servers, the cloud, Kubernetes, GitHub, Packer, and Terraform (2022) by John Doak (Author), David Justice 
- System Programming Essentials with Go: System calls, networking, efficiency, and security practices with practical projects in Golang (2024) by Alex Rios
- Network Programming with Go: Code Secure and Reliable Network Services from Scratch (2021) by Adam Woodbeck
- Concurrency
  - **Concurrency in Go: Tools and Techniques for Developers** (2017) by Katherine Cox-Buddy
  - Learn Concurrent Programming with Go (2024) by James Cutajar
- Efficient
  - Efficient Go: Data-Driven Performance Optimization by Bartlomiej Plotka
  - 100 Go Mistakes and How to Avoid Them (2022) by Teiva Harsanyi

Code Practice

- [7days-golang - GitHub](https://github.com/geektutu/7days-golang)
- [build-web-application-with-golang - GitHub](https://github.com/astaxie/build-web-application-with-golang)

Resources

- [gotraining - GitHub](https://github.com/ardanlabs/gotraining/tree/master/topics/go)
- [awesome-go - GitHub](https://github.com/avelino/awesome-go)

## Utility Libraries

### Basic Utilities

General Purpose

--

JSON Parser

> Analyze JSON Parsing Library In Go: The fastjson API is the simplest to use; GJSON offers fuzzy searching capabilities and high customizability; jsonparser supports inserting callback functions during high-performance parsing, providing a degree of convenience.

> For my use case, which involves simply parsing specific fields from HTTP response JSON strings with predetermined fields and occasional custom operations, jsonparser is the most suitable tool.

- `encoding/json` package (Built-in)
- [buger/jsonparser](https://github.com/buger/jsonparser). One of the fastest alternative JSON parser for Go that does not require schema
- [valyala/fastjson](https://github.com/valyala/fastjson). Fast JSON parser and validator for Go. No custom structs, no code generation, no reflection.
- [tidwall/gjson](https://github.com/tidwall/gjson). Get JSON values quickly - JSON parser for Go.
- [simdjson-go](https://github.com/minio/simdjson-go). Golang port of simdjson: parsing gigabytes of JSON per second

Document Processing

- Microsoft Office documents
  - [UniOffice](https://unidoc.io/unioffice/) (unidoc/unioffice). Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents.
  - GoDocx (gomutex/godocx). Go library for reading and writing Microsoft Docx
- PDF documents
  - [UniPDF](https://unidoc.io/unipdf/) (unidoc/unipdf). Golang PDF library for creating and processing PDF files (pure go)
  - GoFPDF (jung-kurt/gofpdf)
  - go-wkhtmltopdf (SebastiaanKlippert/go-wkhtmltopdf)

Logging

- `log` package (Built-in)
- `log/slog` package (Built-in)
- [Logrus](https://github.com/sirupsen/logrus). Structured, pluggable logging for Go.
- [Zap](https://github.com/uber-go/zap). Blazing fast, structured, leveled logging in Go.
- [Zerolog](https://github.com/rs/zerolog). Zero Allocation JSON Logger

Unit Testing

- `testing` package (Built-in). It is sufficient for basic unit testing.
- [Testify](https://github.com/stretchr/testify). A toolkit with common assertions and mocks that plays nicely with the standard library.

HTTP Client

- `net/http` package
- [Resty](https://resty.dev/). Simple HTTP, REST, and SSE client library for Go
- [GoRequest](https://parnurzeal.github.io/gorequest/). Simplified HTTP client (inspired by nodejs SuperAgent).
- [Fasthttp](https://github.com/valyala/fasthttp). Fast HTTP package for Go. Tuned for high performance. Zero memory allocations in hot paths. Up to 10x faster than net/http.

### More Utilities

Library List

- [Go Projects - go Wiki](https://go.dev/wiki/Projects)

Browser Automation

- [GoConvey](https://smartystreets.github.io/goconvey/). Write behavioral tests in your editor. Get live results in your browser.

Configuration solution

- [Viper](https://github.com/spf13/viper)
- [joho/godotenv](https://github.com/joho/godotenv). A Go port of Ruby's dotenv library (Loads environment variables from .env files)

JSON Web Token

- [golang-jwt/jwt](https://golang-jwt.github.io/jwt/). Go implementation of JSON Web Tokens (JWT).

## Data Access

Database Connectivity APIs

- [database/sql](https://pkg.go.dev/database/sql) package (Built-in). It includes connection pool.
- [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql). Go MySQL Driver is a MySQL driver for Go's (golang) database/sql package
- [lib/pq](https://github.com/lib/pq). Pure Go Postgres driver for database/sql.

Persistence/ORM Frameworks

- [GORM](https://gorm.io/). A popular and feature-rich ORM that supports MySQL, PostgreSQL, SQLite, SQL Server, and ClickHouse. 
- [sqlc](https://sqlc.dev/). An ORM that generates type-safe code from your SQL queries. 
- [SQLBoiler](https://github.com/aarondl/sqlboiler). Generate a Go ORM tailored to your database schema. An extension of database/sql that provides additional features like named parameters and support for struct scanning.

Redis clients

- [redis/go-redis](https://github.com/redis/go-redis). Redis Go client.
- [RediGo](https://github.com/gomodule/redigo). Go client for Redis.

MongoDB clients

- [mongodb/mongo-go-driver](https://www.mongodb.com/docs/drivers/go/current/). The Official Golang driver for MongoDB.

Elasticsearch clients

- [elastic/go-elasticsearch](https://github.com/elastic/go-elasticsearch). The official Go client for Elasticsearch

## Web Frameworks

<details>
    <summary>关于 Go Web 框架</summary>
不建议用 Go 写 Web ，可以用来完成一些基础设施类工作。Go 这边的 Web 框架，比如 gin 那种，其实都是非常轻量级的，属于 http 增强库，和 spring 全家桶不是一回事。Go 这边我觉得可以认为不具有诞生 springboot 类的土壤。

Go 的 Web 框架基本都是标准库套壳。也可以看看 fiber 这种用 fasthttp 的。

Go 是用来写底层服务的，不适合写应用层面的东西。

gin，其他想要什么组件可以自己加上去。

可以自己试着用用，组合出一套顺手的技术栈。
</details>

Books

- Go Web Programming (2016) by Chang Sau Sheong
- Modern Web Development with Go: Build real-world, fast, efficient and scalable web server apps using Go programming language (2023) by Dušan Stojanović 

Web Frameworks

- [Gin](https://gin-gonic.com/). The fastest full-featured web framework for Go. Crystal clear.
- [FastHTTP](https://github.com/valyala/fasthttp). Fast HTTP package for Go. Tuned for high performance. Zero memory allocations in hot paths. Up to 10x faster than net/http.
- [Echo](https://echo.labstack.com/) - High-performance. High performance, extensible, minimalist Go web framework
- [Beego](https://github.com/beego/beego) - High-performance. high-performance web framework for the Go programming language.
- [Fiber](https://gofiber.io/) - Rapid development. An Express-inspired web framework written in Go.

Web Application Scaffolds

- [eagle](https://github.com/go-eagle/eagle). A Go framework for the API or Microservice.

## Web Security

--

## Microservices

Books

- **Cloud Native Go: Building Reliable Services in Unreliable Environments** (2021) by Matthew Titmus

Frameworks & Libraries

- [Go kit](https://gokit.io/). A standard library for microservices.

## Go Tools

IDE

- GoLand
- Visual Studio Code

Package Manager

- [Go Modules](https://go.dev/ref/mod)


## Open-Source Projects

**Recommended Go open source projects to read**

<details>
    <summary>Click to expand!</summary>

- Standard Tools and Libraries
	- [Go Standard Library](https://cs.opensource.google/go/go). It's well-designed, idiomatic, and high-quality. Start with packages like `net/http`, `io`, `context`, and `sync`.
- DevOps / Tools
	- [Docker (initial version written in Go)](https://github.com/moby/moby). Container engine. Learn about Linux namespaces, networking, and system call usage via Go.
	- [K3s](https://github.com/k3s-io/k3s). Lightweight Kubernetes distribution. Learn embedded Go systems, API-driven architecture, Kubernetes internals.
- Web Frameworks / HTTP Servers
	- [Caddy](https://github.com/caddyserver/caddy). HTTP/2 web server with automatic HTTPS. Learn plugin architecture, modular Go design, TLS integration.
	- [Gin](https://github.com/gin-gonic/gin). Popular high-performance HTTP web framework. Learn routing, middleware, context management, JSON handling.
	- [Fiber](https://github.com/gofiber/fiber). Express-inspired web framework built on fasthttp. Learn performance optimization, minimalist design.
- Networking / CLI Tools
	- [gitleaks](https://github.com/gitleaks/gitleaks). Secrets detection for Git repos. Learn regex, file scanning, command-line design.
	- [httpie-go](https://github.com/httpie/httpie-go). A friendly CLI HTTP client. Great for learning argument parsing, API requests, and output formatting.

</details>

**Application Projects**

--

## Directions

### CLI Application Development

Books

- Powerful Command-Line Applications in Go: Build Fast and Maintainable Tools (2021) by Ricardo Gerardi
- Building Modern CLI Applications in Go: Develop next-level CLIs to improve user experience, increase platform usage, and maximize production (2023) by Marian Montagnino

Frameworks & Libraries

- [Cobra](https://cobra.dev/). A Framework for Modern CLI Apps in Go. A Commander for modern Go CLI interactions.

### Infrastructure Development

Web Server Development

- [GorillaMUX](https://gorilla.github.io/). A helpful toolkit for the Go programming language that provides useful, composable packages for writing HTTP-based applications.
