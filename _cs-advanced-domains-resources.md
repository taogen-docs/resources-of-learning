# CS Advanced Domains Resources

> Practice makes perfect.

> Your best teacher is your last mistake.

> Quality not quantity.

### Content

- Part I: Developments
  - <a name="webdev_c" href="#webdev_t">Web Development</a>
  - <a name="gamedev_c" href="#gamedev_t">Game Development</a>
  - Mobile Application Development
  - Desktop Application Development
  - Embedded Development
  - <a name="audio_and_video_dev_c" href="#audio_and_video_dev_t">Audio and Video Development</a>
- Part II: Infrastructures
  - <a name="dbms_c" href="#dbms_t">Database Systems and Data Storage</a>
  - <a name="inforetri_c" href="#inforetri_t">Information Retrieval and Search Engines</a>
  - <a name="web_services_c" href="#web_services_t">Web Services</a>
  - <a name="rpc_c" href="#rpc_t">Remote Procedure Call (RPC)</a>
  - <a name="mq_c" href="#mq_t">Message Queues</a>
  - <a name="infosec_c" href="#infosec_t">Information Security</a>
  - <a name="distsys_c" href="#distsys_t">Distributed Systems</a>
  - <a name="cloudcpt_c" href="#cloudcpt_t">Cloud Computing and Serverless</a>
  - <a name="datamining_c" href="#datamining_t">Big Data and Data Mining</a>
  - <a name="crawler_c" href="#crawler_t">Crawler and  Anti-Crawler</a>
- Part III: The Future
  - <a name="ai_c" href="#ai_t">Artificial Intelligence</a>
  - <a name="blockchain_c" href="#blockchain_t">Blockchain and Cryptocurrency</a>
  - Edge Computing
  - IoT and 5G
  - Virtual Reality (VR) and Augmented Reality (AR)
  - Metaverse
  - <a name="quantcomp_c" href="#quantcomp_t">Quantum Computing</a>
  - Web 3.0

<br>

<h2><a name="webdev_t" href="#webdev_c">Web Development</a></h2>
<br>

### Web Frontend

Reference [Web Frontend Resources](directions/web-frontend-resources.md)

### Web Backend

#### Web Application

Reference [Web Backend - Java Resources](directions/java-resources.md)

#### API Design

- API Design Patterns (2021) by JJ Geewax
- The Design of Web APIs (2019) by Arnaud Lauret

#### CORS

- CORS in Action: Creating and consuming cross-origin APIs (2014) by Monsur Hossain

#### Authentication & Authorization

>In essence, you can use OAuth 2.0 alone if you only need to authorize access to resources. However, if you need to verify the user's identity and enable SSO, you should use OIDC, which builds upon OAuth 2.0.

OAuth 2

>The industry-standard protocol for authorization.

- OAuth 2 in Action (2017) by Justin Richer, Antonio Sanso [4.28, 176]
- OAuth 2.0 Simplified (2018) by Aaron Parecki [4.02, 42]
- OAuth 2.0: Getting Started in API Security (2014) by Matthias Biehl [3.82, 87]
- Advanced API Security: OAuth 2.0 and Beyond (2019) by Prabath Siriwardena [3.90, 20]
- Cloud Identity Patterns and Strategies: Design enterprise cloud identity models with OAuth 2.0 and Azure Active Directory (2022) by Giuseppe Di Federico, Fabrizio Barcaroli 

OpenID Connect (OIDC)

> An authentication protocol built on top of OAuth 2.0.

- OpenID Connect in Action (2024) by Prabath Siriwardena

OAuth 2 and OIDC

- Solving Identity Management in Modern Applications: Demystifying OAuth 2, OpenID Connect, and SAML 2 (2nd, 2022) by Yvonne Wilson, Abhishek Hingnikar [3.76, 66]
- Keycloak - Identity and Access Management for Modern Applications: Harness the power of Keycloak, OpenID Connect, and OAuth 2.0 to secure applications (2nd, 2023) by Stian Thorgersen and Pedro Igor Silva [3.90, 21]

#### Web Application Security

Web Application Security

