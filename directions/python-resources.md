# <img src="/assets/icon/programming-languages/Python.svg" width="24px"/> Python Resources

> Life is short (You need Python) - Bruce Eckel

**Content**

- Python
- Utility Libraries
- Data Access
- Web Frameworks
- Web Security
- Python Tools

## Python Fundamentals

Beginner

- Documentation
  - [The Python Tutorial - doc](https://docs.python.org/3/tutorial/)
  - [Python Documentation](https://www.python.org/doc/)
  - [Beginner's Guide to Python](https://wiki.python.org/moin/BeginnersGuide)
- Online Tutorial
  - [Learn X in Y minutes - Python](https://learnxinyminutes.com/docs/python/)
  - [Python Tutorial - W3Schools](https://www.w3schools.com/python/default.asp)
  - [Python Tutorial - tutorialspoint](https://www.tutorialspoint.com/python/)
  - [Learn Python](https://www.learnpython.org/)
  - [Python Tutorial](https://www.pythontutorial.net/)
  - [Real Python](https://realpython.com/)
- **Learning Python** (5th, 2013) by David Ascher and MARK LUTZ
- Learn Python 3 the Hard Way: A Very Simple Introduction to the Terrifyingly Beautiful World of Computers and Code by Zed Shaw
- A Byte of Python by Swaroop C.H. [LINK](https://python.swaroopch.com/)
- **Automate the Boring Stuff with Python: Practical Programming for Total Beginners** (3rd, 2024) by Al Sweigart
- **Python Crash Course: A Hands-On, Project-Based Introduction to Programming** (3rd, 2023) by Eric Matthes
- **Python Pocket Reference: Python In Your Pocket** (5th, 2014) by Mark Lutz 
- **Think Python** (2nd, 2016) by Allen B. Downey
- **Dive into Python 3** (2009) by Mark Pilgrim
- **The Hitchhiker's Guide to Python: Best Practices for Development** by Kenneth Reitz, Tanya Schlusser. [HTML](https://docs.python-guide.org/)
- Python Essential Reference by David M. Beazley
- Introducing Python: Modern Computing in Simple Packages (2nd, 2019) by Bill Lubanovic
- Core Python Programming by Wesley J. Chun
- Python Basics: A Practical Introduction to Python 3 (2021) by David Amos, Dan Bader
- Python Tricks: A Buffet of Awesome Python Features (2017) by Dan Bader
- The Quick Python Book (3rd, 2018) by Naomi Ceder

Style Guide

- [PEP 8 – Style Guide for Python Code](https://peps.python.org/pep-0008/)
- [PEP 257 – Docstring Conventions](https://peps.python.org/pep-0257/)
- [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html)

Project Structure

- [Structuring Your Project](https://docs.python-guide.org/writing/structure/)
- [Guide to Python Project Structure and Packaging](https://medium.com/@joshuale/a-practical-guide-to-python-project-structure-and-packaging-90c7f7a04f95)
- [Best Practices in Structuring Python Projects](https://dagster.io/blog/python-project-best-practices#9-best-practices-for-structuring-python-projects)
- [Python Application Layouts: A Reference](https://realpython.com/python-application-layouts/)

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
  - Python Distilled (2021) by David Beazley 
  - Python工匠 by 朱雷
- Effective
  - Effective Python: 59 Specific Ways to Write Better Python by Brett Slatkin
  - High Performance Python: Practical Performant Programming for Humans by Ian Ozsvald and Micha Gorelick
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

Resources

- [Python Challenge](http://www.pythonchallenge.com/)
- [awesome-python - GitHub](https://github.com/vinta/awesome-python)
- [Python Tips](https://pythontips.com/)
- [Full Stack Python](https://www.fullstackpython.com/)
- [TheAlgorithms/Python - GitHub](https://github.com/TheAlgorithms/Python)
- [Pythonium](https://pythonium.net/)
- [Web Browser Engineering](https://browser.engineering/) by Pavel Panchekha & Chris Harrelson. This book explains, building a basic but complete web browser, from networking to JavaScript, in a couple thousand lines of Python.


## Utility Libraries

### Basic Utilities

General Purpose

--

JSON Parser

- (built-in module)

Document Processing

- Word Documents
  - python-docx
  - Spire.Doc.Free
- Excel Spreadsheets
  - openpyxl
  - pandas
- PowerPoint Presentations
  - python-pptx
- PDF Documents
  - pypdf
  - PyPDF2

Logging

- The standard logging module
- Loguru
- Structlog
- Eliot
- Logbook
- Picologging

Unit Testing

- Pytest
- Unitest

HTTP Client

- http.client (Built-in)
- requests
- aiohttp
- httpx
- urllib3

### More Utilities

Date Time Handling

- arrow

Web Scraping

- Scrapy
- beautifulsoup4
- m3u8

Browser Automation

- selenium
- playwright

Crypto

- pycrypto
- pycryptodome

OCR

<details>
<summary>Click to expand!</summary>

- [Tesseract](https://github.com/tesseract-ocr/tesseract) (⭐️58.1k). Tesseract is one of the most popular OCR libraries in Python. It supports over 100 languages and can extract text from various image formats.
- [pytesseract](https://github.com/madmaze/pytesseract) (⭐5.5k). pytesseract is a wrapper around Tesseract OCR engine. It provides a simple interface to extract text from images using Tesseract.
- [OpenCV](https://github.com/opencv/opencv) (⭐️75.5k): OpenCV is a computer vision library that can be used for OCR tasks. It provides functions for image preprocessing, text detection, and character recognition.
- [EasyOCR](https://github.com/JaidedAI/EasyOCR) (⭐22k). EasyOCR is a recently developed OCR library for Python. It supports more than 80 languages and provides pre-trained models for text extraction from images. EasyOCR is known for its ease of use and high accuracy.
- [ddddocr](https://github.com/sml2h3/ddddocr) (⭐8.3k)
- [Doctr](https://github.com/mindee/doctr) (⭐3.1k)
- [Keras-OCR](https://github.com/faustomorales/keras-ocr) (⭐1.3k)
- [GOCR](https://jocr.sourceforge.net/): GOCR is an OCR engine developed in C. It can be used in Python using the PyOCR library.
- //OCRopus: OCRopus is a collection of document analysis and OCR tools. It includes the Tesseract OCR engine and provides additional features for document layout analysis and text extraction.
- //PyOCR: PyOCR is another wrapper around Tesseract OCR engine. It supports multiple OCR engines, including Tesseract, CuneiForm, and GOCR.

API

- Google Cloud Vision API: Google Cloud Vision API is a cloud-based OCR service provided by Google. It offers advanced features like image classification, object detection, and handwriting recognition.
- Microsoft Azure Computer Vision API: Microsoft Azure Computer Vision API is another cloud-based OCR service. It provides OCR capabilities along with other computer vision features like image tagging and face recognition.
- Amazon Textract: Amazon Textract is a machine learning-based OCR service provided by Amazon Web Services. It can extract text and data from scanned documents, invoices, forms, and tables.

</details>

Data Science and Analysis

- NumPy. Scientific Computing.
- SciPy
- Polars
- Pandas
- Matplotlib. Data Visualization
- Seaborn. Statistical Data Visualization

Machine Learning

- Scikit-learn. Machine Learning
- XGboost
- Catboost

Deep Learning

- PyTorch. Deep Learning Framework
- TensorFlow. Deep Learning Framework
- Keras. High-Level Deep Learning API

Computer Vision

- OpenCV. Computer Vision and Image Processing

Natural Language Processing

- NLTK
- SpaCy

## Data Access

Database Connectivity APIs

- MySQL
  - PyMySQL
  - mysqlclient
  - aiomysql
- Postgres
  - Psycopg2
  - asyncpg
  - pg8000
  - pgsql

Connection Pools

- dbutils

Persistence/ORM Frameworks

- peewee
- Django ORM
- SQLAlchemy
- PonyORM
- SQLObject
- Tortoise ORM

Redis clients

- redis-py

MongoDB clients

- PyMongo
- Motor

Elasticsearch clients

- elasticsearch. Official Python client for Elasticsearch.
- elasticsearch7
- elasticsearch8
- elasticsearch-dsl. a high-level library whose aim is to help with writing and running queries against Elasticsearch. It is built on top of the official low-level client (elasticsearch-py).


## Web Frameworks

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

Management System Scaffolds

- [full-stack-fastapi-template - GitHub](https://github.com/tiangolo/full-stack-fastapi-template)


## Web Security

- django.contrib.auth
- flask_login

## Python Tools

IDE

- PyCharm
- Visual Studio Code

Package Manager

- [pip](https://pypi.org/project/pip/)
- [pypi](https://pypi.org/)
- poetry
- pdm
- uv

## Open-source projects

**Recommended Python open source projects to read**

<details>
    <summary>Click to expand!</summary>

- Core Libraries / General-Purpose Tools
	- [Requests](https://github.com/psf/requests). A simple and elegant HTTP library. Learn clean code structure, exception handling, session management, and API design.
	- [Rich](https://github.com/Textualize/rich). Rich text and formatting in the terminal. Beautiful use of OOP, type annotations, and terminal UI abstractions.
	- [Click](https://github.com/pallets/click). Command-line interface (CLI) creation toolkit. Learn decorators, CLI design, modularity, and context managers.
- Web Development
	- [Django](https://github.com/django/django). High-level Python web framework. Learn MVC (MTV in Django), ORM, middleware, and large-scale code structure.
	- [Flask](https://github.com/pallets/flask). Lightweight WSGI web framework.  Learn minimalistic design, routing, extension system, and app factory pattern.
	- [FastAPI](https://github.com/tiangolo/fastapi). High-performance web framework for APIs. Learn type hints, async programming, and data validation using Pydantic.
- Data Science / Machine Learning
	- [Pandas](https://github.com/pandas-dev/pandas). Data analysis and manipulation library. Dive into NumPy-backed operations, performance optimization, and APIs.
	- [Scikit-learn](https://github.com/scikit-learn/scikit-learn). Machine learning library built on NumPy and SciPy. Well-structured object-oriented design, consistency in API, estimator interface.
- AI / Deep Learning
	- [Transformers (by HuggingFace)](https://github.com/huggingface/transformers). Library for pretrained transformers. Learn advanced object-oriented Python, config-driven design, CLI tools, models as objects.
	- [TensorFlow](https://github.com/tensorflow/tensorflow). Deep learning framework by Google. C++ backend, Python bindings, computation graph design.
- Language Tools / Compilers / Interpreters
	- [PyPy](https://foss.heptapod.net/pypy/pypy). Alternative Python interpreter with a JIT compiler. Hardcore Python interpreter internals.
	- [Black](https://github.com/psf/black). The uncompromising Python code formatter. Learn AST manipulation, robust error handling, tooling standards.
- Games / GUI
	- [pygame](https://github.com/pygame/pygame). Set of Python modules designed for writing video games. Learn multimedia programming, event loops, input handling.
	- [Textual](https://github.com/Textualize/textual). TUI (Terminal UI) framework using Rich. Learn event-driven programming, component-based design, reactive UI.
- Package Management / Dev Tools
	- [Poetry](https://github.com/python-poetry/poetry). Dependency management and packaging tool. Learn CLI design, environment management, semver parsing.
	- [pipx](https://github.com/pypa/pipx). Run Python CLI apps in isolated environments. Learn subprocess management, virtualenv logic, safety patterns.

</details>

**Application Projects**

- [feapder](https://github.com/Boris-code/feapder) 一款上手简单，功能强大的Python爬虫框架。


## Directions

- Crawler
  - Reference [CS Advanced Domains Resources - Crawler and Anti-Crawler](../_cs-advanced-domains-resources.md#crawler)
- Data Science / Data Engineering
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