- API Security in Action (2020) by Neil Madden
- Bulletproof SSL and TLS: The Complete Guide to Deploying Secure Servers and Web Applications by Ivan Ristic
- Web Application Security: Exploitation and Countermeasures for Modern Web Applications by Andrew Hoffman
- [API Security Best Practices - Roadmap](https://roadmap.sh/best-practices/api-security)

#### Web Servers

<img src="/assets/icon/advanced-domains/Nginx.svg" width="24px"/>Nginx

/engine-x/

- [nginx documentation](http://nginx.org/en/docs/)
- [The Complete NGINX Cookbook](https://www.nginx.com/resources/library/complete-nginx-cookbook/?utm_source=nginxorg&utm_medium=books&utm_campaign=ebooks) (2019) by Derek DeJonghe
- [Deploying NGINX Plus as an API Gateway](https://www.nginx.com/resources/library/nginx-api-gateway-deployment/?utm_source=nginxorg&utm_medium=books&utm_campaign=ebooks) (2018) by Liam Crilly
- [High-Performance Caching with NGINX and NGINX Plus](https://www.nginx.com/resources/library/high-performance-caching-with-nginx-and-nginx-plus/?utm_source=nginxorg&utm_medium=books&utm_campaign=ebooks) (2018) by Owen Garrett
- [Load Balancing in the Cloud: Practical Solutions with NGINX and AWS](https://www.nginx.com/resources/library/load-balancing-in-the-cloud-aws-nlb-elb-nginx-plus/?utm_source=nginxorg&utm_medium=books&utm_campaign=ebooks) (2018) by Derek DeJonghe
- [F5 BIG-IP to NGINX Plus: Migration Guide](https://www.nginx.com/resources/library/f5-big-ip-nginx-migration-guide/?utm_source=nginxorg&utm_medium=books&utm_campaign=ebooks) (2018) by Faisal Memon, Alan Murphy
- [How to Easily and Cost Effectively Replace Cisco ACE](https://www.nginx.com/resources/library/cisco-ace-nginx-migration-guide/?utm_source=nginxorg&utm_medium=books&utm_campaign=ebooks) (2018) by Faisal Memon
- [ModSecurity 3.0 and NGINX: Quick Start Guide](https://www.nginx.com/resources/library/modsecurity-3-nginx-quick-start-guide/?utm_source=nginxorg&utm_medium=books&utm_campaign=ebooks) (2018) by Faisal Memon, Owen Garrett, Michael Pleshakov
- Nginx HTTP Server: Harness the power of Nginx to make the most of your infrastructure and serve pages faster than ever before (4th, 2018) by Martin Fjordvald and Clement Nedelcu
- Mastering NGINX (2nd, 2016) by Dimitri Aivaliotis 
- NGINX Cookbook: Advanced Recipes for High-Performance Load Balancing (2nd, 2022) by Derek DeJonghe
- Nginx Essentials: Excel in Nginx quickly by learning to use its most essential features in real-life applications (2015) by Valery Kholodkov
- NGINX Cookbook: Over 70 recipes for real-world configuration, deployment, and performance (2017) by Tim Butler
- 深入理解Nginx by  陶辉 

Nginx resources

- [NGINXConfig - DigitalOcean](https://www.digitalocean.com/community/tools/nginx).The easiest way to configure a performant, secure, and stable NGINX server.

Nginx Unit

- [Learn NGINX Unit with Zero Pain - YouTube](https://www.youtube.com/playlist?list=PLGz_X9w9raXdV3vuPUu0kKBSBjG9rPaUf)
- NGINX Unit Cookbook: Recipes for Using a Versatile Open Source Server (2020) by Derek DeJonghe

Apache Tomcat

/əˈpatʃi - ˈtɒmkat/

- How Tomcat Works: A Guide to Developing Your Own Java Servlet Container by Budi Kurniawan, Paul Deck 

#### Backend Performance

- [Backend Performance Best Practices - Roadmap](https://roadmap.sh/best-practices/backend-performance)

#### Backend Interview Questions

- [Popular Backend Developer Interview Questions - Roadmap](https://roadmap.sh/questions/backend)

<br>
<h2><a name="gamedev_t" href="#gamedev_c">Game Development</a></h2>

<br>

### Guidance

- [Best Game Development Roadmap-2021](https://www.codelivly.com/game-development-roadmap-2021/)
- [The 2020 Game Developer Roadmap](https://www.programming-hero.com/blog/the-2020-game-developer-roadmap.html)

<details>
    <summary>关于游戏开发</summary>

能熬夜加班到 2-3 点就行，其他不重要。

游戏行业最大的特点基本是赢家通吃，如果你进不了头部几家公司，其他公司基本生存维艰。

做游戏不如写游戏脚本，入门快，获取收益快，做国外的就行。

国内的做游戏的得看能不能跟好的项目，好的项目非常非常少，其它的 90% 都是熬时间、做功能， 加班能加到你吐，加班到凌晨 2-3 点也是常事，再牛逼的热情也会给你浇灭了。

</details>


### Game Engines

> A game engine, also known as a game architecture, game framework, is a software development environment designed for game developers. There are many game engines available such as GameMaker, Godot, OpenGL, Unity, Unreal Engine, etc.

#### <img src="/assets/icon/advanced-domains/Unity.svg" width="24px"/>Unity and C#

/ˈjuːnɪti/

> the most user-friendly gaming engine for beginners

- [Unity User Manual 2021.2](https://docs.unity3d.com/2021.2/Documentation/Manual/index.html)
- Developing 2D Games with Unity: Independent Game Programming with C# by Jared Halpern
- Unity in Action by Joseph Hocking
- Unity Game Development Cookbook: Essentials for Every Game by Paris Buttfield-Addison, Jon Manning, Tim Nugent
- Learning C# by Developing Games with Unity 2020: An enjoyable and intuitive approach to getting started with C# programming and Unity, 5th Edition by Harrison Ferrone

#### Unreal Engine and C++

- Unreal Engine 4 Game Development in 24 Hours, Sams Teach Yourself by Aram Cookson, Tim Johnson, Clinton Crumpler
- Unreal Engine Physics Essentials by Katax Emperore, Devin Sherry

#### Gamemaker and JavaScript, C++ or C#

### Game Design

> Game Mechanics are the basic actions, processes, visuals, and control mechanisms that are used to “gamify” an activity.

- The Art of Game Design: A Book of Lenses by Jesse Schell
- A Theory of Fun for Game Design by Raph Koster
- Rules of Play: Game Design Fundamentals by Katie Salen, Eric Zimmerman
- Game Design Workshop: A Playcentric Approach to Creating Innovative Games by Tracy Fullerton
- Level Up!: The Guide to Great Video Game Design by Scott Rogers
- Game Feel: A Game Designer's Guide to Virtual Sensation y Steve Swink
- Fundamentals of Game Design by Ernest Adams, Andrew Rollings
- Game Mechanics: Advanced Game Design by Ernest Adams, Joris Dormans
- Game Programming Patterns by Robert Nystrom
- Advanced Game Design: A Systems Approach by Michael Sellers


### Game Physics and Animation

> Interactive experiences

- Game Physics Engine Development: How to Build a Robust Commercial-Grade Physics Engine for your Game by Ian Millington
- Game Physics by David H. Eberly
- Game Engine Architecture by Jason Gregory
- Physics for Game Developers by David M. Bourg
- Foundations of Game Engine Development, Volume 1: Mathematics by Eric Lengyel
- Foundations of Game Engine Development, Volume 2: Rendering by Eric Lengyel
- Real-Time Collision Detection by Christer Ericson
- Real-Time Rendering by Tomas Akenine-Möller, Eric Haines
- Planning Algorithms by Steven M. LaValle
- Physically Based Rendering: From Theory to Implementation by Matt Pharr
- The Ray Tracer Challenge by Jamis Buck 

### Math for Game Programming

> Algebra and Linear Algebra, Trigonometry, Calculus, Discrete Mathematics

- Mathematics for 3D Game Programming and Computer Graphics by Eric Lengyel


### Developing Games

> 3D and 2D games
>
> virtual reality or argumented reality games
>
> Multi-player Game

- Game Programming Patterns by Robert Nystrom
- BASIC Computer Games by David H. Ahl


## Embedded Development

- Making Embedded Systems: Design Patterns for Great Software (2nd, 2024) by Elecia White
- Applied Embedded Electronics: Design Essentials for Robust Systems (2023) by Jerry Twomey
- Hands-On RTOS with Microcontrollers: Building real-time embedded systems using FreeRTOS, STM32 MCUs, and SEGGER debug tools (2020) by Brian Amos
- Mastering Embedded Linux Programming: Create fast and reliable embedded solutions with Linux 5.4 and the Yocto Project 3.1 (3rd, 2021) by Frank Vasquez, Chris Simmonds
- Bare-Metal Embedded C Programming: Develop high-performance embedded systems with C for Arm microcontrollers (2024) by Israel Gbati

<br>

<h2><a name="audio_and_video_dev_t" href="#audio_and_video_dev_c">Audio and Video Development</a></h2>

<br>

### Capture

- audio: pcm
- video: YUV, RGB
- capture on mobiles
- capture on PCs
- capture on embedded devices

### Encoding and decoding

Video

- ISO-MPEG/ITU-T: H264(AVC), H265(HEVC), H266(VVC)
- AOM: VP8, VP9, AV1
- AVS2, AVS3

Audio

- G7xx, AAC, MP3, Opus, PCM
- G72x, ilbc

Libraries and frameworks

- x264, x265, libaac, libhevc, FD-AAC

### Encapsulation formats

- MPEG-PS, MPEG-TS, MP4, FLV, WebM
- MVK, TS, RMVB, MP3, ogg

### Streaming Media Transmission

On-demand

- HTTP/HTTPS, HLS, DASH, HTTP-HLV

Live Broadcast

- RTP/RTCP, RTMP, RTSP, HLS, HTTP-FLV, DASH

Other

- SIP/SDP, WebSocket, SRT, QUIC, CDN, WebRTC

Advanced

- P2P
  - TURN
  - STUN
- Reliable UDP
- Packet retransmission
  - ARQ
- Congestion control
  - BBR, GCC, PCC
- Error correction
  - FEC
- jitter-Buffer

Libraries and frameworks

- Live555
- libRTMP
- Nginx-RTMP
- flv.js\hls.js
- pjsip

### Players

Process

- Transmission protocol parsing
- Video stream IO (pull stream)
- Decapsulation
- Decode
- Audio and video synchronization
- Rendering
  - mobile
  - PC
  - OpenGL, OpenGL ES, Direct3D, SDL

Concepts

- IBP frame
- SPS, PPS, VPS
- PTS, DTS
- SEI

Render libraries and frameworks

- Open CV, OPenGL, OpenGL ES (Android), Canvas, Direct 3D, metal, vulcan

Second open technology

### Processing and analysis

Video processing

- Traditional image processing: sharpening, denoising, contrast, brightness, anti-shake
- Filters, watermarks, cropping, compositing, transcoding

Video analysis (AI)

- Motion detection, face detection and recognition, license plate recognition, people flow statistics
- Classification, detection, segmentation

Audio processing

- Voice enhancement, echo cancellation, noise reduction, voice changer

Audio analysis (AI)

- Speech recognition, speech synthesis, semantic understanding

### Engineering

- FFMEPG
- WebRTC
  - Janus
  - Licode
  - MediaSoup
- ijkplayer
- mpv
- vlc
- SRS
- GStreamer
- ZLMediaKit

<br>

<h2><a name="dbms_t" href="#dbms_c">Database Systems and Data Storage</a></h2>
<br>


### Relational Databases

>Store data in structured formats using rows and columns in tables. Relationships between tables are established via foreign keys

>Use Cases: Transactional systems, business applications, and data integrity-centric tasks.

#### <img src="/assets/icon/advanced-domains/Mysql.svg" width="24px"/>MySQL

/maɪ ˈɛs kjuː ˈɛl/ or /my sequel/

Beginner

- Beginner-friendly books
  - **Murach's MySQL** (4th, 2023) by Joel Murach
- MySQL 5.7 Reference Manual. [DOC](https://dev.mysql.com/doc/refman/5.7/en/ ), [PDF](https://downloads.mysql.com/docs/refman-5.7-en.pdf)
- MySQL 5.7 Release Notes - [DOC]( https://dev.mysql.com/doc/relnotes/mysql/5.7/en/ )
- MySQL 8.0 Reference Manual. [DOC](https://dev.mysql.com/doc/refman/8.0/en/), [PDF](https://downloads.mysql.com/docs/refman-8.0-en.pdf)
- MySQL 8.0 Release Notes - [DOC]( https://dev.mysql.com/doc/relnotes/mysql/8.0/en/ )
- **Learning MySQL: Get a Handle on Your Data** (2nd, 2021) by Vinicius Grippa, Sergey Kuzmichev
- MySQL Crash Course by Ben Forta
- MySQL in a Nutshell by Russell J.T. Dyer
- **MySQL** (5th, 2014) by Paul DuBois
- **MySQL Cookbook** (4rd, 2022) by Sveta Smirnova and Alkin Tezuysal
- MySQL Stored Procedure Programming: Building High-Performance Web Applications in MySQL by Guy Harrison, Steven Feuerstein
- MySQL Pocket Reference: SQL Functions and Utilities (2nd, 2007) by George Reese

Administration

- MySQL Administrator's Bible by Sheeri K. Cabral, Keith Murphy
- Hands-On MySQL Administration: Managing MySQL on Premises and in the Cloud (2024) by Arunjith Aravindan, Jeyaram Ayyalusamy
- Mastering MySQL Administration: High Availability, Security, Performance, and Efficiency (2024) by Y V Ravi Kumar, Arun Kumar Samayam, Naresh Kumar Miryala 

Optimization

- **High Performance MySQL** by Baron Schwartz (4th, 2021) (3rd, 2012, This 3rd edition of the book mainly based on MySQL 5.1 and 5.5.) 
- Efficient MySQL Performance: Best Practices and Techniques (2022) by Daniel Nichter
- Effective MySQL Optimizing SQL Statements by Ronald Bradford
- MySQL性能调优与架构设计 by 简朝阳 
- Relational Database Index Design and the Optimizers by Tapio Lahdenmaki 
- MySQL Troubleshooting: What To Do When Queries Don't Work by Sevta Smirnova
- MySQL 8 Query Performance Tuning: A Systematic Method for Improving Execution Speeds (2020) by Jesper Wisborg Krogh
- MySQL 8 Cookbook: Over 150 recipes for high-performance database querying and administration (2018) by Karthik Appigatla
- MySQL 8 Administrator's Guide: Effective guide to administering high-performance MySQL 8 solutions (2018) by Chintan Mehta , Ankit Bhavsar
- Advanced MySQL 8: Discover the full potential of MySQL and ensure high performance of your database (2019) by Eric Vanier , Birju Shah
- [深入MySQL实战：快速理解MySQL核心技术 - 阿里云](https://developer.aliyun.com/ebook/450)

High Availability, Cluster, Backup and Replication

- Reference Guide for InnoDB Cluster. [DOC](https://dev.mysql.com/doc/refman/8.0/en/mysql-innodb-cluster-userguide.html)
- Reference Guide for MySQL NDB Cluster. [DOC](https://dev.mysql.com/doc/refman/8.0/en/mysql-cluster.html), [PDF](https://downloads.mysql.com/docs/mysql-cluster-excerpt-8.0-en.pdf)
- MySQL NDB Cluster Internals Manual - [DOC]( https://dev.mysql.com/doc/ndb-internals/en/ )
- MySQL High Availability: Tools for Building Robust Data Centers (2nd, 2014) by Charles Bell
- Introducing Innodb Cluster: Learning the MySQL High Availability Stack (2018) by Charles Bell
- High Availability MySQL Cookbook by Alex Davies
- Pro MySQL NDB Cluster by Jesper Wisborg Krogh and Mikiya Okuno
- Effective MySQL Backup and Recovery by Ronald Bradford
- Effective MySQL Replication Techniques in Depth

MySQL Internal and Programming

- [MySQL Internals Manual - doc]( https://dev.mysql.com/doc/internals/en/ )
- [MySQL  8.0.18 Source Code Documentation]( https://dev.mysql.com/doc/dev/mysql-server/latest/ )
- [MySQL Connector/J 5.1 Developer Guide - doc]( https://dev.mysql.com/doc/connector-j/5.1/en/ )
- Expert MySQL  by Charles A Bell
- Understanding MySQL Internals by Sasha Pachev
- MySQL 技术内幕：InnoDB存储引擎 by  姜承尧 
- MySQL 内核：InnoDB存储引擎 by  姜承尧
- MariaDB 原理与实现 by 张金鹏
- MySQL是怎样运行的：从根儿上理解 MySQL by 小孩子4919


#### <img src="/assets/icon/advanced-domains/Postgresql.svg" width="24px"/>PostgreSQL

/Post-Gres-Q-L/ or /Postgres/

- [PostgreSQL Documentation](https://www.postgresql.org/docs/current/index.html)
- [PostgreSQL Tutorials & Other Resources](https://www.postgresql.org/docs/online-resources/)
- Online tutorials
  - [PostgreSQL Tutorial](https://www.postgresqltutorial.com/)
  - [PostgreSQL Tutorial - TutorialsPoint](https://www.tutorialspoint.com/postgresql/index.htm)
  - [PostgreSQL Primer for Busy People](https://zaiste.net/posts/postgresql-primer-for-busy-people/)
- [PostgreSQL Exercises](https://pgexercises.com/)
- Learn PostgreSQL (2nd, 2023) by Luca Ferrari, Enrico Pirozzi
- PostgreSQL 16 Administration Cookbook (2023) by Gianni Ciolli, Boriss Mejías, Jimmy Angelakos
- PostgreSQL: Up and Running: A Practical Guide to the Advanced Open Source Database (3rd, 2017) by Regina Obe, Leo Hsu
- PostgreSQL Configuration: Best Practices for Performance and Security (2020) by Baji Shaik
- Mastering PostgreSQL 15 (5th, 2023) by Hans-Jürgen Schönig
- PostgreSQL Query Optimization (2nd, 2024) by Henrietta Dombrovskaya, Database expert, Anna Bailliekova
- Just Use Postgres: A fast guide for developers (2025) by Denis Magda
- [A Tour of PostgreSQL Internals](https://www.postgresql.org/files/developer/tour.pdf)
- [PostgreSQL 14 Internals: A deep dive into the server mechanics](https://postgrespro.com/community/books/internals)
- The Internals of PostgreSQL by Hironobu Suzuki [online book](https://www.interdb.jp/pg/)

#### <img src="/assets/icon/advanced-domains/Oracle.svg" width="24px"/>Oracle

/ˈɒrəkl/

Prime

- Beginning Oracle SQL for Oracle Database 18c: From Novice to Professional by Ben Brumm
- [Oracle Database 12c Release 2 - doc](https://docs.oracle.com/en/database/oracle/oracle-database/12.2/index.html)
- Oracle Essentials: Oracle Database 12c by Jonathan P. Stern, Rick Greenwald, and Robert Stackowiak
- OCA Oracle Database SQL Exam Guide (Exam 1Z0-071) by Steve O'Hearn
- OCA Oracle Database 12c SQL Fundamentals I Exam Guide by Roopesh Ramklass
- Oracle Database 12c: The Complete Reference by Bob Bryla and Kevin Loney


PL/SQL

- **Oracle PL/SQL Programming** (6th, 2014) by Steven Feuerstein, Bill Pribyl
- Oracle Database 12c Pl/SQL Advanced Programming Techniques by Michael McLaughlin, John M. Harper
- Mastering Oracle SQL by Alan Beaulieu and Mishra Sanjay
- Murach's Oracle SQL and PL/SQL for Developers by Joel Murach
- Oracle Database 12c Pl/SQL Programming by Michael McLaughlin
- Oracle PL/SQL Best Practices by Steven Feuerstein

Administration

- Beginning Oracle Database 12c Administration: From Novice to Professional by Ignatius Fernandez
- Oracle DBA Mentor: Succeeding as an Oracle Database Administrator by Brian Peasland
- [Database 2 Day DBA](https://docs.oracle.com/database/121/ADMQS/toc.htm)

Advanced

- OCA/OCP Oracle Database 12c All‑in‑One Exam Guide by Bob Bryla, John Watson, and Roopesh Ramklass
- Effective Oracle by design by Thomas Kyte
- Expert one-on-one Oracle by Thomas Kyte
- Troubleshooting Oracle Performance by Christian Antognini
- Expert Oracle Database Architecture by Thomas Kyte
- **Oracle Database 12c Release 2 Performance Tuning Tips & Techniques** (2017) by Richard Niemiec
- **Oracle Database 11g Release 2 Performance Tuning Tips & Techniques** by Richard Niemiec
- Optimizing Oracle Performance: A Practitioner's Guide to Optimizing Response Time (2003) by Cary Millsap, Jeff Holt
- Oracle High Availability, Disaster Recovery, and Cloud Services: Explore RAC, Data Guard, and Cloud Technology by Ravi Kumar 

Tutorials

- [Oracle Live SQL](https://livesql.oracle.com/apex/livesql/file/index.html) - It allows you to run Oracle code and queries in an actual database, via a web interface. It's hooked up to our documentation libraries
- [Ask Tom](http://asktom.oracle.com/)
- [PL/SQL Challenge](http://plsqlchallenge.oracle.com/) - A website offering new quizzes each week on SQL, PL/SQL, Database Design, Application Express and Logic. Test your knowledge against others, and also access a library of over 1400 past quizzes on which to practice.

### Key-Value Databases 

>Key-Value databases store data as pairs of keys and values. Each key is unique, and the corresponding value can be a simple data type or a complex object. 

>Key-Value databases are excellent for simple, high-speed access to individual values based on unique keys.

>Use Cases: Caching, user sessions, shopping carts, and other scenarios where rapid lookups by unique identifiers are essential.

#### <img src="/assets/icon/advanced-domains/Redis.svg" width="24px"/>Redis

/ˈrɛd-ɪs/

Must Read

- [Redis Documentation](https://redis.io/documentation)
- **The Little Redis Book** (Free Book, 2012) by Karl Seguin. [GitHub](https://github.com/karlseguin/the-little-redis-book), [Book](https://www.openmymind.net/2012/1/23/The-Little-Redis-Book/)
- **Redis in Action** (2013) by Josiah L. Carlson
- **Redis Cookbook** (2011) by Tiago Macedo and Fred Oliveira
- Redis设计与实现 by 黄健宏
- Redis应用实例 by 黄健宏
- Redis 深度历险：核心原理与应用实践 by 钱文品

Some More

- Redis Stack for Application Modernization: Build real-time multi-model applications at any scale with Redis (2023) by Luigi Fugaro, Mirko Ortensi
- Learning Redis by Vinoo Das
- Redis Essentials: Harness the power of Redis to integrate and manage your projects efficiently (2015) by Maxwell Dayvson Da Silva, Hugo Lopes Tavares
- Redis 4.x Cookbook: Over 80 hand-picked recipes for effective Redis development and administration (2018) by Pengcheng Huang and Zuofei Wang
- Mastering Redis (2016) by Jeremy Nelson
- Instant Redis Optimization How-to (2013) by Arun Chinnachamy
- Instant Redis Persistence (2013) by Matt Palmer

Tutorials

- [Try Redis](http://try.redis.io/)

### Document Databases

>Document databases store data in documents, which are typically JSON, BSON, or XML format. Each document is a self-contained data unit that can contain nested structures. 

>Document databases offer more complex data structures and querying capabilities suitable for applications that require handling rich, nested data.

>Use Cases: Content management systems, e-commerce applications, real-time analytics, and data that naturally fits into a document structure.

#### <img src="/assets/icon/advanced-domains/Mongodb.svg" width="24px"/>MongoDB

/mohn-go-dee-bee/

- [MongoDB Documentation](https://www.mongodb.com/docs/)
- **MongoDB: The Definitive Guide: Powerful and Scalable Data Storage** (3rd, 2019) by Shannon Bradshaw, Eoin Brazil, Kristina Chodorow
- MongoDB Applied Design Patterns: Practical Use Cases with the Leading NoSQL Database by Rick Copeland  

### Wide-Column / Column-Family Databases

>Store data in columns rather than rows, which can improve performance for queries involving large datasets with sparse data.

>Use Cases: Data warehousing, analytics, and real-time data processing.

Cassandra, HBase

### Graph Databases

>Designed to handle data structured as graphs, where entities are nodes and relationships are edges, suitable for representing and querying interconnected data.

>Use Cases: Social networks, recommendations, fraud detection, and network analysis.

Neo4j, Amazon Neptune.

### Time Series Databases (TSDB)

>Specifically designed to handle time-stamped data and optimized for time-based queries and aggregations.

>Use Cases: Monitoring systems, IoT data management, financial market analysis.

InfluxDB, TimescaleDB, Prometheus, OpenTSDB.

### Multi-model Database

Fauna DB

<br>

<h2><a name="inforetri_t" href="#inforetri_c">Information Retrieval and Search Engines</a></h2>

<br>

### Information Retrieval

- Introduction to information retrieval by Christopher D. Manning, Hinrich Schütze, and Prabhakar Raghavan
- Information Retrieval: Implementing and Evaluating Search Engines by Charles L. A. Clarke, Gordon Cormack, and Stefan Büttcher
- Managing gigabytes by Ian H. Witten
- Search Engines: Information Retrieval in Practice by Donald Metzler, Trevor Strohman, and W. Bruce Croft
- Lucene in Action by Erik Hatcher and Otis Gospodnetić
- Information Retrieval: Data Structures and Algorithms by William B. Frakes, Ricardo Baeza-Yates
- Google's Pagerank and Beyond: The Science of Search Engine Rankings by Amy N. Langville, Carl D. Meyer
- Modern Information Retrieval by Berthier Ribeiro-Neto

### Full-Text Search Engines

- [Apache LuceneTM 7.4.0 Documentation](https://lucene.apache.org/core/7_4_0/index.html)
- [Apache Solr Reference Guide](https://lucene.apache.org/solr/guide/)

Elastic Stack

- Elastic Stack 8.x Cookbook: Over 80 recipes to perform ingestion, search, visualization, and monitoring for actionable insights (2024) by Huage Chen , Yazid Akadiri
- Learning Elastic Stack 7.0: Distributed search, analytics, and visualization using Elasticsearch, Logstash, Beats, and Kibana (2nd, 2019) by Pranav Shukla and Sharath Kumar M N
- Getting Started with Elastic Stack 8.0: Run powerful and scalable data platforms to search, observe, and secure your organization (2022) by Asjad Athick 

<img src="/assets/icon/advanced-domains/Elasticsearch.svg" width="24px"/>Elasticsearch

/ɪˈlæs.tɪk-səːtʃ/

- [Elasticsearch Documentation](https://www.elastic.co/guide/index.html)
- Elasticsearch: The Definitive Guide: A Distributed Real-Time Search and Analytics Engine (2015) by Clinton Gormley and Zachary Tong
- Elasticsearch in Action (2nd, 2023) by Madhusudhan Konda
- Elasticsearch 8 for Developers: A beginner's guide to indexing, analyzing, searching, and aggregating data (2nd, 2023) by Anurag Srivastava
- Vector Search for Practitioners with Elastic: A toolkit for building NLP solutions for search, observability, and security using vector search (2023) by Bahaaldine Azarmi and Jeff Vestal
- Relevant Search: With applications for Solr and Elasticsearch (2016)by Doug Turnbull and John Berryman
- Elasticsearch Data Modeling and Schema Design (2023) by Steve Hoberman and Rafid Reaz
- Elasticsearch 8.x Cookbook - Fifth Edition: Over 180 recipes to perform fast, scalable, and reliable searches for your enterprise (5th, 2022) by Alberto Paro 

Kibana

/kee-BAH-nah/ (The "BAH" is the loudest part of the word.)

- Kibana 8.x - A Quick Start Guide to Data Analysis: Learn about data exploration, visualization, and dashboard building with Kibana (2024) by Krishna Shah
- Learning Kibana 7: Build powerful Elastic dashboards with Kibana's data visualization capabilities (2nd, 2019) by Anurag Srivastava and Bahaaldine Azarmi
- Kibana 7 Quick Start Guide: Visualize your Elasticsearch data with ease (2019) by Anurag Srivastava


<h2><a name="web_services_t" href="#web_services_c">Web Services</a></h2>

Java RESTful and SOAP Web Services

>Java API for RESTful Web Services (JAX-RS): It provides a declarative and intuitive way to build RESTful web services in Java by leveraging annotations to define resource behavior and manage interactions with HTTP requests and responses.

>JAX-RS is nothing more than a specification, a set of interfaces and annotations offered by Java EE. And then, of course, we have the implementations; some of the more well known are RESTEasy and Jersey.

>Java API for XML Web Services (JAX-WS): It is a Java programming API used for creating web services, particularly SOAP-based services. It is a key part of the Java Platform, Enterprise Edition (Java EE) and later Jakarta EE. 

- [Java Web Services - Java EE Documentation](https://javaee.github.io/tutorial/partwebsvcs.html)
- Java Web Services: Up and Running: A Quick, Practical, and Thorough Introduction (2nd, 2013) (1st, 2009) by Martin Kalin
- Java Web Services: Using Java in Service-Oriented Architectures (2002) by David A. Chappell, Tyler Jewell 
- Java and SOAP (2002) by Robert Englander
- Building Web Services with Java: Making Sense of XML, SOAP, WSDL, and UDDI (2004) by Steve Graham, Doug Davis
- Java Web Services in a Nutshell (2003) by Kim Topley
- RESTful Java Web Services: A pragmatic guide to designing and building RESTful APIs using Java(3rd, 2017) by Bogunuva Mohanram Balachandar
- Professional Java for Web Applications (2014) by Nicholas S. Williams 
- Jakarta Application Development: Develop Enterprise applications using the latest versions of CDI, Jakarta RESTful Web Services, Jakarta JSON Binding, Jakarta Persistence, Security, and more (2nd, 2024) by David R. Heffelfinger
- Building RESTful Web Services with Java EE 8: Create modern RESTful web services with the Java EE 8 API (2018) by Mario-Leander Reimer
- Professional Java Web Services (2001) by Scott Cable, Ben Galbraith
- Web Services Essentials (2002) by Ethan Cerami
- Programming Web Services with SOAP: Building Distributed Applications (2009) by Doug Tidwell, James Snell

JAX-RS

- Pro RESTful APIs: Design, Build and Integrate with REST, JSON, XML and JAX-RS (2017) by Sanjay Patni
- RESTful Java with JAX-RS 2.0: Designing and Developing Distributed Web Services (2013) by Bill Burke
- Java EE 8 Application Development: Develop Enterprise applications using the latest versions of CDI, JAX-RS, JSON-B, JPA, Security, and more (2017) by David R. Heffelfinger

<br>

<h2><a name="rpc_t" href="#rpc_c">Remote Procedure Call (RPC)</a></h2>

<br>

### gRPC

![GitHub Repo stars](https://img.shields.io/github/stars/grpc/grpc)  ![GitHub last commit](https://img.shields.io/github/last-commit/grpc/grpc)  ![GitHub contributors](https://img.shields.io/github/contributors/grpc/grpc)  ![GitHub Created At](https://img.shields.io/github/created-at/grpc/grpc)

> A high performance, open source universal RPC framework.

- [gRPC](https://grpc.io/)
- gRPC: Up and Running: Building Cloud Native Applications with Go and Java for Docker and Kubernetes (2020) by Kasun Indrasiri and Danesh Kuruppu [3.61, 113]
- gRPC Microservices in Go (2023) by Hüseyin Babal [3.95, 21]
- Modern API Development with Spring 6 and Spring Boot 3: Design scalable, viable, and reactive APIs with REST, gRPC, and GraphQL using Java 17 and Spring Boot 3 (2nd, 2023) by Sourabh Sharma

Some more

- gRPC Go for Professionals: Implement, test, and deploy production-grade microservices (2023) by Clément Jean (Packt Publisher)
- Modern API Design with gRPC: Efficient Solutions to Design Modern APIs with gRPC Using Golang for Scalable Distributed Systems (2024) by Hitesh Pattanayak
- Practical gRPC (2018) by Joshua Humphries 

### Apache Thrift

/əˈpatʃi - θrɪft/

![GitHub Repo stars](https://img.shields.io/github/stars/apache/thrift)  ![GitHub last commit](https://img.shields.io/github/last-commit/apache/thrift)  ![GitHub contributors](https://img.shields.io/github/contributors/apache/thrift)  ![GitHub Created At](https://img.shields.io/github/created-at/apache/thrift)

> A lightweight, language-independent software stack for point-to-point RPC implementation.

- [Apache Thrift Documentation](https://thrift.apache.org/docs/)
- Learning Apache Thrift (2015) by Krzysztof Rakowski
- Programmer's Guide to Apache Thrift (2019) by William Abernethy

### Apache Dubbo

/əˈpatʃi - ˈdʌbəʊ/

![GitHub Repo stars](https://img.shields.io/github/stars/apache/dubbo)  ![GitHub last commit](https://img.shields.io/github/last-commit/apache/dubbo)  ![GitHub contributors](https://img.shields.io/github/contributors/apache/dubbo)  ![GitHub Created At](https://img.shields.io/github/created-at/apache/dubbo)

>Dubbo是阿里巴巴开发的一个开源的高性能、高可用、可扩展的分布式RPC调用框架，致力于提供高性能和透明化的 RPC 远程调用服务解决方案。

>简单来说它就是一个RPC框架，但是和普通的RPC框架不同的是，它提供了服务治理功能，比如服务注册、监控、路由、容错等。

- [Apache Dubbo](https://dubbo.apache.org/en/) - A Cloud-Native Microservice Framework.
- [Dubbo 文档](https://dubbo.apache.org/zh-cn/overview/home/)
- 深入理解Apache Dubbo与实战 (2019) by 诣极, 林琳
- 深度剖析Apache Dubbo核心技术内幕 (2019) by 翟陆续（加多）

### Motan

/ˈmoʊtən/

>一套高性能、易于使用的分布式远程服务调用(RPC)框架。

- [weibocom/motan](https://github.com/weibocom/motan). A cross-language remote procedure call(RPC) framework for rapid development of high performance distributed services.
- [Motan Wiki](https://github.com/weibocom/motan/wiki/zh_overview)

### Protobuf

>Protocol Buffers - Google's data interchange format

- [Protobuf](https://protobuf.dev/). Protocol Buffers are language-neutral, platform-neutral extensible mechanisms for serializing structured data.
- Protocol Buffers Handbook: Getting deeper into Protobuf internals and its usage (2024) by Clément Jean

<br>

<h2><a name="mq_t" href="#mq_c">Message Queues</a></h2>

<br>

### Message Protocol and Specification

**Java Message Service (JMS)**

>An API specification in Java for messaging. Part of Jakarta EE (formerly Java EE). Not an implementation—it's a standard for messaging in Java applications. Requires a JMS-compliant provider (e.g., ActiveMQ, Artemis, IBM MQ).

>A Java API specification for sending messages between two or more clients. Created by Sun Microsystems (now Jakarta EE). Best for Java-based enterprise applications.

<details><summary>When use JMS</summary>

- You're in a Java-only environment. 
- You're building applications on Jakarta EE or Spring that need container-managed transactions.
- You use JMS-compliant brokers (ActiveMQ, Artemis).

</details>

- Java Message Service by Mark Richards, Richard Monson-Haefel and David A. Chappell

**AMQP**

>An open wire-level messaging protocol that defines how messages are formatted, routed, delivered, etc. Best for: Polyglot systems needing interoperability and flexible routing.


**STOMP**

>A very simple, text-based protocol for messaging over WebSocket or TCP. Best for Lightweight clients, WebSocket messaging, browser-based apps.

**MQTT**

>A lightweight messaging protocol designed for low-bandwidth, high-latency, or unreliable networks. Created by IBM. Best for IoT, embedded systems, mobile messaging.

**OpenWire**

>A binary protocol developed by Apache ActiveMQ for optimized message transmission. Best for Internal use with ActiveMQ where performance is key.


**OpenMessaging**

>A vendor-neutral messaging standard initiative (open spec). Started by Alibaba, Tencent, and others under the Linux Foundation. Best for Cloud-native or streaming-first systems looking for vendor-agnostic messaging APIs.

### Message Queue

<details>
    <summary>消息队列选型</summary>

性能优先选 Kafka，有事务需求选 RabbitMQ。除非用 Spring Alibaba 那一套，否则不会考虑 rocketmq，http 协议才有多语言 sdk，生态差太多了。

事务型：RabbitMQ，流量型：Kafka。

业务量不大，只是要一个稳定不出问题的消息队列。RabbitMQ 最少这个选择不会错。因为太成熟了。

只用主流和支持多语言的。低吞吐，部署简单的，用 RabbitMQ。大流量大吞吐的，用 kafka。

不建议 redis 业务稍微上来点就要重构。

Kafka vs. RabbitMQ vs. Pulsar

- Kafka: The Streaming Heavyweight
- RabbitMQ: The Agile Middleweight
- Pulsar: The Rising Lightweight Star

</details>

Message queue summary table

| Feature             | Apache Kafka                              | RabbitMQ                            | ActiveMQ                                     |
| ------------------- | ----------------------------------------- | ----------------------------------- | -------------------------------------------- |
| Delivery Model      | Pull only                                 | Push (hybrid pull with prefetch)    | Push                                         |
| Primary Use Case    | Event streaming, logs, analytics          | General messaging, microservices    | Java EE integration, legacy systems          |
| Retention           | Long-term (logs), replayable              | Queue-based (until ack or TTL)      | Queue/topic-based, typically short-term      |
| Protocol            | Kafka’s own binary protocol               | AMQP 0-9-1, MQTT, STOMP, etc.       | OpenWire, JMS, AMQP, MQTT, STOMP             |
| Consumer Tracking   | Client tracks offset                      | Broker tracks delivery & ack        | Broker tracks delivery & ack                 |
| Durability          | Log-based, disk-backed                    | Configurable queues, durable queues | Persistent messages and durable queues       |
| Language Support    | Java-native (with client APIs for others) | Polyglot (AMQP-based)               | Java-centric (JMS API)                       |
| Built-in Clustering | Yes (via brokers + Zookeeper or KRaft)    | Yes (node clustering, HA queues)    | Yes (depends on version - Artemis is better) |

- Kafka: Best for event streaming, large-scale logs, data pipelines.
- RabbitMQ: Best for decoupling services, work queues, polyglot environments.
- ActiveMQ: Best for JMS-based enterprise apps, legacy Java systems.

### RabbitMQ

- [RabbitMQ](https://www.rabbitmq.com/)
- [RabbitMQ Tutorials - Doc](https://www.rabbitmq.com/tutorials)
- [RabbitMQ Documentation](https://www.rabbitmq.com/docs)
- **RabbitMQ Essentials**: Build distributed and scalable applications with message queuing using RabbitMQ (2nd, 2020) by Lovisa Johansson and David Dossot [4.09, 23]
- **RabbitMQ in Action: Distributed Messaging for Everyone** (2012) by Alvaro Videla, Jason J. W. Williams [3.88, 165]
- **RabbitMQ in Depth** (2017) by Gavin M. Roy [3.94, 70]

Some more

- RabbitMQ Cookbook: Over 70 Practical Recipes to Help You Develop Messaging Applications Using Rabbitmq With the Help of Plenty of Real-life Examples (2013) by Boschi Sigismondo, Gabriele Santomaggio [3.72, 18]
- Ultimate Microservices with RabbitMQ: Master Microservices Architecture and RabbitMQ Integration to Build Scalable, Resilient Systems, and to Drive Innovation ... in Software Development (2024) by Peter Morlion
- Advanced RabbitMQ: Comprehensive Messaging and Integration Frameworks (2024) by Adam Jones
- Learning RabbitMQ (2015) by Martin Toshev
### Apache Kafka

/əˈpatʃi - ˈkaf.ka/

- Apache Kafka documentation. [DOC](https://kafka.apache.org/)
- Kafka: a Distributed Messaging System for Log Processing [PDF](https://notes.stephenholiday.com/Kafka.pdf)
- [Kafka Books and Papers](https://kafka.apache.org/books-and-papers)
- **Kafka: The Definitive Guide: Real-Time Data and Stream Processing at Scale** (2nd, 2021) by Neha Narkhede, Gwen Shapira, Todd Palino [4.2, 712]
- I Heart Logs: Event Data, Stream Processing, and Data Integration (2014) by Jay Kreps [3.85, 384]
- Effective Kafka: A Hands-on Guide to Building Robust and Scalable Event-Driven Applications with Code Examples in Java (2020) by Emil Koutanov [4.40, 42]
- Kafka in Action (2022) by Dylan Scott [3.74, 39]
- Apache Kafka in Action: From basics to production (2025) by Anatoly Zelenin, Alexander Kropp
- Apache Kafka Quick Start Guide: Leverage Apache Kafka 2.0 to simplify real-time data processing for distributed applications (2018) by Raúl Estrada
- Kafka Troubleshooting in Production: Stabilizing Kafka Clusters in the Cloud and On-premises (2023) by Elad Eldor

Some more

- Kafka Connect: Build and Run Data Pipelines (2023) by Mickael Maison, Kate Stanley
- Event Streams in Action: Real-time event systems with Kafka and Kinesis (2019) by Alexander Dean, Valentin Crettaz
- Streaming Data: Understanding the real-time pipeline (2017) by Andrew Psaltis
- Streaming Systems: The What, Where, When, and How of Large-Scale Data Processing (2018) by Tyler Akidau, Slava Chernyak, Reuven Lax

Apache Kafka Stream

- Kafka Streams in Action: : Event-driven applications and microservices (2nd, 2024) by Bill Bejeck [4.05, 122]
- Mastering Kafka Streams and ksqlDB: Building Real-Time Data Systems by Example (2021) by Mitch Seymour [4.16, 38]

### Apache ActiveMQ


- [Apache ActiveMQ](http://activemq.apache.org/)

### Apache Pulsar

/əˈpatʃi - ˈpʌlsɑː/

- Mastering Apache Pulsar: Cloud Native Event Streaming at Scale (2022) by Jowanza Joseph
- Apache Pulsar in Action (2021) by David Kjerrumgaard
- Cloud-Native Microservices with Apache Pulsar: Build Distributed Messaging Microservices (2021) by Rahul Sharma and Mohammad Atyab
- Stream Processing with Apache Pulsar: Building real-time scalable data streaming applications (2021) by Theophilus Siameh

### Apache RocketMQ


- [Apache RocketMQ](https://github.com/apache/rocketmq)
- Apache RocketMQ 进阶之路 (2024) by 林俊杰
- RocketMQ分布式消息中间件：核心原理与最佳实践 (2020) by 李伟
- RocketMQ技术内幕：RocketMQ架构设计与实现原理 (2018) by 丁威, 周继锋
- RocketMQ实战 (2020) by 丁威 梁勇

### More Message Queues

Amazon Simple Queue System (SQS)

Google Cloud Pub/Sub

Microsoft Azure Service Bus

IBM MQ

Red Hat AMQ

<br>

<h2><a name="infosec_t" href="#infosec_c">Information Security</a></h2>

<br>

Reference [Information Security Resources](directions/information-security-resources.md)

<br>

<h2><a name="distsys_t" href="#distsys_c">Distributed Systems</a></h2>
<br>

### Distributed Systems

/dɪˈstrɪbjuːtɪd - ˈsɪs.təms/

Must Read


- **Distributed Systems** (4th, 2023) by Andrew S. Tanenbaum, Maarten van Steen. A good overview of distributed systems that goes to enough depth to spark interest. Might be too much for beginners, but a good intermediate level reference.
- **Designing Data-Intensive Applications** (2017) by Martin Kleppmann
- **Distributed Systems For Fun and Profit** by Mikito Takada. Great intro book to distributed systems theory, with plenty of references to learn more once you're done.
- Think Distributed Systems (2025) by Dominik Tornow
- Understanding Distributed Systems: What every developer should know about large distributed applications (2nd, 2022) by Roberto Vitillo
- Designing Distributed Systems: Patterns and Paradigms for Scalable, Reliable Services by Brendan Burns. Patterns and Paradigms for container architecture. Useful but shallow.
- Patterns of Distributed Systems by Unmesh Joshi [HTML](https://martinfowler.com/articles/patterns-of-distributed-systems/)
- 从PAXOS到ZOOKEEPER分布式一致性原理与实践 by 倪超

Some More


- Distributed Systems: Concepts and Design by George Coulouris, Jean Dollimore, Tim Kindberg, Gordon Blair
- Distributed Algorithms by Nancy A. Lynch
- Principles of Transaction Processing by Philip A. Bernstein
- Introduction to Distributed Algorithms by Gerard Tel
- Programming Distributed Computing Systems: A Foundational Approach by Carlos A. Varela
- Distributed Computing: Principles, Algorithms, and Systems by Ajay D. Kshemkalyani
- Design and Analysis of Distributed Algorithms by Nicola Santoro
- Introduction to Reliable Distributed Programming by Rachid Guerraoui
- Elements of Distributed Computing by Vijay K. Garg
- Fault-Tolerant Message-Passing Distributed Systems: An Algorithmic Approach by Michel Raynal
- Distributed Algorithms for Message-Passing Systems by Michel Raynal
- Introduction to Reliable and Secure Distributed Programming by Christian Cachin
- Replication: Theory and Practice by Bernadette Charron-Bost

Papers of Distributed Systems

- [Distributed Systems Reading List](https://dancres.github.io/Pages/)
- [Distributed Systems Reading List - CS Rutgers](https://www.cs.rutgers.edu/~pxk/417/readinglist.html)

Courses

- [Distributed Systems lecture series](https://www.youtube.com/playlist?list=PLeKd45zvjcDFUEv_ohr_HdUFe97RItdiB) by Martin Kleppmann
- [MIT 6.824: Distributed Systems](https://www.youtube.com/playlist?list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB)

More Distributed Systems

- [awesome-distributed-systems - GitHub](https://github.com/theanalyst/awesome-distributed-systems)

### Distributed Data Storage

- **Database Internals: A deep-dive into how distributed data systems work** (2019) by Alex Petrov
- Principles of Distributed Database Systems by M. Tamer Ozsu
- Distributed Databases: Principles and Systems by Stefano Ceri, G. Pelagatti
- Distributed Database Systems by Chhanda Ray

For HBase

- HBase in Action by Nick Dimiduk, Amandeep Khurana

### Microservices

- **Building Microservices: Designing Fine-Grained Systems** (2nd, 2021) by Sam Newman
- **Microservices Patterns: With Examples in Java** (2018) by Chris Richardson
- **Microservice Architecture: Aligning Principles, Practices, and Culture** (2016) by Irakli Nadareishvili, Matt McLarty, and Michael Amundsen
- **The Tao of Microservices** (2017) by Richard Rodger
- **Monolith to Microservices: Evolutionary Patterns to Transform Your Monolith** (2019) by Sam Newman
- **Spring Microservices in Action** (2nd, 2021) by John Carnell
- **Production-Ready Microservices: Building Standardized Systems Across an Engineering Organization** (2016) by Susan Fowler and Susan J. Fowler
- **Cloud Native Java: Designing Resilient Systems with Spring Boot, Spring Cloud, and Cloud Foundry** (2017) by Josh Long and Kenny Bastani
- Microservices for the Enterprise: Designing, Developing, and Deploying by Kasun Indrasiri, Prabath Siriwardena
- **大型网站技术架构：核心原理与案例分析** by 李智慧
- **大规模Web服务开发技术** by 伊藤直也, 田中慎司
- 大型网站系统与Java中间件实践 by 曾宪杰
- 分布式Java应用：基础与实践 by 林昊
- 分布式服务框架：原理与实践 by 李林锋

Microservices Architecture Design 

- Reference [CS software development and engineering - Architecture Design](_cs-software-development-and-engineering.md#archdes_t)

Middleware - Microservices Collaboration

- [Apache Dubbo](https://dubbo.apache.org/en-us/)
- [Apache ZooKeeper](https://zookeeper.apache.org/)
- [Spring Cloud](https://spring.io/projects/spring-cloud)

Middleware - Microservices Communication (RPC/Message/HTTP)



Middleware - Database Cluster / Big Data

- MySQL master-slave replication
- Data Sharding
	- [Mycat](http://www.mycat.org.cn/)
	- [Sharding-JDBC](https://shardingsphere.apache.org/document/4.1.1/en/manual/sharding-jdbc/)
	- [alibaba/cobar](https://github.com/alibaba/cobar)
	- [Citus](https://www.citusdata.com/) (for PostgreSQL)
	- [proxysql](https://github.com/sysown/proxysql)
- Databases
	- PostgreSQL
	- Oracle
- Analytical Databases / Data Warehouse / OLAP
	- [Apache Doris](https://doris.apache.org/)
	- [StarRocks](https://www.starrocks.io/)
	- [ClickHouse](https://clickhouse.com/)
	- [Greenplum](https://greenplum.org/) (Based on PostgreSQL)
- OLAP+OLTP
	- [TiDB](https://pingcap.com/en/) 社区版（加 TiFlash，HTAP）
	- [OceanBase](https://www.oceanbase.com/) 企业版

Middleware - Authentication and Authorization

Keycloak

>- Single-Sign On: Login once to multiple applications.
>- Standard Protocols: OpenID Connect, OAuth 2.0 and SAML 2.0.
>- Centralized Management: For admins and users

- [Keycloak Getting Started](https://www.keycloak.org/guides)
- Keycloak - Identity and Access Management for Modern Applications: Harness the power of Keycloak, OpenID Connect, and OAuth 2.0 to secure applications (2nd, 2023) by Stian Thorgersen and Pedro Igor Silva

Logto

- [Logto](https://github.com/logto-io/logto). Authentication and authorization infrastructure for SaaS and AI apps, built on OIDC and OAuth 2.1 with multi-tenancy, SSO, and RBAC.

<br>

<h2><a name="cloudcpt_t" href="#cloudcpt_c">Cloud Computing and Serverless</a></h2>

<br>

General

- The Self-Taught Cloud Computing Engineer: A comprehensive professional study guide to AWS, Azure, and GCP (2023) by Dr. Logan Song
- Data Pipelines with Apache Airflow (2021) by Bas P. Harenslak, Julian Rutger de Ruiter
- Architecting Modern Data Platforms: A Guide to Enterprise Hadoop at Scale (2019) by Jan Kunigk, Ian Buss, Paul Wilkinson, Lars George

AWS

- AWS Cloud Projects: Strengthen your AWS skills through practical projects, from websites to advanced AI applications (2024) by Ivo Pinto, Pedro Santos
- AWS for Solutions Architects: The definitive guide to AWS Solutions Architecture for migrating to, building, scaling, and succeeding in the cloud (2nd, 2023) by Saurabh Shrivastava, Neelanjali Srivastav, Alberto Artasanchez 
- AWS Security Cookbook: Practical solutions for securing AWS cloud infrastructure with essential services and best practices (2nd, 2024) by Heartin Kanikathottu
- AWS Cookbook: Recipes for Success on AWS (2022) by John Culkin, Mike Zazon
- Data Science on AWS: Implementing End-to-End, Continuous AI and Machine Learning Pipelines (2021) by Chris Fregly, Antje Barth
- Generative AI on AWS: Building Context-Aware Multimodal Reasoning Applications (2023) by Chris Fregly, Antje Barth, Shelbee Eigenbrode
- AWS for System Administrators: Build, automate, and operate scalable cloud infrastructure on AWS (2nd, 2025) by Marcel Neidinger, Prashant Lakhera
- System Design on AWS: Building and Scaling Enterprise Solutions (2025) by Jayanth Kumar, Mandeep Singh 
- Engineering Resilient Systems on AWS: Design, Build, and Test for Resilience 1st Edition (2024) by Kevin Schwarz, Jennifer Moran, Nate Bachmeier

Google Cloud

- Visualizing Google Cloud: 101 Illustrated References for Cloud Engineers and Architects (2022) by Priyanka Vergadia
- Google Cloud Cookbook: Practical Solutions for Building and Deploying Cloud Services (2021) by Rui Santos Costa, Drew Hodun
- Data Science on the Google Cloud Platform: Implementing End-to-End Real-Time Data Pipelines: From Ingest to Machine Learning (2nd, 2022) by Valliappa Lakshmanan
- Building Serverless Applications with Google Cloud Run: A Real-World Guide to Building Production-Ready Services (2021) by Wietse Venema

Google Cloud CLI

- [Google Cloud CLI documentation](https://cloud.google.com/sdk/docs)

Microsoft Azure

- Azure Cloud Projects: Learn Microsoft Azure through hands-on, real-world projects (2025) by Hamid Sadeghpour Saleh
- Learning Microsoft Azure: Cloud Computing and Development Fundamentals (2023) by Jonah Carrio Andersson
- Cloud Native Infrastructure with Azure: Building and Managing Cloud Native Applications (2022) by Nishant Singh, Michael Kehoe 
- Azure Cookbook: Recipes to Create and Maintain Cloud Solutions in Azure (2023) by Reza Salehi
- Azure OpenAI Service for Cloud Native Applications: Designing, Planning, and Implementing Generative AI Solutions (2024) by Adrián González Sánchez
- Azure AI Services at Scale for Cloud, Mobile, and Edge: Building Intelligent Apps with Azure Cognitive Services and Machine Learning (2022) by Simon Bisson, Mary Branscombe, Chris Hoder, Anand Raman
- Azure for Developers: Implement rich Azure PaaS ecosystems using containers, serverless services, and storage solutions (2nd, 2022) by Kamil Mrzygłód

阿里云

- 阿里云云原生架构实践 (2022) by 阿里集团
- 阿里云运维架构实践秘籍 (2020) by 驻云科技-乔锐杰
- 阿里云数字新基建系列
	- 云数据库架构 (2021) by 朱明
	- 混合云架构 (2021) by 解国红, 刘怿平, 陈煜文, 罗寒曦
	- CDN技术架构 (2022) by 阿里云CDN团队
	- 云服务器运维之Windows篇 by 杨洋
	- 云原生操作系统Kubernetes (2020) by 罗建龙, 刘中巍, 张城, 黄珂, 苏夏, 高相林, 盛训杰
- 云存储：释放数据无限价值 (2022) by 阿里云基础产品委员会
- 企业数字化基石 : 阿里巴巴云计算基础设施实践 (2020) by 高山渊, 蔡德忠, 赵晓雪, 刘礼寅, 刘水旺, 陈义全, 徐波

<br>

<h2><a name="datamining_t" href="#datamining_c">Big Data and Data Mining</a></h2>

<br>

### Introduction to Big Data and Information

- The Signal and the Noise: Why So Many Predictions Fail—But Some Don't by Nate Silver
- The Tipping Point: How Little Things Can Make a Big Difference by Malcolm Gladwell
- Moneyball: The Art of Winning an Unfair Game by Michael Lewis
- Invisible Women: Data Bias in a World Designed for Men by Caroline Criado Perez
- The Wisdom of Crowds: Why the Many Are Smarter Than the Few and How Collective Wisdom Shapes Business, Economies, Societies and Nations by James Surowiecki
- Everybody Lies: Big Data, New Data, and What the Internet Can Tell Us About Who We Really Are by Seth Stephens-Davidowitz 
- Superforecasting: The Art and Science of Prediction by Philip E. Tetlock
- The Misbehavior of Markets: A Fractal View of Financial Turbulence by Benoît B. Mandelbrot
- Quiet: The Power of Introverts in a World That Can't Stop Talking by Susan Cain
- Big Data: A Revolution That Will Transform How We Live, Work, and Think by Viktor Mayer-Schönberger
- Weapons of Math Destruction: How Big Data Increases Inequality and Threatens Democracy by Cathy O'Neil
- The Lady Tasting Tea: How Statistics Revolutionized Science in the Twentieth Century by David Salsburg
- A Human's Guide to Machine Intelligence: How Algorithms Are Shaping Our Lives and How We Can Stay in Control by Kartik Hosanagar
- Freakonomics: A Rogue Economist Explores the Hidden Side of Everything by Steven D. Levitt
- Thinking, Fast and Slow by Daniel Kahneman
- Predictably Irrational: The Hidden Forces That Shape Our Decisions by Dan Ariely
- Dataclysm: Who We Are by Christian Rudder
- Fooled by Randomness: The Hidden Role of Chance in Life and in the Markets by Nassim Nicholas Taleb
- The Long Tail: Why the Future of Business is Selling Less of More by Chris Anderson
- The Creative Destruction of Medicine: How the Digital Revolution Will Create Better Health Care by Eric J. Topol
- Bringing Down the House: The Inside Story of Six M.I.T. Students Who Took Vegas for Millions by Ben Mezrich 

### Introduction to Data Science

- Data Science from Scratch by Joel Grus
- Machine Learning: An Introduction Math Guide for Beginners to Understand Data Science Through the Business Applications by Samuel Hack
- Doing Data Science: Straight Talk from the Frontline by Cathy O'Neil and Rachel Schutt
- Data Science for Business: What you need to know about data mining and data-analytic thinking by Foster Provost
- How to Lie with Statistics by Darrell Huff
- Algorithms to Live By: What Computers Can Teach Us About Solving Human Problems by Brian Christian
- The Ethical Algorithm: The Science of Socially Aware Algorithm Design by Michael Kearns
- Think Like a Data Scientist: Tackle the data science process step-by-step by Brian Godsey
- Hello World: Being Human in the Age of Algorithms by Hannah Fry
- Data Smart: Using Data Science to Transform Information into Insight by John W. Foreman
- Naked Statistics: Stripping the Dread from the Data by Charles Wheelan

### Introduction to Data Mining 

/ˈdeɪtə - ˈmʌɪnɪŋ/

> It is the process of extracting a specific pattern from large datasets. It's based on mathematical and scientific methods to identify patterns or trends. it's generally used for the process of extracting, cleaning, learning and predicting from data.

- Introduction to Data Mining by Vipin Kumar
- Introduction to Data Mining by Pang-Ning Tan
- Data Mining: Concepts and Techniques by Jiawei Han
- Mining of Massive Datasets by Anand Rajaraman and Jeffrey Ullman
- Data Mining and Analysis: Fundamental Concepts and Algorithms by Mohammed J. Zaki and Wagner Meira
- Data Mining with Rattle and R: The Art of Excavating Data for Knowledge Discovery by Graham J. Williams
- Bayesian Methods for Hackers: Probabilistic Programming and Bayesian Inference by Cameron Davidson-Pilon
- Data Mining with R: Learning with Case Studies by Luis Torgo
- Data Mining Techniques: For Marketing, Sales, and Customer Relationship Management by Michael J. A. Berry, Gordon S. Linoff
- Mining the Social Web: Data Mining Facebook, Twitter, LinkedIn, Instagram, GitHub, and More by Matthew A. Russell and Mikhail Klassen
- Data Mining: Practical Machine Learning Tools and Techniques by Ian H. Witten

### Statistical Learning

- The Elements of Statistical Learning by Jerome H. Friedman, Robert Tibshirani, and Trevor Hastie
- An Introduction to Statistical Learning: With Applications in R by Gareth James, Trevor Hastie, Robert Tibshirani, Daniela Witten
- Advanced R by Hadley Wickham 
- An Introduction to Applied Multivariate Analysis with R by Brian S. Everitt
- R in Action by Robert Kabacoff
- R for Everyone: Advanced Analytics and Graphics by Jared P. Lander
- The R Book by Michael J. Crawley
- R for Data Science: Import, Tidy, Transform, Visualize, and Model Data by Hadley Wickham
- Statistics in Plain English by Timothy C. Urdan
- What is a P-Value Anyway? 34 Stories to Help You Actually Understand Statistics by Andrew J. Vickers
- All of Statistics: A Concise Course in Statistical Inference by Larry Wasserman
- Regression Modeling Strategies: With Applications to Linear Models, Logistic Regression, and Survival Analysis by Frank E. Harrell Jr.

### Data Engineering

#### Data Engineering

- Data Engineering Design Patterns: Recipes for Solving the Most Common Data Engineering Problems (2025) by Bartosz Konieczny
- Fundamentals of Data Engineering: Plan and Build Robust Data Systems by Joe Reis, Matt Housley
- The Self-Service Data Roadmap: Democratize Data and Reduce Time to Insight (2002) by Sandeep Uttamchandani
- Designing Cloud Data Platforms by Danil Zburivsky, Lynda Partner
- Big Data: Principles and best practices of scalable realtime data systems (2015) by Nathan Marz, James Warren 
- Deciphering Data Architectures: Choosing Between a Modern Data Warehouse, Data Fabric, Data Lakehouse, and Data Mesh (2024) by James Serra 
- Data Engineering with Apache Spark, Delta Lake, and Lakehouse: Create scalable pipelines that ingest, curate, and aggregate complex data in a timely and secure way (2021) by Manoj Kukreja

#### Data Ingestion & Integration

>Collect and move raw data from various sources (databases, APIs, IoT, logs) into the data platform.

- Apache Kafka: Distributed streaming platform for real-time data pipelines.
- Apache NiFi: Drag-and-drop data flow automation and ETL tool.
- AWS Kinesis: Amazon’s managed real-time data streaming service.
- Apache Flume: Collects, aggregates, and transports log data.
- Fivetran: Cloud-based ETL platform for automated data ingestion.
- Airbyte: Open-source ELT tool connecting APIs, databases, and warehouses.
- Debezium: Captures database changes (CDC) and streams them via Kafka.

#### Data Storage & Warehousing

>Store data in raw or structured formats for later analysis.

##### Data Warehousing

- Agile Data Warehouse Design: Collaborative Dimensional Modeling, from Whiteboard to Star Schema (2011) by Lawrence Corr, Jim Stagnitto
- The Data Warehouse Toolkit: The Definitive Guide to Dimensional Modeling (3rd, 2013) by Ralph Kimball, Margy Ross 

##### <img src="/assets/icon/advanced-domains/Hadoop.svg" width="24px"/>Hadoop Ecosystem

Hadoop

/həˈduːp/

- Hadoop: The Definitive Guide by Tom White, Doug Cutting 
- Hadoop in Action by Chuck Lam
- Hadoop Operations by Eric Sammer
- Hadoop in Practice by Alex Holmes
- Professional Hadoop Solutions by Alexey Yakubovich, Boris Lublinsky, and Kevin T. Smith
- Data Analytics with Hadoop: An Introduction for Data Scientists by Benjamin Bengfort and Jenny Kim
- Expert Hadoop Administration: Managing, Tuning, and Securing Spark, YARN, and HDFS by Sam R. Alapati
- Hadoop Application Architectures: Designing Real-World Big Data Applications by Gwen Shapira, Ted Malaska Jonathan S Mark Grover
- Hadoop Security: Protecting Your Big Data Platform by Ben Spivey and Joey Echeverria
- Architecting Modern Data Platforms: A Guide to Enterprise Hadoop at Scale by Jan Kunigk, Ian Buss, Paul Wilkinson, Lars George

Hadoop HDFS

>Distributed file system for big data storage.

MapReduce

>A programming model and framework for processing large datasets in parallel across a cluster of computers, famously used with the Hadoop ecosystem. 

- MapReduce Design Patterns: Building Effective Algorithms and Analytics for Hadoop and Other Systems by Adam Shook and Donald Miner

Apache Hive

>SQL-like query layer built on top of Hadoop.

- Programming Hive by Dean Wampler, Edward Capriolo, and Jason Rutherglen

Apache HBase

>NoSQL database on HDFS

>NoSQL database optimized for random, real-time read/write on big data.

- HBase: The Definitive Guide by Lars George

Pig

>Scripting for Hadoop transformations

- Programming Pig by Alan Gates

##### Modern Warehousing

Snowflake

>Cloud data warehouse with elastic compute and storage.

- Data Modeling with Snowflake: A practical guide to accelerating Snowflake development using universal modeling techniques (2nd, 2025) by Serge Gershkovich
- Snowflake: The Definitive Guide: Architecting, Designing, and Deploying on the Snowflake Data Cloud (2022) by Joyce Kay Avila
- Snowflake Data Engineering (2025) by Maja Ferle
- Jumpstart Snowflake: A Step-by-Step Guide to Modern Cloud Analytics (2nd, 2025) by Dmitry Anoshin, Dmitry Foshin, Donna Strok 
- Learning Snowflake SQL and Scripting: Generate, Retrieve, and Automate Snowflake Data (2023) by Alan Beaulieu
- Snowflake Cookbook: Techniques for building modern cloud data warehousing solutions (2021) by Hamid Mahmood Qureshi, Hammad Sharif

Google BigQuery

>Serverless data warehouse with SQL and ML integration.

- Google BigQuery: The Definitive Guide: Data Warehousing, Analytics, and Machine Learning at Scale (2019) by Valliappa Lakshmanan, Jordan Tigani
- Data Exploration and Preparation with BigQuery: A practical guide to cleaning, transforming, and analyzing data for business insights (2023) by Mike Kahn
- Google BigQuery Analytics (2014) by Jordan Tigani, Siddartha Naidu 
- BigQuery for Data Warehousing: Managed Data Analysis in the Google Cloud (2020) by Mark Mucchetti 
- Machine Learning with BigQuery ML: Create, execute, and improve machine learning models in BigQuery using standard SQL queries (2021) by Alessandro Marrandino 
- Learning Google BigQuery: A beginner's guide to mining massive datasets through interactive analysis (2017) by Thirukkumaran Haridass, Eric Brown
- Data Science on the Google Cloud Platform: Implementing End-to-End Real-Time Data Pipelines: From Ingest to Machine Learning (2nd, 2022) by Valliappa Lakshmanan
- Data Engineering with Google Cloud Platform: A guide to leveling up as a data engineer by building a scalable data platform with Google Cloud (2nd, 2024) by Adi Wijaya, António Vilares

Amazon Redshift

>Scalable data warehouse service by AWS.

- Amazon Redshift: The Definitive Guide: Jump-Start Analytics Using Cloud Data Warehousing (2023) by Rajesh Francis, Rajiv Gupta, Milind Oke
- Amazon Redshift Cookbook: Recipes for building modern data warehousing solutions (2nd, 2025) by Shruti Worlikar, Harshida Patel, Anusha Challa
- Data Science on AWS: Implementing End-to-End, Continuous AI and Machine Learning Pipelines (2021) by Chris Fregly, Antje Barth 

Delta Lake

>Open-source data lake format ensuring reliability (ACID) on big data.

- Delta Lake: The Definitive Guide: Modern Data Lakehouse Architectures with Data Lakes (2024) by Denny Lee, Tristen Wentling, Scott Haines, Prashanth Babu
- Practical Lakehouse Architecture: Designing and Implementing Modern Data Platforms at Scale (2024) by Gaurav Ashok Thalpati 
- Delta Lake: Up and Running: Modern Data Lakehouse Architectures with Delta Lake (2023) by Bennie Haelen, Dan Davis
- Building Medallion Architectures: Designing with Delta Lake and Spark (2025) by Piethein Strengholt

Apache Iceberg

>Modern table format for large-scale data lakes (schema evolution + time travel).

- Apache Iceberg: The Definitive Guide: Data Lakehouse Functionality, Performance, and Scalability on the Data Lake (2024) by Tomer Shiran, Jason Hughes, Alex Merced

Parquet / ORC

>Columnar storage formats for efficient analytics.


#### Data Processing & Transformation

>Clean, transform, and model raw data into analysis-ready form.

Data Processing

- Data Pipelines Pocket Reference: Moving and Processing Data for Analytics (2021) by James Densmore
- Streaming Systems: The What, Where, When, and How of Large-Scale Data Processing (2018) by Tyler Akidau, Slava Chernyak, Reuven Lax 

Apache Spark

>Unified engine for large-scale data processing (batch + streaming).

- Learning Spark: Lightning-Fast Big Data Analysis by Holden Karau, Andy Konwinski, Patrick Wendell, Matei Zaharia
- Spark: The Definitive Guide: Big Data Processing Made Simple by Bill Chambers. Matei Zaharia
- Learning Spark by Mark Hamstra
- Stream Processing with Apache Spark: Mastering Structured Streaming and Spark Streaming (2019) by Gerard Maas, Francois Garillot
- Data Algorithms with Spark: Recipes and Design Patterns for Scaling Up using PySpark (2022) by Mahmoud Parsian 
- High Performance Spark: Best Practices for Scaling and Optimizing Apache Spark (2nd, 2026) by Holden Karau, Adi Polak, Rachel Warren 
- Apache Spark for Machine Learning: Build and deploy high-performance big data AI solutions for large-scale clusters (2024) by Deepak Gowda 
- Modern Data Engineering with Apache Spark: A Hands-On Guide for Building Mission-Critical Streaming Applications (2022) by Scott Haines
- Spark in Action, Second Edition: Covers Apache Spark 3 with Examples in Java, Python, and Scala (2nd, 2020) by Jean-Georges Perrin
- Beginning Apache Spark 3: With DataFrame, Spark SQL, Structured Streaming, and Spark Machine Learning Library (2nd, 2021) by Hien Luu

Databricks

>Cloud platform built around Spark for data engineering and ML.

- Databricks Certified Data Engineer Associate Study Guide: In-Depth Guidance and Practice (2025) Derar Alhussein
- Databricks Data Intelligence Platform: Unlocking the GenAI Revolution (2024) by Nikhil Gupta, Jason Yip 
- Data Governance with Unity Catalog on Databricks: Implement Data and AI Governance with Databricks Data Intelligence Platform (2025) by Kiran Sreekumar, Karthik Subbarao 
- Data Engineering with Databricks Cookbook: Build effective data and AI solutions using Apache Spark, Databricks, and Delta Lake (2024) by Pulkit Chadha
- Azure Databricks Cookbook: Accelerate and scale real-time analytics solutions using the Apache Spark-based analytics service (2021) by Phani Raj, Vinod Jaiswal 
- Beginning Apache Spark Using Azure Databricks: Unleashing Large Cluster Analytics in the Cloud (2020) by Robert Ilijason
- Databricks ML in Action: Learn how Databricks supports the entire ML lifecycle end to end from data ingestion to the model deployment (2024) by Stephanie Rivera, Anastasia Prokaieva, Amanda Baker 
- Databricks Certified Associate Developer for Apache Spark Using Python: The ultimate guide to getting certified in Apache Spark using practical examples with Python (2024) by Saba Shah
- Practical Machine Learning on Databricks: Seamlessly transition ML models and MLOps on Databricks (2023) by Debu Sinha

Apache Flink

>Stream-processing framework for real-time analytics.

- Stream Processing with Apache Flink: Fundamentals, Implementation, and Operation of Streaming Applications (2019) by Fabian Hueske, Vasiliki Kalavri 

Apache Beam

>Unified model for batch and stream data processing.

- Building Big Data Pipelines with Apache Beam: Use a single programming model for both batch and stream data processing (2022) by Jan Lukavsky

dbt (Data Build Tool)

>SQL-based transformation and modeling framework.

- Data Engineering with dbt: A practical guide to building a cloud-based, pragmatic, and dependable data platform with SQL (2023) by Roberto Zagni
- Analytics Engineering with SQL and dbt: Building Meaningful Data Models at Scale (2024) by Rui Machado, Hélder Russa 
- Unlocking dbt: Design and Deploy Transformations in Your Cloud Data Warehouse (2023) by Cameron Cyr, Dustin Dorsey

Apache Airflow

>Workflow orchestrator for ETL and data pipelines.

- Apache Airflow Best Practices: A practical guide to orchestrating data workflow with Apache Airflow (2024) by Dylan Intorf, Dylan Storey, Kendrick van Doorn
- Data Pipelines with Apache Airflow (2021) Julian de Ruiter, Bas Harenslak

AWS Glue / Dataflow

>Managed ETL services by AWS / Google Cloud.


### Data Science & Machine Learning

>Analyze data, build and deploy predictive models.

>Discover patterns, build predictive models, and extract insights.

- Python / R: Core programming languages for analytics and ML.
- scikit-learn: Python library for classical machine learning algorithms.
- TensorFlow / PyTorch: Frameworks for deep learning and neural networks.
- MLflow: Open-source platform for managing ML lifecycle (training → deployment).
- H2O.ai: Open-source and enterprise platform for automated machine learning.
- Jupyter Notebooks: Interactive notebook environment for analysis and visualization.
- Databricks ML: Unified environment for big data + machine learning.
- Google Vertex AI / AWS SageMaker: Cloud platforms for developing and deploying ML models.
- RapidMiner / KNIME / Weka: Visual tools for data mining and predictive analytics.

Data analysis

- Data Analysis with Open Source Tools: A Hands-On Guide for Programmers and Data Scientists by Philipp K. Janet
- Multivariate Data Analysis by Joseph F. Hair Jr.
- Bayesian Data Analysis by Andrew Gelman
- Data Analysis Using Regression and Multilevel/Hierarchical Models by Andrew Gelman
- Python for Data Analysis by Wes McKinney

### Data Analytics & BI

>Present insights, dashboards, KPIs for decisions.

Data Analytics

- Web Analytics 2.0: The Art of Online Accountability & Science of Customer Centricity by Avinash Kaushik
- Competing on Analytics: Updated, with a New Introduction: The New Science of Winning by Thomas H. Davenport
- Forecasting: principles and practice by Rob J Hyndman
- Presenting Data Effectively: Communicating Your Findings for Maximum Impact by Stephanie D.H. Evergreen

Data Visualization

- The Visual Display of Quantitative Information by Edward R. Tufte
- The Functional Art: An Introduction to Information Graphics and Visualization by Alberto Cairo
- Visualize This: The FlowingData Guide to Design, Visualization, and Statistics by Nathan Yau
- Beautiful Visualization: Looking at Data through the Eyes of Experts by Julie Steele
- Say It with Charts: The Executive's Guide to Visual Communication by Gene Zelazny
- Bayes Theorem: A Visual Introduction For Beginners by Dan Morris
- Decision Trees and Random Forests: A Visual Introduction For Beginners: A Simple Guide to Machine Learning with Decision Trees by Chris Smith
- The Truthful Art: Data, Charts, and Maps for Communication by Alberto Cairo
- Storytelling with Data: A Data Visualization Guide for Business Professionals (2018) by Cole Nussbaumer Knaflic

Power BI

>Microsoft’s interactive business analytics tool.

- Mastering Microsoft Power BI: Expert techniques to create interactive insights for effective data analytics and business intelligence (2nd, 2022) by Greg Deckler, Brett Powell
- Data Visualization with Microsoft Power BI: How to Design Savvy Dashboards (2024) by Alex Kolokolov, Maxim Zelensky
- Microsoft Power BI For Dummies (2022) by Jack A. Hyman
- Learn Microsoft Power BI: A comprehensive, beginner-friendly guide to real-world business intelligence (3rd, 2025) by Greg Deckler 
- Microsoft Power BI Cookbook: Convert raw data into business insights with updated techniques, use cases, and best practices (3rd, 2024) by Greg Deckler, Brett Powell
- The Definitive Guide to DAX: Business Intelligence for Microsoft Power BI, SQL Server Analysis Services, and Excel (2nd, 2019) by Marco Russo, Alberto Ferrari
- Expert Data Modeling with Power BI: Enrich and optimize your data models to get the best out of Power BI for reporting and business needs (2nd, 2023) by Soheil Bakhshi
- Learn Power BI: a Comprehensive, Step-By-Step Guide for Beginners to Learn Real-World Business Intelligence (2nd, 2023) Greg Deckler
- Microsoft Power BI Quick Start Guide: The ultimate beginner's guide to data modeling, visualization, digital storytelling, and more (3rd, 2022) by Devin Knight, Erin Ostrowsky, Mitchell Pearson 
- Extending Power BI with Python and R: Perform advanced analysis using the power of analytical languages (2nd, 2024) by Luca Zavarella 
- Learning Microsoft Power BI: Transforming Data into Insights (2022) by Jeremey Arnold
- Power BI - Business Intelligence Clinic: Create and Learn (2018) by Roger F. Silva 
- Data Modeling with Microsoft Power BI: Self-Service and Enterprise Data Warehouse with Power BI (2024) by Markus Ehrenmueller-Jensen
- Microsoft Power BI Dashboards Step by Step (2018) by Errin O'Connor
- The Definitive Guide to Power Query (M): Mastering complex data transformation with Power Query (2024) by Gregory Deckler, Rick de Groot, Melissa de Korte
- Power Pivot and Power BI: The Excel User's Guide to DAX, Power Query, Power BI & Power Pivot in Excel 2010-2016 (2nd, 2021) by Rob Collie, Avichal Singh
- Introducing Microsoft Power BI (2016) by Alberto Ferrari, Marco Russo 
- Expert Data Modeling with Power BI: Get the best out of Power BI by building optimized data models for reporting and business needs (2021) by Soheil Bakhshi 
- The Future of Finance with ChatGPT and Power BI: Transform your trading, investing, and financial reporting with ChatGPT and Power BI (2023) by James Bryant, Aloke Mukherjee
- Microsoft Power BI Quick Start Guide: Bring your data to life through data modeling, visualization, digital storytelling, and more (2nd, 2020) by Devin Knight, Mitchell Pearson, Bradley Schacht 
- Microsoft Power BI Cookbook: Gain expertise in Power BI with over 90 hands-on recipes, tips, and use cases (2nd, 2021) by Greg Deckler, Brett Powell 

Tableau

>Visual analytics platform with drag-and-drop dashboards.

- Tableau For Dummies (2nd, 2023) by Jack A. Hyman
- Learning Tableau 2025: Leverage Tableau's newest features to revolutionize your data storytelling with AI-enhanced insights (6th, 2025) by Joshua N. Milligan
- Practical Tableau: 100 Tips, Tutorials, and Strategies from a Tableau Zen Master (2018) by Ryan Sleeper
- Tableau Desktop Pocket Reference: Essential Features, Syntax, and Data Visualizations (2021) by Ryan Sleeper 

Looker (Looker Studio)

>Google Cloud BI and data modeling platform.

Qlik Sense

>Self-service BI tool with associative data exploration.

ThoughtSpot

>AI-powered BI for natural language queries (“search analytics”).

Metabase / Superset

>Open-source BI and dashboarding tools.

**Business Intelligence (BI) vs. Data Analytics**

| Feature       | Business Intelligence (BI)                                                                | Data Analytics                                                                                     |
| ------------- | ----------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| Core question | What happened? What is happening now?                                                     | Why did it happen? What will happen?                                                               |
| Primary focus | Descriptive analytics—summarizing past and present data to monitor performance and trends | Predictive and prescriptive analytics—using data to forecast future outcomes and recommend actions |
| Data used     | Historical and real-time data to monitor key performance indicators (KPIs)                | A broader range of structured and unstructured data to find patterns                               |
| Methodology   | Reporting, dashboards, and data visualization                                             | Data mining, statistical modeling, machine learning, and algorithms                                |
| Users         | Often non-technical business leaders and management                                       | More technical users like data analysts and scientists                                             |

### Data Governance

>Ensure data accuracy, lineage, security, and reliability.

Data Governance

- Data Governance: The Definitive Guide: People, Processes, and Tools to Operationalize Data Trustworthiness (2021) by Evren Eryurek, Uri Gilad, Valliappa Lakshmanan, Anita Kibunguchy-Grant, Jessi Ashdown
- Data Management at Scale: Best Practices for Enterprise Architecture (2020) by Piethein Strengholt
- Foundations for Architecting Data Solutions: Managing Successful Data Projects (2018) by Ted Malaska, Jonathan Seidman
- The Enterprise Big Data Lake: Delivering the Promise of Big Data and Data Science (2019) by Alex Gorelik
- The Enterprise Data Catalog: Improve Data Discovery, Ensure Data Governance, and Enable Innovation (2023) by Ole Olesen-Bagneux

DataHub

>Open-source data catalog and lineage tracking system.

Collibra / Alation / Atlan

>Enterprise data governance and catalog platforms.

Great Expectations

>Framework for automated data validation and testing.

Monte Carlo / Bigeye

>Data observability platforms to detect pipeline issues.

Apache Atlas

>Governance and metadata management for Hadoop ecosystems.

Grafana / Prometheus

>Monitoring and alerting for data and system health.

### End-to-End Analytics Platforms

Microsoft Fabric

>Microsoft Fabric is an end-to-end data analytics platform developed by Microsoft that unifies data engineering, data integration, data science, real-time analytics, and business intelligence (BI) in a single, cloud-based environment.

>Unified analytics across Power BI, Synapse, Data Factory.

- Real-Time Intelligence with Microsoft Fabric: Empowering Data-Driven Decisions in the Era of AI (2026) by Johan Ludvig Brattås, Frank Geisler
- Microsoft Fabric Analytics Engineer Associate Study Guide: Hands-on Practice and Expert Tips for Acing the DP-600 Certification Exam (2026) by Brian Bønk, Valerie Junk

Databricks Lakehouse

>Combines data engineering, ML, and BI.

- Building Modern Data Applications Using Databricks Lakehouse: Develop, optimize, and monitor data pipelines on Databricks (2024) by Will Girten

Google Cloud Vertex AI + BigQuery + Looker

>Integrated for data-to-insight workflows.

SAS Viya

>Enterprise analytics, modeling, and reporting.

### OLAP (Online Analytical Processing)

- [ClickHouse - a fast open-source OLAP database management system](https://clickhouse.tech/)
- [Apache Druid - a high performance real-time analytics database](https://druid.apache.org/)
- [Apache Pinot - Realtime distributed OLAP datastore](https://pinot.apache.org/)

<br>

<h2><a name="crawler_t" href="#crawler_c">Crawler and Anti-Crawler</a></h2>

<br>

**Web Scraping with Python**

- **Web Scraping with Python** (3rd, 2024) by Ryan Mitchell [4.18, 403]
- Hands-On Web Scraping with Python: Extract quality data from the web using effective Python techniques (2nd, 2023) by Anish Chapagain
- Python Automation Cookbook: 75 Python automation ideas for web scraping, data wrangling, and processing Excel, reports, emails, and more (2nd, 2020) by Jaime Buelta 
- Mining the Social Web: Data Mining Facebook, Twitter, LinkedIn, Instagram, GitHub, and More (3rd, 2019) by Matthew A. Russell and Mikhail Klassen [3.73, 373]
- Mining Social Media: Finding Stories in Internet Data (2019) by Lam Thuy Vo

Some more

- Getting Structured Data from the Internet: Running Web Crawlers/Scrapers on a Big Data Production Scale (2020) by Jay M. Patel 
- Practical Web Scraping for Data Science: Best Practices and Examples with Python (2018) by Seppe vanden Broucke and Bart Baesens 
- Python Web Scraping Cookbook: Over 90 proven recipes to get you scraping with Python, micro services, Docker and AWS (2018) by Michael Heydt
- Website Scraping with Python: Using BeautifulSoup and Scrapy (2018) by Gábor László Hajba
- Python 3网络爬虫开发实战 by 崔庆才

**Robots.txt**

- [Robotstxt.org](https://www.robotstxt.org/)
- [Introduction to robots.txt](https://developers.google.com/search/docs/crawling-indexing/robots/intro)

**JavaScript Reverse Engineering & Deobfuscation**

- 反爬虫AST原理与还原混淆实战 by 李岳阳、卓斌
- JS Deobfuscation Tools
	- [JavaScript Deobfuscator](https://deobfuscate.io/)
	- [JSNice](http://jsnice.org/)
- JS Formatting Tools
	- Prettier
	- ESLint

**Android Reverse Engineering**

--


**Criminal Law**

- 第二百五十三条之一：【侵犯公民个人信息罪】
- 第二百八十五条：【非法侵入计算机信息系统罪;非法获取计算机信息系统数据、非法控制计算机信息系统罪;提供侵入、非法控制计算机信息系统程序、工具罪】
- 第二百八十六条：【破坏计算机信息系统罪】
- [明确越界网络爬虫行为的刑事处罚边界](https://www.spp.gov.cn/spp/llyj/202202/t20220215_544538.shtml)

<br>

<h2><a name="ai_t" href="#ai_c">Artificial Intelligence</a></h2>
<br>

### The new age of AI

- Co-Intelligence: Living and Working with AI (2024) by Ethan Mollick
- Superagency: What Could Possibly Go Right with Our AI Future (2025) by Reid Hoffman, Greg Beato
- Nexus: A Brief History of Information Networks from the Stone Age to AI (2024) by Yuval Noah Harari 
- The Coming Wave: AI, Power, and Our Future (2025) by Mustafa Suleyman
- Brave New Words: How AI Will Revolutionize Education (and Why That's a Good Thing) (2024) by Salman Khan
- The Singularity Is Nearer: When We Merge with AI (2024) by Ray Kurzweil
- Mastering the Data Paradox: Key to Winning in the AI Age (2024) by Nitin Seth
- Supremacy: AI, ChatGPT, and the Race that Will Change the World (2024) by Parmy Olson
- The Age of AI: And Our Human Future (2021) by Henry A Kissinger, Eric Schmidt, Daniel Huttenlocher
- AI 2041: Ten Visions for Our Future (2021) by Kai-Fu Lee, Chen Qiufan

### Introduction to Artificial Intelligence

- Grokking Artificial Intelligence Algorithms: Understand and apply the core algorithms of deep learning and artificial intelligence in this friendly illustrated guide including exercises and examples (2020) by Rishal Hurbans
- Introduction to Artificial Intelligence by Philip C. Jackson
- Artificial Intelligence: A Modern Approach by Stuart Russell, Peter Norvig
- The Elements of Statistical Learning: Data Mining, Inference, and Prediction by Trevor Hastie, Robert Tibshirani, Jerome Friedman
- An Introduction to Statistical Learning: With Applications in R by Gareth James, Trevor Hastie, Robert Tibshirani, Daniela Witten
- AI and Machine Learning for Coders: A Programmer's Guide to Artificial Intelligence by Laurence Moroney 

### Machine Learning

Machine Learning

- Pattern Recognition and Machine Learning (2006) by Christopher M. Bishop [4.32, 1885]
- The Hundred-Page Machine Learning Book (2019) by Andriy Burkov [4.25, 1386]
- Designing Machine Learning Systems: An Iterative Process for Production-Ready Applications (2022) by Chip Huyen [4.5, 900]
- Machine Learning (1986) by Tom M. Mitchell [4.07, 853]
- Introduction to Machine Learning with Python: A Guide for Data Scientists (2016) by Andreas C. Müller, Sarah Guido [4.34, 587]
- Machine Learning With Random Forests And Decision Trees: A Visual Guide For Beginners (2016) by Scott Hartshorn [4.0, 546]
- Machine Learning: A Probabilistic Perspective (2012) Kevin P. Murphy [4.34, 520]
- Information Theory, Inference, and Learning Algorithms by David J.C. MacKay [4.52, 486]
- Machine Learning For Absolute Beginners: A Plain English Introduction (2020) by Oliver Theobald [4.12, 458]
- Machine Learning Design Patterns: Solutions to Common Challenges in Data Preparation, Model Building, and MLOps (2020) by Valliappa Lakshmanan, Sara Robinson, Michael Munn [4.2, 266]
- Introduction to Machine Learning Systems: Principles and Practices of Engineering Artificially Intelligent Systems by Vijay Janapa Reddi [open-source book](https://www.mlsysbook.ai/)
- Machine Learning for OpenCV
- 机器学习 by 周志华 (**西瓜书**)

Some more

- Machine Learning in Action (2011) by Peter Harrington [3.78, 240] 
- The StatQuest Illustrated Guide To Machine Learning (2022) by Josh Starmer [4.71, 192]
- Machine Learning with Neural Networks: An In-depth Visual Introduction with Python: Make Your Own Neural Network in Python: A Simple Guide on Machine Learning with Neural Networks (2017) by Michael Taylor, Mark Koning [4.0, 173]
- Machine Learning Engineering (2020) by Andriy Burkov [4.31, 140]
- Understanding Machine Learning: From Theory to Algorithms (2014) by Shai Shalev-Shwartz, Shai Ben-David [4.21, 131]
- Foundations of Machine Learning (2nd, 2018) by Mehryar Mohri, Afshin Rostamizadeh, Ameet Talwalkar [4.21, 94]
- Grokking Machine Learning (2021) by Luis G. Serrano [4.47, 64]
- Learning Deep Learning: Theory and Practice of Neural Networks, Computer Vision, Natural Language Processing, and Transformers Using TensorFlow (2021) by Magnus Ekman
- Machine Learning Pocket Reference: Working with Structured Data in Python (2019) by Matt Harrison 
- Python Machine Learning By Example: Unlock machine learning best practices with real-world use cases (4th, 2024) by Yuxi (Hayden) Liu 
- Machine Learning with Python Cookbook: Practical Solutions from Preprocessing to Deep Learning (2nd, 2023) by Kyle Gallatin, Chris Albon 

Mathematics for Machine Learning

- Mathematics of Machine Learning: Master linear algebra, calculus, and probability for machine learning (2025) by Tivadar Danka
- Mathematics for Machine Learning (2020) by Marc Peter Deisenroth

Courses

- [Machine Learning Crash Course - Google Developer](https://developers.google.com/machine-learning/crash-course)
- [Data Science: Machine Learning - Harvard](https://pll.harvard.edu/course/data-science-machine-learning)
- [CS229: Machine Learning - Stanford](https://online.stanford.edu/courses/cs229-machine-learning) 
	- [Stanford CS229: Machine Learning Full Course taught by Andrew Ng 吴恩达 | Autumn 2018 - YouTube](https://www.youtube.com/playlist?list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU)
- [6.036: Introduction to Machine Learning - MIT](https://openlearninglibrary.mit.edu/courses/course-v1:MITx+6.036+1T2019/about)

### Deep Learning

- Deep Learning (2016) by Aaron Courville, Ian Goodfellow, and Yoshua Bengio (**花书**) [4.43, 1903]
- Deep Learning with Python (3rd, 2025) by Francois Chollet [4.57, 1273]
- The Deep Learning Revolution (2018) by Terry Sejnowski [3.75, 491]
- Neural Networks and Deep Learning (2013) by Michael Nielsen [4.56, 417]
- Deep Learning (The MIT Press Essential Knowledge series) (2019) by John D. Kelleher [3.9, 443]
- Generative Deep Learning: Teaching Machines To Paint, Write, Compose, and Play (2nd, 2023) by David Foster [4.3, 245]
- Grokking Deep Learning (2019) by Andrew W. Trask [4.23, 238]
- Machine Learning: An Algorithmic Perspective by Stephen Marsland [3.77, 182]
- Fundamentals of Deep Learning: Designing Next-Generation Machine Intelligence Algorithms (2nd, 2022) by Nicholas Locascio and Nikhil Buduma [3.86, 112]
- Deep Learning Illustrated: A Visual, Interactive Guide to Artificial Intelligence (2019) by Jon Krohn, Grant Beyleveld, Aglaé Bassens [4.3, 107]
- 深度学习入门 by [日］斋藤康毅 [9.5, 1832] ゼロから作るDeep Learning

Some more

- Deep Learning: A Practitioner's Approach (2015) by Adam Gibson and Josh Patterson [3.77, 110]
- Understanding Deep Learning (2023) by Simon J.D. Prince [4.6, 86]
- Deep Learning: A Visual Approach (2021) by Andrew Glassner [4.9, 61]
- Deep Learning for Vision Systems (2020) by Mohamed Elgendy [4.3, 48]
- Deep Learning from Scratch: Building with Python from First Principles (2019) by Seth Weidman [4.0, 45]
- Deep Learning: Foundations and Concepts (2024th) by Christopher M. Bishop, Hugh Bishop [4.6, 40]
- Deep Learning Cookbook: Practical Recipes to Get Started Quickly (2018) by Douwe Osinga [3.93, 29]
- Practical Deep Learning: A Python-Based Introduction (2nd, 2025) by Ronald T. Kneusel
- Artificial Intelligence with Python Cookbook: Proven recipes for applying AI algorithms and deep learning techniques using TensorFlow 2.x and PyTorch 1.6 (2020) by Ben Auffarth 
- Dive into Deep Learning (2023) by Mu Li, Aston Zhang, Zachary Lipton, Alexander J. Smola [HTML](https://d2l.ai/) （中文版：动手学深度学习 by 李沐 [HTML](https://zh.d2l.ai/) ）

Courses

- [CS230: Deep Learning - Stanford](https://online.stanford.edu/courses/cs230-deep-learning) by Andrew Ng 吴恩达
	- [Stanford CS230: Deep Learning | Autumn 2018 - YouTube](https://www.youtube.com/playlist?list=PLoROMvodv4rOABXSygHTsbvUz4G_YQhOb)
- [MIT 6.S191 Introduction to Deep Learning](https://introtodeeplearning.com/)
- [Practical Deep Learning for Coders](https://course.fast.ai/)
- [【2025版】李沐深度学习系列课程](https://www.bilibili.com/video/BV1daQAYuEYm/). 涵盖CNN、RNN、LSTM、GAN、DQN、transformer、自编码器和注意力机制等神经网络核心知识点

Math for Deep Learning

- Math and Architectures of Deep Learning (2024) by Krishnendu Chaudhury
- Math for Deep Learning: What You Need to Know to Understand Neural Networks (2021) by Ronald T. Kneusel
- Inside Deep Learning: Math, Algorithms, Models (2022) by Edward Raff 

### Neural Network

- Make Your Own Neural Network (2016) by Tariq Rashid [4.3, 693]
- Neural Network Design by Martin T. Hagan [4.33, 60]
- Neural Networks And Learning Machines by Simon Haykin [4.09, 45]
- The Math of Neural Networks (2017) by Michael Taylor

### Reinforcement Learning

- Reinforcement Learning: An Introduction (2nd, 2018) by Richard S. Sutton, Andrew G. Barto [4.5, 795]
- Algorithms for Reinforcement Learning (2010) by Csaba Szepesvari
- Hands-On Reinforcement Learning with Python: Master reinforcement and deep reinforcement learning using OpenAI Gym and TensorFlow by Sudharsan Ravichandiran
- Reinforcement Learning: Industrial Applications of Intelligent Agents (2020) by Phil Winder Ph.D.
- Applied Reinforcement Learning with Python: With OpenAI Gym, Tensorflow, and Keras (2019) by Taweh Beysolow II 

### Deep Reinforcement Learning

> Deep reinforcement learning is a subfield of machine learning that combines reinforcement learning and deep learning.

- Grokking Deep Reinforcement Learning (2020) by Miguel Morales
- Deep Reinforcement Learning Hands-On: Apply modern RL methods, with deep Q-networks, value iteration, policy gradients, TRPO, AlphaGo Zero and more (3rd, 2024) by Maxim Lapan
- Deep Reinforcement Learning in Action (2020) by Brandon Brown, Alexander Zai
- Deep Reinforcement Learning with Python: Master classic RL, deep RL, distributional RL, inverse RL, and more with OpenAI Gym and TensorFlow (2nd, 2020) by Sudharsan Ravichandiran
- The Art of Reinforcement Learning: Fundamentals, Mathematics, and Implementations with Python (2023) by Michael Hu 

### Robotics

- Life 3.0: Being Human in the Age of Artificial Intelligence by Max Tegmark
- The Master Algorithm: How the Quest for the Ultimate Learning Machine Will Remake Our World by Pedro Domingos
- Artificial Intelligence for Robotics: Build Intelligent Robots that Perform Human Tasks Using AI Techniques by Francis X. Govers
- The Singularity Is Near: When Humans Transcend Biology by Ray Kurzweil
- Human Compatible: Artificial Intelligence and the Problem of Control by Stuart J. Russell
- The Fourth Age: Smart Robots, Conscious Computers, and the Future of Humanity by Byron Reese
- AI Superpowers by Kai-Fu Lee
- An Introduction to AI Robotics by Robin R. Murphy
- I, Robot by Isaac Asimov

### Computer Vision

- Learning OpenCV: Computer Vision with the OpenCV Library (2008) by Gary Bradski, Adrian Kaehler [4.01, 170]
- Computer Vision: Algorithms and Applications (2nd, 2022) by Richard Szeliski [4.2, 144]
- Multiple View Geometry in Computer Vision (2nd, 2004) by Richard Hartley, Andrew Zisserman [4.35, 141]
- Computer Vision: A Modern Approach (2nd, 2011) by David Forsyth and Jean Ponce [3.8, 94]
- Programming Computer Vision with Python: Tools and Algorithms for Analyzing Images by Jan Erik Solem [3.96, 69]
- Computer Vision: Models, Learning, and Inference (2012) by Simon J. D. Prince [4.4, 58]

Some more

- Practical Machine Learning for Computer Vision: End-to-End Machine Learning for Images (2021) by Valliappa Lakshmanan, Martin Görner, Ryan Gillard 
- Practical Computer Vision with SimpleCV by Demaagd
- Learning OpenCV 3: Computer Vision in C++ with the OpenCV Library (2017) by Adrian Kaehler, Gary Bradski
- Foundations of Computer Vision (2024) by Antonio Torralba, Phillip Isola, William T. Freeman
- Learning OpenCV 4 Computer Vision with Python 3: Get to grips with tools, techniques, and algorithms for computer vision and machine learning (3rd, 2020) by Joseph Howse, Joe Minichino

### Natural Language Processing

- Speech and Language Processing: An Introduction to Natural Language Processing, Computational Linguistics and Speech Recognition (2000) by Daniel Jurafsky and James H. Martin [4.28, 633]
- Natural Language Processing with Python: Analyzing Text with the Natural Language Toolkit (2009) by Edward Loper, Ewan Klein, and Steven Bird [4.1, 567] [Online book](https://www.nltk.org/book/)
- Foundations of Statistical Natural Language Processing (1999) by Christopher D. Manning and Hinrich Schütze [4.1, 261]
- Practical Natural Language Processing: A Comprehensive Guide to Building Real-World NLP Systems (2020) by Sowmya Vajjala, Bodhisattwa Majumder, Anuj Gupta [3.9, 75]
- Natural Language Processing in Action (2nd, 2025) by Hobson Lane, Cole Howard, Hannes Hapke [4.11, 71]
- Neural Network Methods for Natural Language Processing by Yoav Goldberg, Graeme Hirst [4.45, 65]
- Applied Text Analysis with Python: Enabling Language-Aware Data Products with Machine Learning by Benjamin Bengfort, Rebecca Bilbro, and Tony Ojeda [3.82, 56]
- Text Analytics with Python: A Practitioner's Guide to Natural Language Processing (2nd, 2019) by Dipanjan Sarkar [4.12, 49]

Some more

- Introduction to Natural Language Processing (2019) by Jacob Eisenstein
- Natural Language Processing with Python and spaCy: A Practical Introduction (2020) by Yuli Vasiliev
- Python Natural Language Processing Cookbook: Over 60 recipes for building powerful NLP solutions using Python and LLM libraries (2nd, 2024) by Zhenya Antić, Saurabh Chakravarty
- Representation Learning for Natural Language Processing (2020) by Zhiyuan Liu, Yankai Lin, Maosong Sun
- Getting Started with Natural Language Processing (2022) by Ekaterina Kochmar
- Real-World Natural Language Processing: Practical applications with deep learning (2021) by Masato Hagiwara

Courses

- [CS224N: Natural Language Processing with Deep Learning - Stanford](https://web.stanford.edu/class/cs224n/)
- [NLP Tutorial Python - YouTube](https://www.youtube.com/playlist?list=PLeo1K3hjS3uuvuAXhYjV2lMEShq2UYSwX)
- [Live NLP Playlist - YouTube](https://www.youtube.com/playlist?list=PLZoTAELRMXVNNrHSKv36Lr3_156yCo6Nn)

### Recommender Systems

- Programming Collective Intelligence (2002) by Toby Segaran [4.07, 1457]
- Practical Recommender Systems (2019) by Kim Falk [4.15, 84]
- Recommendation Engines (2020) by Michael Schrage [3.7, 105]
- Recommender Systems: An Introduction (2010) by Dietmar Jannach, Markus Zanker, Alexander Felfernig, Gerhard Friedrich [4.06, 54]
- Recommender Systems: The Textbook (2016) by Charu C. Aggarwal [4.28, 47]
- Recommender Systems Handbook (3rd, 2022) by Francesco Ricci, Lior Rokach, Bracha Shapira [4.3, 37]
- 推荐系统实践 by 项亮
- 深度学习推荐系统 by 王喆

Some more

- Statistical Methods for Recommender Systems by Bee-Chung Chen and Deepak K. Agarwal
- Hands-On Recommendation Systems with Python: Start Building Powerful and Personalized, Recommendation Engines with Python (2002) by Rounak Banik
- Building Recommendation Systems in Python and JAX: Hands-On Production Systems at Scale (2024) by Bryan Bischof Ph.D, Hector Yee
- Applied Recommender Systems with Python: Build Recommender Systems with Deep Learning, NLP and Graph-Based Techniques (2022) by Akshay Kulkarni, Adarsha Shivananda, Anoosh Kulkarni 

### Frameworks

#### Scikit-learn

/ˈsʌɪ-kɪt/

>Scikit-learn, often referred to as `sklearn`, is a free and open-source machine learning library for the Python programming language. It is built upon the numerical and scientific libraries NumPy, SciPy, and Matplotlib, and provides a wide range of algorithms for various machine learning tasks.

- [scikit-learn](https://scikit-learn.org/stable/). Machine Learning in Python
- Mastering Machine Learning with scikit-learn - Second Edition: Apply effective learning algorithms to real-world problems using scikit-learn (2nd, 2017) by Gavin Hackeling
- Hands-On Machine Learning with scikit-learn and Scientific Python Toolkits: A practical guide to implementing supervised and unsupervised machine learning algorithms in Python (2020) by Tarek Amr 
- Learning scikit-learn Machine Learning in Python (2022) by Brandon Pondexter

#### PyTorch

/py-tɔːtʃ/

> PyTorch is a Python package that provides two high-level features: 1. Tensor computation (like NumPy) with strong GPU acceleration. 2. Deep neural networks built on a tape-based autograd system.

- [PyTorch documentation](https://docs.pytorch.org/docs/stable/index.html)
- [PyTorch Tutorials](https://docs.pytorch.org/tutorials/)
- [yunjey/pytorch-tutorial - GitHub](https://github.com/yunjey/pytorch-tutorial)
- [PyTorch Tutorial - Tutorialspoint](https://www.tutorialspoint.com/pytorch/index.htm)
- Machine Learning
	- Machine Learning with PyTorch and Scikit-Learn: Develop machine learning and deep learning models with Python (2022) by Sebastian Raschka, Yuxi (Hayden) Liu, Vahid Mirjalili [4.41, 90]
	- Hands-On Machine Learning with Scikit-Learn and PyTorch: Concepts, Tools, and Techniques to Build Intelligent Systems (2025) by Aurélien Géron
- Deep Learning
	- Deep Learning with PyTorch: Build, train, and tune neural networks using Python tools (2020) by Eli Stevens, Luca Antiga [4.19, 135]
	- Deep Learning for Coders with Fastai and PyTorch: AI Applications Without a PhD (2020) by Jeremy Howard and Sylvain Gugger [4.48, 211]
	- Deep Learning with PyTorch Step-by-Step: A Beginner's Guide: Volume I: Fundamentals (2022) by Daniel Voigt Godoy
	- PyTorch Pocket Reference: Building and Deploying Deep Learning Models (2021) by Joe Papa
	- Programming PyTorch for Deep Learning: Creating and Deploying Deep Learning Applications (2019) by Ian Pointer
- Generative AI 
	- AI and ML for Coders in PyTorch: A Coder's Guide to Generative AI and Machine Learning (2025) by Laurence Moroney
	- The Hundred-Page Language Models Book: hands-on with PyTorch (2025) by Andriy Burkov
	- Mastering PyTorch: Create and deploy deep learning models from CNNs to multimodal models, LLMs, and beyond (2nd, 2024) by Ashish Ranjan Jha
	- Generative AI with Python and PyTorch: Navigating the AI frontier with LLMs, Stable Diffusion, and next-gen AI applications (2nd, 2025) by Joseph Babcock, Raghav Bali 
	- Learn Generative AI with PyTorch (2024) by Mark Liu
	- The StatQuest Illustrated Guide to Neural Networks and AI: With hands-on examples in PyTorch!!! (2025) by Josh Starmer
	- Accelerate Model Training with PyTorch 2.X: Build more accurate models by boosting the model training process (2024) by Maicon Melo Alves
	- AI Systems Performance Engineering: Optimizing Model Training and Inference Workloads with GPUs, CUDA, and PyTorch (2025) by Chris Fregly 
- Computer Vision
	- Modern Computer Vision with PyTorch: A practical roadmap from deep learning fundamentals to advanced applications and Generative AI (2nd, 2024) by V Kishore Ayyadevara, Yeshwanth Reddy
- Natural Language Processing
	- Natural Language Processing with PyTorch: Build Intelligent Language Applications Using Deep Learning (2019) by Delip Rao, Brian McMahan

Courses

- [PyTorch Tutorials - YouTube](https://www.youtube.com/playlist?list=PLhhyoLH6IjfxeoooqP9rhU3HJIAVAJ3Vz)
- [Deep Learning With PyTorch - YouTube](https://www.youtube.com/playlist?list=PLCC34OHNcOtpcgR9LEYSdi9r7XIbpkpK1)
- [PyTorch Tutorials - Complete Beginner](https://www.youtube.com/playlist?list=PLqnslRFeH2UrcDBWF5mfPGpqQDSta6VK4)

#### Transformers

/tran(t)sˈfɔːməs/

>Transformers: the model-definition framework for state-of-the-art machine learning models in text, vision, audio, and multimodal models, for both inference and training.


- [Transformers](https://github.com/huggingface/transformers)
- [NielsRogge/Transformers-Tutorials - GitHub](https://github.com/NielsRogge/Transformers-Tutorials)
- How Transformers Work: A Detailed Exploration of Transformer Architecture [Link](https://www.datacamp.com/tutorial/how-transformers-work)
- [Transformers: a Primer](https://www.columbia.edu/~jsl2239/transformers.html). A math-guided tour of the Transformer architecture and preceding literature.
- Transformers in Action (2025) by Nicole Koenigstein
- Natural Language Processing
	- Natural Language Processing with Transformers: Building Language Applications with Hugging Face (2022) by Lewis Tunstall, Leandro von Werra, Thomas Wolf [4.4, 201]
	- Transformers for Natural Language Processing: Build, train, and fine-tune deep neural network architectures for NLP with Python, Hugging Face, and OpenAI's GPT-3, ChatGPT, and GPT-4 (2nd, 2022) by Denis Rothman [4.19, 43]
	- Introduction to Transformers for NLP: With the Hugging Face Library and Models to Solve Problems (2022) by Shashank Mohan Jain
	- Transformers for Natural Language Processing and Computer Vision: Explore Generative AI and Large Language Models with Hugging Face, ChatGPT, GPT-4V, and DALL-E 3 (3rd, 2024) by Denis Rothman
	- Mastering Transformers: Build state-of-the-art models from scratch with advanced natural language processing techniques (2021) by Savaş Yıldırım, Meysam Asgari- Chenaghlu
- Machine Learning
	- Transformers for Machine Learning: A Deep Dive (2022) by Uday Kamath, Kenneth Graham, Wael Emara
- Generative AI
	- Mastering Transformers: The Journey from BERT to Large Language Models and Stable Diffusion (2nd, 2024) by Savaş Yıldırım, Meysam Asgari- Chenaghlu
	- Hands-On Generative AI with Transformers and Diffusion Models (2024) by Omar Sanseviero, Pedro Cuenca, Apolinário Passos

#### TensorFlow & Keras

/ˈtɛn(t)sə-fləʊ/

>TensorFlow is an open-source software library developed by Google for machine learning and artificial intelligence, particularly for deep learning. It provides tools and resources for building and training neural networks and other machine learning models. TensorFlow is widely used in various applications, including image recognition, natural language processing, and recommendation systems. 

- [TensorFlow](https://www.tensorflow.org/). An end-to-end platform for machine learning.
- [TensorFlow Tutorial - Tutorialspoint](https://www.tutorialspoint.com/tensorflow/index.htm)
- [aymericdamien/TensorFlow-Examples - GitHub](https://github.com/aymericdamien/TensorFlow-Examples). TensorFlow Tutorial and Examples for Beginners (support TF v1 & v2).
- TensorFlow Tutorial For Beginners [Link](https://www.datacamp.com/tutorial/tensorflow-tutorial)
- TensorFlow in Action (2022) by Thushan Ganegedara
- Machine Learning
	- Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems (3rd, 2022) by Aurélien Géron [4.5, 2722]
	- Python Machine Learning: Machine Learning and Deep Learning with Python, scikit-learn, and TensorFlow 2 (3rd, 2019) by Sebastian Raschka, Vahid Mirjalili [4.25, 753]
	- TensorFlow 2 Pocket Reference: Building and Deploying Machine Learning Models (2021) by KC Tung 
	- Machine Learning with TensorFlow (2nd, 2021) by Mattmann A. Chris
- Deep Learning
	- Deep Learning with TensorFlow and Keras: Build and deploy supervised, unsupervised, deep, and reinforcement learning models (3rd, 2022) by Amita Kapoor, Antonio Gulli, Sujit Pal
	- Learning TensorFlow: A Guide to Building Deep Learning Systems (2017) by Tom Hope, Yehezkel S. Resheff, Itay Lieder
	- Advanced Deep Learning with TensorFlow 2 and Keras: Apply DL, GANs, VAEs, deep RL, unsupervised learning, object detection and segmentation, and more (2nd, 2020) by Rowel Atienza 
	- Deep Learning with TensorFlow 2 and Keras: Regression, ConvNets, GANs, RNNs, NLP, and more with TensorFlow 2 and the Keras API (2nd, 2019) by Antonio Gulli, Amita Kapoor, Sujit Pal
	- Practical Deep Learning for Cloud, Mobile, and Edge: Real-World AI & Computer-Vision Projects Using Python, Keras & TensorFlow (2019) by Anirudh Koul, Siddha Ganju, Meher Kasam [4.6, 44]
- Generative AI
	- Generative AI with Python and TensorFlow 2: Create images, text, and music with VAEs, GANs, LSTMs, Transformer models (2021) by Joseph Babcock
- Natural Language Processing
	- Advanced Natural Language Processing with TensorFlow 2: Build effective real-world NLP applications using NER, RNNs, seq2seq models, Transformers, and more (2021) by Ashish Bansal 

TinyML

- TinyML: Machine Learning with TensorFlow Lite on Arduino and Ultra-Low-Power Microcontrollers (2020) by Pete Warden, Daniel Situnayake

TensorFlow.js

- Learning TensorFlow.js: Powerful Machine Learning in JavaScript (2021) by Gant Laborde
- Deep Learning with JavaScript: Neural networks in TensorFlow.js (2020) by Shanqing Cai, Stan Bileschi, Eric Nielsen

**Keras**

>Keras is a deep learning API designed for human beings, not machines. Keras focuses on debugging speed, code elegance & conciseness, maintainability, and deployability. When you choose Keras, your codebase is smaller, more readable, easier to iterate on.

>Keras is a high-level API for building and training deep learning models. It was designed for rapid prototyping and ease of use, abstracting away much of the complexity of lower-level frameworks. Keras can run on top of various backends, including TensorFlow, Theano, and Microsoft CNTK. In TensorFlow 2.0 and later, Keras became the official high-level API within TensorFlow, accessible as `tf.keras`.

- [Keras](https://keras.io/). Deep Learning for humans.

#### SpaCy

/ˈspeɪsi/

>SpaCy is an open-source Natural Language Processing (NLP) library in Python, designed for fast, efficient, and production-ready text processing. It’s widely used in AI, machine learning, and data science for working with human language data.

- [SpaCy](https://spacy.io/). Industrial-strength Natural Language Processing in Python
- Mastering spaCy: Build structured NLP solutions with custom components and models powered by spacy-llm (2nd, 2025) by Déborah Mesquita, Duygu Altinok
- Natural Language Processing with Python and spaCy: A Practical Introduction (2020) by Yuli Vasiliev
- Mastering spaCy: An end-to-end practical guide to implementing NLP applications using the Python ecosystem (2021) by Duygu Altinok

### Artificial Intelligence Papers

- [Artificial Intelligence - Elsevier](https://www.journals.elsevier.com/artificial-intelligence)
- [Top Papers in Machine Learning - Papers With Code](https://paperswithcode.com/greatest)

Resources

- [awesome-AI-books](https://github.com/zslucky/awesome-AI-books)

<br>

<h2><a name="blockchain_t" href="#blockchain_c">Blockchain and Cryptocurrency</a></h2>

<br>

### Blockchain

#### Introduction to Blockchain

- [Blockchain - Wikipedia](https://en.wikipedia.org/wiki/Blockchain)
- **Blockchain Basics: A Non-Technical Introduction in 25 Steps** (2017) by Daniel Drescher
- **Blockchain Bubble or Revolution: The Present and Future of Blockchain and Cryptocurrencies** (2019) by Neel Mehta
- Blockchain: Blueprint for a New Economy by Melanie Swan
- The Business Blockchain: Promise, Practice, and Application of the Next Internet Technology by William Mougayar
- Blockchain Wars: The Future of Big Tech Monopolies and the Blockchain Internet by Evan McFarland
- The Sovereign Individual: Mastering the Transition to the Information Age by James Dale Davidson, William Rees-Mogg
- The Price of Tomorrow: Why Deflation is the Key to an Abundant Future by Jeff Booth
- The Creature from Jekyll Island: A Second Look at the Federal Reserve by G. Edward Griffin
- Blockchain For Dummies by Tiana Laurence
- Financial Services Revolution: How Blockchain is Transforming Money, Markets, and Banking by Alex Tapscott
- Irrational Exuberance by Robert J. Shiller
- The Infinite Machine: How an Army of Crypto-hackers Is Building the Next Internet with Ethereum by Camila Russo

#### Techniques of Blockchain

- Mastering Blockchain: Distributed Ledgers, Decentralization and Smart Contracts Explained by Imran Bashir
- Mastering Blockchain: A deep dive into distributed ledgers, consensus protocols, smart contracts, DApps, cryptocurrencies, Ethereum, and more by Imran Bashir
- Mastering Blockchain: Unlocking the Power of Cryptocurrencies, Smart Contracts, and Decentralized Applications by Lorne Lantz, Daniel Cawrey

Lightning Network (Layer 2)

- Mastering the Lightning Network: A Second Layer Blockchain Protocol for Instant Bitcoin Payments by Andreas M. Antonopoulos, Olaoluwa Osuntokun, Ren Pickhardt

### Cryptocurrencies

/ˈkrɪptəʊ - ˈkʌr(ə)n(t)si/

#### Introduction to Cryptocurrencies

- [Coin Center - Education](https://www.coincenter.org/education/)
- [Blockchain and Money - MIT Course](https://ocw.mit.edu/courses/sloan-school-of-management/15-s12-blockchain-and-money-fall-2018/index.htm)
- The Fiat Standard: The Debt Slavery Alternative to Human Civilization by Saifedean Ammous
- Layered Money: From Gold and Dollars to Bitcoin and Central Bank Digital Currencies by Nik Bhatia
- Blockchain Bubble or Revolution: The Present and Future of Blockchain and Cryptocurrencies by Neel Mehta, Aditya Agashe, Parth Detroja 
- The Basics of Bitcoins and Blockchains: An Introduction to Cryptocurrencies and the Technology that Powers Them by Antony Lewis
- Narrative Economics: How Stories Go Viral and Drive Major Economic Events by Robert J. Shiller
- Kings of Crypto: One Startup's Quest to Take Cryptocurrency Out of Silicon Valley and Onto Wall Street by Jeff John Roberts

#### Crypto Mining

- Cryptocurrency Mining For Dummies by Peter Kent, Tyler Bain
- Cryptocurrency Mining: A Complete Beginners Guide to Mining Cryptocurrencies, Including Bitcoin, Litecoin, Ethereum, Altcoin, Monero, and Others by Crypto Tech Academy

#### Crypto Investing

- Cryptocurrency Investing For Dummies by Kiana Danial
- The Only Bitcoin Investing Book You’ll Ever Need: An Absolute Beginner’s Guide to the Cryptocurrency Which Is Changing the World and Your Finances in 2021 & Beyond by Freeman Publications
- The Everything Guide to Investing in Cryptocurrency: From Bitcoin to Ripple, the Safe and Secure Way to Buy, Trade, and Mine Digital Currencies by Ryan Derousseau
- Cryptoassets: The Innovative Investor's Guide to Bitcoin and Beyond by Chris Burniske, Jack Tatar

#### Bitcoin

Must Read

- **Bitcoin: A Peer-to-Peer Electronic Cash System** by Satoshi Nakamoto [PDF](https://bitcoin.org/bitcoin.pdf)
- The Bitcoin Lightning Network: Scalable Off-Chain Instant Payments [PDF](https://lightning.network/lightning-network-paper.pdf)
- [Bitcoin Core - GitHub](https://github.com/bitcoin/bitcoin)
- [Bitcoin - Wikipedia](https://en.wikipedia.org/wiki/Bitcoin)
- **The Internet of Money** (2016) by Andreas M. Antonopoulos
- **The Bitcoin Standard: The Decentralized Alternative to Central Banking** (2018) by Saifedean Ammous 
- **Mastering Bitcoin: Programming the Open Blockchain** (2rd, 2023) by Andreas Antonopoulos
- Mastering Bitcoin: Programming the Open Blockchain (2nd, 2017) by Andreas Antonopoulos
- **Cryptoassets: The Innovative Investor's Guide to Bitcoin and Beyond** (2017) by Chris Burniske
- **Digital Gold: Bitcoin and the Inside Story of the Misfits and Millionaires Trying to Reinvent Money** (2016) by Nathaniel Popper
- Bitcoin and Cryptocurrency Technologies: A Comprehensive Introduction by Arvind Narayanan
- Programming Bitcoin: Learn How to Program Bitcoin from Scratch by Jimmy Song
- Attack of the 50 Foot Blockchain: Bitcoin, Blockchain, Ethereum & Smart Contracts by David Gerard
- The Book of Satoshi: The Collected Writings of Bitcoin Creator Satoshi Nakamoto by Phil Champagne
- The Age of Cryptocurrency: How Bitcoin and Digital Money Are Challenging the Global Economic Order by Paul Vigna
- Inventing Bitcoin: The Technology Behind The First Truly Scarce and Decentralized Money Explained by Yan Pritzker
- 21 Lessons: What I've Learned from Falling Down the Bitcoin Rabbit Hole by Gigi


Some More

- Decentralized Applications: Harnessing Bitcoin's Blockchain Technology by Siraj Raval
- Blockchain Revolution: How the Technology Behind Bitcoin Is Changing Money, Business, and the World by Don Tapscott
- The End of Money: The story of bitcoin, cryptocurrencies and the blockchain revolution by New Scientist
- Bitcoin Clarity: The Complete Beginners Guide to Understanding by Kiara Bickers
- Bitcoin: Sovereignty through mathematics by Knut Svanholm

Resources

- https://bitcoin-resources.com/

#### Ethereum

/ˈɛθərɪəm/

- [Ethereum Whitepaper](https://ethereum.org/en/whitepaper/)
- [Ethereum wiki - GitHub](https://github.com/ethereum/wiki/wiki)
- [Ethereum - Wikipedia](https://en.wikipedia.org/wiki/Ethereum)
- Mastering Ethereum: Building Smart Contracts and Dapps by Andreas M Antonopoulos
- Ethereum: Blockchains, Digital Assets, Smart Contracts, Decentralized Autonomous Organizations by Henning Diedrich
- Out of the Ether: The Amazing Story of Ethereum and the $55 Million Heist that Almost Destroyed It All by Matthew Leising
- Ethereum For Dummies by Michael G. Solomon

Programming

- Solidity Programming Essentials: A beginner's guide to build smart contracts for Ethereum and blockchain by Ritesh Modi
- Learn Ethereum: Build your own decentralized applications with Ethereum and smart contracts by Xun Wu, Zhihong Zou, Dongying Song
- Mastering Blockchain Programming with Solidity: Write production-ready smart contracts for Ethereum blockchain with Solidity by Jitendra Chittoda
- Beginning Ethereum Smart Contracts Programming: With Examples in Python, Solidity, and JavaScript by Wei-Meng Lee
- Beginning Ethereum and Solidity with React: Complete Guide to becoming a Blockchain Developer by Greg Lim

Smart Contract

- Hands-On Smart Contract Development with Solidity and Ethereum: From Fundamentals to Deployment by Kevin Solorio, Randall Kanna, Dave Hoover

DApps

- Building Ethereum DApps: Decentralized Applications on the Ethereum Blockchain by Roberto Infante

### Decentralized Finance (DeFi)

- [Decentralized finance - Wikipedia](https://en.wikipedia.org/wiki/Decentralized_finance)
- [Decentralized finance - Ethereum](https://ethereum.org/en/defi/)
- [Top DeFi Tokens by Market Capitalization](https://coinmarketcap.com/view/defi/)
- [DeFi: The Ultimate Beginner's Guide to Decentralized Finance](https://decrypt.co/resources/defi-ultimate-beginners-guide-decentralized-finance)
- How to DeFi: Beginner by Coin Gecko, Darren Lau, Sze Jin Teh
- How to DeFi: Advanced by Coin Gecko, Lucius Fang, Benjamin Hor, Erina Azmi, Win Win Khor
- DeFi and the Future of Finance by Ashwin Ramachandran, Campbell Harvey, and Joey Santoro

### Non-fungible token (NFT) and Metaverse

NFT

- [Non-fungible token - Wikipedia](https://en.wikipedia.org/wiki/Non-fungible_token)
- [Non-fungible tokens - Ethereum](https://ethereum.org/en/nft/)
- [NFTs, explained](https://www.theverge.com/22310188/nft-explainer-what-is-blockchain-crypto-art-faq)
- [What You Need To Know About Non-Fungible Tokens](https://www.forbes.com/advisor/investing/nft-non-fungible-token/)
- Token Economy: How the Web3 reinvents the Internet (Token Economy: How the Web3 reinvents the internet by Shermin Voshmgir
- The NFT Handbook: How to Create, Sell and Buy Non-Fungible Tokens by Matt Fortnow, QuHarrison Terry, Kendrick Nguyen
- The NFT Revolution 2021: 2 in 1 Basic guide for beginners + Crypto art & Real Estate Edition. Create, buy, sell and make a profit with non-fungible tokens by Crypto Dukedom
- NFTs for Beginners: Making Money with Non-Fungible Tokens by Oliver J. Rich
- Nfts for Dummies by Tiana Laurence
- NFT Investing for Beginners: The Easy Investing Guide to Create, Buy and Sell with Digital Crypto Art and Collectibles. NFT (Non-Fungible Token) by Kevin W. Allen

Metaverse

- Metaverse Investing Beginners Guide To Crypto Art, NFT’s, & Digital Assets in the Metaverse: The Future of Cryptocurreny, Digital Art, (Non Fungible Token) and Blockchain Gaming by The Meta-Verse
- The Metaverse: Prepare Now For the Next Big Thing! by Terry Winters

### Decentralized Autonomous Organizations (DAOs)

- [Decentralized autonomous organization - Wikipedia](https://en.wikipedia.org/wiki/Decentralized_autonomous_organization)
- [Decentralized autonomous organizations - Ethereum](https://ethereum.org/en/dao/)
- [Decentralized Autonomous Organization (DAO)](https://www.investopedia.com/tech/what-dao/)
- [What Are DAOs And Why You Should Pay Attention](https://www.forbes.com/sites/cathyhackl/2021/06/01/what-are-daos-and-why-you-should-pay-attention/)

<br>

## Web 3.0

<br>

- [What Is Web 3.0 & Why It Matters](https://medium.com/fabric-ventures/what-is-web-3-0-why-it-matters-934eb07f3d2b)
- The Spatial Web: How Web 3.0 Will Connect Humans, Machines, and AI to Transform the World by Gabriel Rene, Dan Mapes, Jay Samit

<br>

## IoT and 5G

<br>

Books

- Exploring Raspberry Pi: Interfacing to the Real World with Embedded Linux by Derek Molloy
- IoT and Edge Computing for Architects: Implementing edge and IoT systems from sensors to clouds with communication systems, analytics, and security (2nd, 2020) by Perry Lea
- Hands-On Industrial Internet of Things: Create a powerful Industrial IoT infrastructure using Industry 4.0 by Giacomo Veneri, Antonio Capasso
- Precision: Principles, Practices and Solutions for the Internet of Things by Timothy Chou
- IoT Fundamentals: Networking Technologies, Protocols, and Use Cases for the Internet of Things by David Hanes, Gonzalo Salgueiro, Patrick Grossetete
- Hands-On Artificial Intelligence for IoT: Expert machine learning and deep learning techniques for developing smarter IoT systems by Amita Kapoor
- The IoT Hacker's Handbook: A Practical Guide to Hacking the Internet of Things by Aditya Gupta
- Practical Internet of Things Security by Brian Russell, Drew Van Duren
- The Amazon Way on IoT: 10 Principles for Every Leader from the World's Leading Internet of Things Strategies by John Rossman
- Enterprise Iot: Strategies and Best Practices for Connected Products and Services by Dirk Slama, Frank Puhlmann, Jim Morrish
- Getting Started with the Internet of Things: Connecting Sensors and Microcontrollers to the Cloud by Cuno Pfister
- Precision: Principles, Practices and Solutions for the Internet of Things by Timothy Chou
- Programming the Internet of Things: An Introduction to Building Integrated, Device-To-Cloud Iot Solutions by Andy King
- IoT Inc.: How Your Company Can Use the Internet of Things to Win in the Outcome Economy by Bruce Sinclair 
- The IoT Hacker's Handbook: A Practical Guide to Hacking the Internet of Things by Aditya Gupta 
- Everyware: The Dawning Age of Ubiquitous Computing by Adam Greenfield

Protocols

- [The Matter smart home protocol](https://csa-iot.org/all-solutions/matter/)

<br>

<h2><a name="quantcomp_t" href="#quantcomp_c">Quantum Computing</a></h2>

<br>

/ˈkwɒntəm - kəmˈpjuːtɪŋ/

Quantum Computing

- **Quantum Computing: An Applied Approach** (2nd, 2021) by Jack D. Hidary
- **Quantum Computing for Everyone** (2020) by Chris Bernhardt
- **Quantum Computing Since Democritus** (2013) by Scott Aaronson
- Mathematics of Quantum Computing: An Introduction by Wolfgang Scherer
- Programming Quantum Computers: Essential Algorithms and Code Samples by Eric R. Johnston , Nic Harrigan
- Quantum Computing for Computer Scientists by Noson S. Yanofsky, Mirco A. Mannucci
- Problems and Solutions in Quantum Computing and Quantum Information by Willi-Hans Steeb, Yorick Hardy
- Dancing with Qubits: How quantum computing works and how it can change the world by Robert S. Sutor
- Quantum: Computing Nouveau: The Technological Step Change That Could Foster Scientific Discovery, Break Blockchains, and Trigger a Global Cybersecurity Arms Race by Jason Schenker
- Quantum Computer Systems: Research for Noisy Intermediate-Scale Quantum Computers by Yongshan Ding and Chong T. Frederic
- Learn Quantum Computing with Python and IBM Quantum Experience: A hands-on introduction to quantum computing and writing your own quantum programs with Python by Robert Loredo

For Quantum Physics

- QUANTUM PHYSICS for Beginners in 90 Minutes without Math: All the major ideas of quantum mechanics, from quanta to entanglement, in simple language by Modern Science
- My First Book of Quantum Physics by Sheddad Kaid-Salah Ferron, Eduard Altarriba
- Introduction to Quantum Mechanics by David J. Griffiths
- Something Deeply Hidden: Quantum Worlds and the Emergence of Spacetime by Sean Carroll 
- Reality Is Not What It Seems: The Journey to Quantum Gravity by Carlo Rovelli , Simon Carnell
- How to Teach Quantum Physics to Your Dog by Chad Orzel
- What Is Real?: The Unfinished Quest for the Meaning of Quantum Physics by Adam Becker
- Quantum Mechanics: The Theoretical Minimum by Leonard Susskind, Art Friedman
- Quantum Enigma: Physics Encounters Consciousness by Bruce Rosenblum and Fred Kuttner
- The Elegant Universe: Superstrings, Hidden Dimensions, and the Quest for the Ultimate Theory by Brian Greene, Erik Davies



<br>

## References

[1] [Distributed Systems - GoodReads](https://www.goodreads.com/list/show/134830.Distributed_Systems)

[2] [What is the best book on building distributed systems? - Quora](https://www.quora.com/What-is-the-best-book-on-building-distributed-systems)

[3] [Blockchain and Related Technologies - Goodreads](https://www.goodreads.com/list/show/121555.Blockchain_and_Related_Technologies)

[4] [Data Science - Learning About Data - Goodreads](https://www.goodreads.com/list/show/33337.Data_Science_Learning_About_Data)

[5] [Data, Information & Analytics - Goodreads](https://www.goodreads.com/list/show/74233.Data_Information_Analytics)
