<a id="top"></a>

# Python Engineer Roadmap [![README to PDF](https://github.com/DjangoEx/python-engineer-roadmap/actions/workflows/convert-to-pdf.yml/badge.svg)](README.pdf)

[Python](https://www.python.org/) can be used in a lot of computer science fields. In this repository, we have collected resources for each field of computer science that are related to Python.\
**Not sure which source to choose?** You can follow the resources marked with a ✅ symbol, they are highly recommended by the community.


### Contribution
Before you head over, read the [Contribution Guide](CONTRIBUTING.md) first. You are new to contribution process? For more information about the steps and guides, check out the [First Contribution Guide](https://github.com/firstcontributions/first-contributions).

### Table of Contents

- [Prerequisites](#prerequisites)
  - [Algorithms and Data Structures](#algorithms-and-data-structures)
  - [System Design](#system-design)
  - [Git](#git)
  - [Operating System](#operating-system)
  - [Virtual Environment](#virtual-environment)
  - [Python](#python)
- [Career Path](#career-path)
  - [Backend](#backend)
    - [Django](#django)
    - [FastAPI](#fastapi)
    - [Flask](#flask)
    - [Tornado](#tornado)
    - [Web2Py](#web2py)
    - [Sanic](#sanic)
    - [AIOHTTP](#aiohttp)
    - [Bottle](#bottle)
    - [Dash](#dash)
  - [Data Science](#data-science)
    - [Data Analysis](#data-analysis)
      - [Numpy](#numpy)
      - [Scipy](#scipy)
      - [Pandas](#pandas)
    - [Data Visualization](#data-visualization)
      - [Matplotlib](#matplotlib)
      - [Plotly](#plotly)
  - [Machine Learning](#machine-learning)
  - [Deep Learning](#deep-learning)
  - [Reinforcement Learning](#reinforcement-learning)
  - [Neural Networks](#neural-networks)
  - [Image Processing](#image-processing)
  - [DevOps](#devops)
  - [Hacking](#hacking)
  - [Algorithmic Trading](#algorithmic-trading)
  - [Bot](#bot)
    - [Web](#web)
      - [Selenium](#selenium)
      - [WebBot](#webbot)
      - [Browser](#mozbase)
    - [Telegram](#telegram)
      - [Telethon](#telethon)
      - [Pygram](#pygram)
      - [Pyrogram](#pyrogram)
      - [Python Telegram Bot](#python-telegram-bot)
      - [AIOGram](#aiogram)
      - [PyTelegramBotApi](#pytelegrambotapi)
      - [TeleBot](#telebot)
    - [Discord](#discord)
      - [DiscordPy](#discordpy)
    - [Instagram](#instagram)
      - [Instagram-Scraper](#instagram-scraper)
      - [InstaPy](#instapy)
- [Advanced Topics](#advanced-topics)
  - [Databases](#databases)
    - [General](#general)
    - [SQLite](#sqlite)
    - [PostgreSQL](#postgresql)
    - [MySQL](#mysql)
    - [Oracle](#oracle)
    - [MongoDB](#mongodb)
    - [Redis](#redis)
    - [MemCached](#memcached)
    - [Apache Cassandra](#apache-cassandra)
  - [Clean Code](#clean-code)
  - [Clean Architecture](#clean-architecture)
  - [Caching](#caching)
  - [Testing](#testing)
    - [Python `unittest` Package](#python-unittest-package)
    - [`PyTest` Testing Package](#pytest-testing-package)
    - [DRF Test Framework](#drf-test-framework)
  - [Container Platforms](#container-platforms)
    - [Docker](#docker)
    - [Kubernetes](#kubernetes)
  - [Programming Paradigms](#programming-paradigms)
    - [Object-Oriented Programming](#object-oriented-programming)
    - [Functional Programming](#functional-programming)
  - [Architectural Patterns](#architectural-patterns)
    - [Microservice](#microservice)
    - [Enterprise Applications](#enterprise-applications)
  - [Design Principles](#design-principles)
    - [SOLID](#solid)
    - [KISS](#kiss)
    - [DRY](#dry)
  - [Design Patterns](#design-patterns)
  - [Message Brokers](#message-brokers)
    - [RabbitMQ](#rabbitmq)
    - [Apache Kafka](#apache-kafka)
  - [WSGI Servers](#wsgi-servers)
    - [Gunicorn](#gunicorn)
    - [uWSGI](#uwsgi)
  - [ASGI Servers](#asgi-servers)
    - [Uvicorn](#uvicorn)
    - [Starlette](#starlette)
  - [Web Servers](#web-servers)
    - [Nginx](#nginx)
    - [Apache](#apache)
  - [API](#api)
    - [Design](#design)
    - [Security](#security)
  - [Availability and Reliability](#availability-and-reliability)
  - [Distributed Systems](#distributed-systems)
  - [Reactive Systems](#reactive-systems)
  - [Refactoring](#refactoring)
  - [Security](#security)
  - [Monitoring](#monitoring)
  - [Soft Skill](#soft-skill)
  - [Public Cloud](#public-cloud)
  - [IoT](#iot)
- [Where to Go Next?](#where-to-go-next)

## Prerequisites

- ### Algorithms and Data Structures
  
  - **Book**
    - ✅ [Grokking Algorithms by Aditya Bhargava](https://www.amazon.com/Grokking-Algorithms-illustrated-programmers-curious/dp/1617292230)
    - ✅ [Cracking the Coding Interview by Gayle Laakmann McDowell](https://www.amazon.com/Cracking-Coding-Interview-Programming-Questions/dp/0984782850)
    - [Data Structure and Algorithmic Thinking with Python: Data Structure and Algorithmic Puzzles by Narasimha Karumanchi](https://www.amazon.com/Data-Structure-Algorithmic-Thinking-Python/dp/8192107590)
    - [Introduction to Algorithms (CLRS)](https://www.amazon.com/Introduction-Algorithms-3rd-MIT-Press/dp/0262033844)

  - **Video**
    - [Data Structures And Algorithms Course by Mosh Hamedani](https://codewithmosh.com/p/data-structures-algorithms)

  - **Platform**
    - ✅ [LeetCode](https://leetcode.com/)
    - [HackerRank](https://www.hackerrank.com/)
    - [CodeWars](https://www.codewars.com/)
    - [TheAlgorithms](https://the-algorithms.com/)
    - [Codeforces](https://codeforces.com/)

  - **Repo**
    - ✅ [Coding University](https://github.com/jwasham/coding-interview-university)

  - **Cheat Sheet**
    - [Data Structures Cheat Sheet](https://intellipaat.com/mediaFiles/2019/02/Python-Data-structures-cheat-sheet.pdf)

- ### System Design
  
  - **Book**
    - ✅ [System Design Interview by Alex Xu](https://www.amazon.com/System-Design-Interview-insiders-Second/dp/B08CMF2CQF)
    - [System Design Interview: Volume 2 by Alex Xu & Sahn Lam](https://www.amazon.com/System-Design-Interview-Insiders-Guide/dp/1736049119)

  - **Course**
    - [Educative - Grokking the System Design Interview](https://www.educative.io/courses/grokking-the-system-design-interview)

- ### Git
  
  - **Documentation**
    - [Git Documentation](https://git-scm.com/docs)

  - **Video**
    - ✅ [Git Course by Mosh Hamedani](https://codewithmosh.com/p/the-ultimate-git-course)
    - [Git and GitHub tutorial for beginners by Amigoscode](https://www.youtube.com/watch?v=3fUbBnN_H2c)
    - [Git and GitHub crash course by freeCodeCamp](https://www.youtube.com/watch?v=RGOj5yH7evk)
    - [Git For Professionals course by Trevor Miller](https://egghead.io/courses/practical-git-for-everyday-professional-use)

  - **Book**
    - [Pro Git](https://git-scm.com/book/en/)
    - [Git Notes for Professionals](https://books.goalkicker.com/GitBook/)

  - **Website**
    - [Git For Beginners by tutorialspoint](https://www.tutorialspoint.com/git/index.htm)
    - [Git For Intermediates and Professionals by W3schools](https://www.w3schools.com/git/)
    - [Advanced Git Tips by atlassian](https://www.atlassian.com/git/tutorials/advanced-overview)
    - [Learn Git Branching](https://learngitbranching.js.org/)
  
  - **Cheat Sheet**
    - [Git cheat sheet](https://wac-cdn.atlassian.com/dam/jcr:e7e22f25-bba2-4ef1-a197-53f46b6df4a5/SWTM-2088_Atlassian-Git-Cheatsheet.pdf?cdnVersion=353)

- ### Operating System

  - **Book**
    - ✅ [LPIC-1: Linux Professional Institute Certification Study Guide: Exams 101 and 102 by Roderick W. Smith](https://www.amazon.com/LPIC-1-Linux-Professional-Institute-Certification/dp/1118495632)

  - **Video**
    - [Lpic-1 Course by Jadi](https://www.youtube.com/watch?v=AKkNUvEHXhk&list=PLFOYXCPEqdNUU55Xvgst8wGTWnz_sd-cj)

  - **Platform**
    - [Linux Journey](https://linuxjourney.com/)

  - **Community**
    - [Discord Linux group](https://discord.gg/discord-linux)
    - [Linux For Everyone Community](https://t.me/linux4everyone)

  - **Cheat Sheet**
    - [Linux commands cheat sheet](https://www.guru99.com/linux-commands-cheat-sheet.html)

- ### Virtual Environment

  - **VENV**
  
    - **Documentation**
      - [VENV Documentation](https://docs.python.org/3/library/venv.html)
  
  - **VirtualEnvWrapper**
    - **Documentation**
      - [VirtualEnvWrapper Documentation](https://virtualenvwrapper.readthedocs.io/en/latest/)
  
  - **PipEnv**
    - **Documentation**
      - [PipEnv Documentation](https://pipenv.pypa.io/en/latest/)
  
  - **Conda**
    - **Documentation**
      - [Conda Documentation](https://docs.conda.io/en/latest/)
  
  - **Python-Poetry**
    - **Documentation**
      - [Python-Poetry Documentation](https://python-poetry.org/docs/)

- ### Python

  - **Documentation**
    - [Python Documentation](https://docs.python.org/3/)

  - **Beginner**
    - **Book**
      - ✅ [Python Crash Course by Eric Matthes](https://www.amazon.co.uk/dp/1593276036/)
      - [Head First Python by Paul Barry](https://www.amazon.com/Head-First-Python-Brain-Friendly-Guide/dp/1449382673)
      - [Learn Python the Hard Way by Zed Shaw](https://www.amazon.com/Learn-Python-Hard-Way-Introduction/dp/0321884914)
      - [Essential Python Tools](https://books.agiliq.com/projects/essential-python-tools/en/latest/)

    - **Video**
      - [Python Beginner Tutorial by NeuralNine](https://www.youtube.com/playlist?list=PL7yh-TELLS1E6dNCzfQl-NG-KJP3C-4mc)
      - [Python Programming Tutorials by Tech with Tim](https://www.youtube.com/playlist?list=PLzMcBGfZo4-mFu00qxl0a67RhjjZj3jXm)

    - **Platform**
      - [W3schools](https://www.w3schools.com/python/default.asp)
      - [Codecademy Python 2](https://www.codecademy.com/learn/learn-python)
      - [Codecademy Python 3](https://www.codecademy.com/learn/learn-python-3)
      - [Sololearn Python](https://www.sololearn.com/learning/1073)

  - **Intermediate**  
    - **Book**
      - ✅ [Python Cookbook by David Beazley & Brian Jones](https://www.amazon.com/Python-Cookbook-Third-David-Beazley/dp/1449340377)
      - [Beyond the Basic Stuff with Python Best Practices for Writing Clean Code by Sweigart, Al](https://www.amazon.de/-/en/Al-Sweigart/dp/1593279663)
      - [Fluent Python by Luciano Ramalho 2nd Edition](https://www.amazon.com/Fluent-Python-Concise-Effective-Programming/dp/1492056359)
      - [Effective Python by Brett Slatkin](https://www.amazon.com/Effective-Python-Specific-Software-Development/dp/0134853989)
      - [Python Concurrency with asyncio](https://www.manning.com/books/python-concurrency-with-asyncio)

    - **Video**
      - [Python Intermediate Tutorial by NeuralNine](https://www.youtube.com/playlist?list=PL7yh-TELLS1F3KytMVZRFO-xIo_S2_Jg1)
      - [Intermediate Python Tutorials by Tech with Tim](https://www.youtube.com/playlist?list=PLzMcBGfZo4-nhWva-6OVh1yKWHBs4o_tv) 
  
    - **Platform**
      - [GeeksForGeeks](https://www.geeksforgeeks.org/python-programming-language)
      - [Programiz](https://www.programiz.com/python-programming)
      - [Scaler Topics](https://www.scaler.com/topics/python/)

  - **Advanced**
    - **Book**
      - ✅ [Architecture Patterns with Python by Harry Percival & Bob Gregory](https://www.amazon.com/Architecture-Patterns-Python-Domain-Driven-Microservices/dp/1492052205)
      - ✅ [Practices of the Python Pro by Dane Hillard](https://www.amazon.com/Practices-Python-Pro-Dane-Hillard/dp/1617296082)
      - ✅ [Python Tricks by Dan Bader](https://www.amazon.com/Python-Tricks-Buffet-Awesome-Features/dp/1775093301)
      - [Python Testing with pytest by Brian Okken](https://www.amazon.com/Python-Testing-pytest-Effective-Scalable/dp/1680502409)
      - [Python Concurrency with asyncio by Matthew Fowler](https://www.manning.com/books/python-concurrency-with-asyncio)
      - [Python for Programmers by Deitel Developer Series](https://deitel.com/python-for-programmers-book/)
      - [Serious Python by Julien Danjou](https://serious-python.com/)
      - [Python Notes for Professionals](https://books.goalkicker.com/PythonBook/)

    - **Video**
      - [Python3: Deep Dive (4 Parts)](https://www.udemy.com/course/python-3-deep-dive-part-1/)

    - **Platform**
      - ✅ [RealPython](https://realpython.com/)
      - [Python-Course](https://python-course.eu/)
  
  - **Community**
    - [Python Discord group](https://discord.gg/python)
    - [Python Telegram group](https://t.me/Python)

  - **Cheat Sheet**
    - [Beginners Python cheat sheet](https://edu.anarcho-copy.org/Programming%20Languages/Python/Python%20CheatSheet/beginners_python_cheat_sheet_pcc_django.pdf)
    - [Python cheat sheet](https://perso.limsi.fr/pointal/_media/python:cours:mementopython3-english.pdf)
  
## Career Path

- ### Backend

  - #### Django
    - **Documentation**
      - [Django Documentation](https://www.djangoproject.com/) 
      - [Django Tutorial - w3schools](https://www.w3schools.com/django/)

    - **Book**
      - [Django for Beginners by William S. Vincent](https://www.amazon.com/gp/product/1735467200)
      - [Django for APIs by William S. Vincent](https://www.amazon.com/gp/product/1735467227/)
      - [Django for Professionals by William S. Vincent](https://www.amazon.com/gp/product/1735467235)
      - [Two Scoops of Django 3.x by Daniel Roy Greenfeld, Audrey Roy Greenfeld](https://www.feldroy.com/books/two-scoops-of-django-3-x)
      - [Test-Driven Development with Python: Obey the Testing Goat: Using Django, Selenium, and JavaScript by Harry Percival](https://www.obeythetestinggoat.com/book/praise.harry.html)
      - [Test-Driven Development with Django by Kevin Harvey](https://www.amazon.com/Test-Driven-Development-Django-Kevin-Harvey/dp/178528116X)
      - [Django3 by example by antonio mele](https://www.amazon.com/Django-Example-powerful-reliable-applications-dp-1838981950/dp/1838981950/ref=mt_other?_encoding=UTF8&me=&qid=)

    - **Video**
      - [Django Web Framework - Full Course for Beginners by Justin Mitchel](https://www.youtube.com/watch?v=F5mRW0jo-U4)
      - [Build REST APIs with Django REST Framework and Python By Shubham Sarda](https://www.packtpub.com/product/build-rest-apis-with-django-rest-framework-and-python-video/9781801819022)
      - [Django For Everybody - Full Course by Dr. Charles Severance](https://youtu.be/o0XbHvKxw7Y)
      - [Django ORM Mastery - Very Academy](https://www.youtube.com/watch?v=iQF6pln3Gog&list=PLOLrQ9Pn6cazjoDEnwzcdWWf4SNS0QZml)
      - [Learn Django Class Base View - Very Academy](https://www.youtube.com/watch?v=GxA2I-n8NR8&list=PLOLrQ9Pn6caxNb9eFZJ6LfY29nZkKmmXT)
      - [Django Course by Mosh Hamedani](https://codewithmosh.com/p/the-ultimate-django-series)
      - [Try Django 3.2 - Python Web Development Tutorial Series by Justin Mitchel](https://www.youtube.com/playlist?list=PLEsfXFp6DpzRMby_cSoWTFw8zaMdTEXgL)

    - **Awesome Django**
      - [Awesome Django](https://github.com/wsvincent/awesome-django#readme)

    - **Community**
      - [Django Discord group](https://discord.me/unofficial-django) 
      - [Django Telegram group](https://t.me/django)

    - **Cheat Sheet**
      - [Django Cheat Sheet](https://cheatography.com/ogr/cheat-sheets/django/)
      - [Django Models Cheat Sheet](https://cheatography.com/lewiseason/cheat-sheets/django-models/)
      - [Django Class Based Views Cheat Sheet](https://cheatography.com/papousekp/cheat-sheets/django-class-based-views/)
      - [Django Class Based Views Cheat Sheet 2](https://ccbv.co.uk/)

  - #### FastAPI

    - **Video**
      - [Python API Development - Comprehensive Course for Beginners by Sanjeev Thiyagarajan](https://www.youtube.com/watch?v=0sOvCWFmrtA)
      - [FastAPI course by testdriven.io & talkpython.fm](https://testdriven.io/talkpython/)

    - **Documentation**
      - [FastAPI documentation](https://fastapi.tiangolo.com)
      - [FastAPI Utilities documentation](https://fastapi-utils.davidmontague.xyz/)

    - **Awesome FastAPI**
      - [Awesome FastAPI](https://github.com/mjhea0/awesome-fastapi#readme)

    - **Community**
      - [FastApi Discord group](https://discord.gg/VQjSZaeJmf)
  
  - #### Flask
  
    - **Book**
      - [Flask Web Development: Developing Web Applications with Python](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)
      - [Flask Framework Cookbook](https://www.amazon.de/Flask-Framework-Cookbook-techniques-development/dp/1789951291/)
      - [The New And Improved Flask Mega-Tutorial](https://www.amazon.com/New-Improved-Flask-Mega-Tutorial/dp/B09YQ33QYT)

    - **Video**
      - [Flask Tutorial by Tech With Tim](https://youtube.com/playlist?list=PLzMcBGfZo4-n4vJJybUVV3Un_NFS5EOgX)
      - [REST APIs with Flask and Python by Jose Salvatierra](https://www.udemy.com/course/rest-api-flask-and-python/)

    - **Documentation**
      - [Flask Document](https://flask.palletsprojects.com/)

    - **Cheat Sheet**
      - [Flask Cheat Sheet and Quick Reference](https://s3.us-east-2.amazonaws.com/prettyprinted/flask_cheatsheet.pdf)

  - #### Tornado

    - **Book**
      - [Introduction to Tornado by Michael Dory](https://www.amazon.com/Introduction-Tornado-Michael-Dory-2012-03-31/dp/B01FEK31OM)

    - **Video**
      - [Tornado, Coroutines and Concurrency by Bek Brace](https://www.youtube.com/watch?v=-gJ21qzpieA)
      - [Tornado in Depth by Oscar Vilaplana](https://www.youtube.com/watch?v=4Ztq-Yz1ero)
      - [More than just a pretty web framework, the Tornado IOLoop by Gavin M.Roy](https://www.youtube.com/watch?v=3BYN3ouwkRA)

    - **Documentation**
      - [Tornado Document](https://www.tornadoweb.org/en/stable/)

  - #### Web2Py

    - **Documentation**
      - [Web2Py Document](https://web2py.readthedocs.io/en/latest/)

    - **Book**
      - [Complete Reference Manual by Massimo Di Pierro](http://www.web2py.com/book)
      - [Killer Web Development by Marco Laspe](http://killer-web-development.com/)

  - #### Sanic

    - **Documentation**
      - [Sanic Document](https://sanic.readthedocs.io/en/stable/index.html)
      - [Sanic Guide](https://sanic.dev/en/guide/)
    
    - **Article**
      - [Getting Started with Sanic for Python by Mukul Khanna](https://scoutapm.com/blog/go-fast-getting-started-with-sanic-for-python)

    - **Video**
      - [Async Web Apps with Sanic by Dougal Matthews](https://www.youtube.com/watch?v=wb0lk4e9DEg)

  - #### AIOHTTP

    - **Documentation**
      - [AIOHTTP Document](https://docs.aiohttp.org/en/stable/)

  - #### Bottle

    - **Documentation**
      - [Bottle Document](https://bottlepy.org/docs/dev/)

  - #### Dash

    - **Documentation**
      - [Dash-Python Document](https://dash.plotly.com/introduction)

    - **Awesome Dash**
      - [Awesome Dash](https://github.com/ucg8j/awesome-dash#readme)

    - **Template**
      - [Dash Clean Architecture Template](https://github.com/CzakoZoltan08/dash-clean-architecture-template)

  - [List Of All Python Backend Web Frameworks](https://wiki.python.org/moin/WebFrameworks)

- ### Data Science

  - #### Data Analysis

    - ##### Numpy
      - **Documentation**
        - [Numpy Document](https://numpy.org/doc/stable/user/index.html)
  
    - ##### Scipy

      - **Documentation**
        - [Scipy Document](https://docs.scipy.org/doc/scipy/tutorial/index.html)
  
    - ##### Pandas

      - **Documentation**
        - [Pandas Document](https://pandas.pydata.org/docs/user_guide/index.html)

  - #### Data Visualization

    - ##### Matplotlib

      - **Documentation**
        - [Matplotlib Document](https://matplotlib.org/stable/users/index.html)
  
    - ##### Plotly

      - **Documentation**
        - [Plotly Document](https://plotly.com/python-api-reference/)


- ### Machine Learning

  - **Video**
    - [Machine Learning Course by Andrew Ng](https://coursera.org/learn/machine-learning)

- ### Deep Learning

  - **Video**
    - [Deep Learning Specialization by Andrew Ng](https://www.coursera.org/specializations/deep-learning)
    - [MIT-Intoduction to Deep Learning](https://www.youtube.com/playlist?list=PLtBw6njQRU-rwp5__7C0oIVt26ZgjG9NI)
    - [AladdinPersson](https://www.youtube.com/c/AladdinPersson)
    

- ### Reinforcement Learning
  - **Video**
    - [Foundations of Deep RL](https://www.youtube.com/playlist?list=PLwRJQ4m4UJjNymuBM9RdmB3Z9N5-0IlY0)
    - [Deep Reinforcement Learning](https://www.youtube.com/playlist?list=PL_iWQOsE6TfURIIhCrlt-wj9ByIVpbfGc)
    - [Stanford-Reinforcement Learning](https://www.youtube.com/playlist?list=PLoROMvodv4rOSOPzutgyCTapiGlY2Nd8u)
    
- ### Neural Networks

  - **Video**
      - [Neural Networks and Calculus](https://www.youtube.com/c/3blue1brown)

- ### Image Processing

- ### DevOps

  - **Community**
    - [DevOps, SRE, & Infrastructure](https://discord.com/invite/VEEnHkPzY6)

  - **CI/CD**
    - [CI/CD Full Course | Continuous Integration And Continuous](https://www.youtube.com/watch?v=h9K1NnqwUvE)
    - [GitLab CI CD Tutorial for Beginners](https://www.youtube.com/watch?v=qP8kir2GUgo)

- ### Hacking

  - **Book**
    - [Black Hat Python, 2nd Edition: Python Programming for Hackers and Pentesters](https://www.amazon.com/Black-Hat-Python-2nd-Programming/dp/1718501129)

- ### Algorithmic Trading

- ### Bot
  - #### Web

    - #### Selenium
      - [Selenium (Main Home)](https://github.com/SeleniumHQ/selenium)
      - [Source](https://github.com/SeleniumHQ/selenium/tree/trunk/py)
      - [Documentation](https://www.selenium.dev/selenium/docs/api/py/)
      - [Helium](https://github.com/mherrmann/selenium-python-helium)
      - [Base](https://github.com/seleniumbase/SeleniumBase)
      - [InstaPy](https://github.com/InstaPy/InstaPy)
      - [AutoCrawler](https://github.com/YoongiKim/AutoCrawler)
      - [Wire](https://github.com/wkeeling/selenium-wire)
      - [Cucucumber](https://github.com/executeautomation/SeleniumWithCucucumber)
      - [Requestium](https://github.com/tryolabs/requestium)
      - [Undetected](https://github.com/ultrafunkamsterdam/undetected-chromedriver)
  
  

    - #### Browser
      - [Source](https://wiki.mozilla.org/Auto-tools/Projects/Mozbase)
      - [Documentation](https://firefox-source-docs.mozilla.org/mozbase/index.html)
  
  
    - #### WebBot
      - [Source](https://github.com/nateshmbhat/webbot)
  
  
  - #### Telegram
    - #### Telethon
      - [Source](https://github.com/LonamiWebs/Telethon)
      - [Documentation](https://docs.telethon.dev/)
    
    - #### Pygram
      - [Source](https://github.com/pygram/pygram)
      - [Documentation](https://pygram.readthedocs.io/en/latest/)
    - #### Pyrogram
      - [Source](https://github.com/pyrogram/pyrogram)
      - [Documentation](https://docs.pyrogram.org/)
    
    - #### Python Telegram Bot
      - [Source](https://github.com/python-telegram-bot/python-telegram-bot)
      - [Documentation](https://python-telegram-bot.readthedocs.io/)
    
    - #### AIOGram
      - [Source](https://github.com/aiogram/aiogram)
      - [Documentation](https://docs.aiogram.dev/)
    
    - #### PyTelegramBotApi
      - [Source](https://github.com/eternnoir/pyTelegramBotAPI)
      - [Documentation](https://pytba.readthedocs.io/)
    
    - #### TeleBot
      - [Source](https://github.com/KyleJamesWalker/telebot)
  
  - #### Discord
    - #### DiscordPy
      - [Source](https://github.com/Rapptz/discord.py)
      - [Documentation](https://discordpy.readthedocs.io)

  - #### Instagram
    - #### Instagram-Scraper
      - [Source](https://github.com/realsirjoe/instagram-scraper)
    - #### InstaPy  
      - [Source](https://github.com/InstaPy/InstaPy)

## Advanced Topics

  ⚠️ The following topics don't have any order or priority of learning.\
  🔥 Choose topics that you are **interested in** or **suit your needs**.

- ### Databases

  - #### General
  
    - **Book**
      - ✅ [Designing Data-Intensive Applications: The Big Ideas Behind Reliable, Scalable, and Maintainable Systems](https://www.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable/dp/1449373321)
      - [Seven Databases in Seven Weeks: A Guide to Modern Databases and the NoSQL Movement](https://www.amazon.com/Seven-Databases-Weeks-Modern-Movement/dp/1680502530/)

  - #### SQLite
    
    - **Documentation**
      - [SQLite Documentation](https://www.sqlite.org/docs.html)
    
    - **Tutorials**
      - [SQLite Tutorial](https://www.sqlitetutorial.net/)

  - #### PostgreSQL
    
    - **Documentation**
      - [PostgreSQL Documentation](https://www.postgresql.org/docs/)
    
    - **Book**
      - [Essential Postgres: Database Development using PostgreSQL](https://www.amazon.com/Essential-Postgres-Database-Development-PostgreSQL/dp/B08KH136G4)

    - **Community**
      - [PostgreSQL Telegram group](https://t.me/pg_sql)
  
    - **Cheat Sheet**
      - [PostgreSQL Cheat Sheet By GoalKicker](https://books.goalkicker.com/PostgreSQLBook/PostgreSQLNotesForProfessionals.pdf)
      - [PostgreSQL CHEAT SHEET](https://www.postgresqltutorial.com/wp-content/uploads/2018/03/PostgreSQL-Cheat-Sheet.pdf)
      - [POSTGRESQL 8.3 PSQL CHEAT SHEET](http://www.postgresonline.com/downloads/special_feature/postgresql83_psql_cheatsheet.pdf)

  - #### MySQL
    
    - **Documentation**
      - [MySQL Documentation](https://dev.mysql.com/doc/)
    
    - **Tutorials**
      - [MySQL Tutorial](https://www.mysqltutorial.org/)

    - **Cheat Sheet**
      - [MySQL Cheat Sheet by GoalKicker](https://books.goalkicker.com/MySQLBook/MySQLNotesForProfessionals.pdf)

  - #### Oracle
    
    - **Documentation**
      - [Oracle Documentation](https://docs.oracle.com/en/database/index.html)
    
    - **Tutorials**
      - [Oracle Tutorial](https://www.oracletutorial.com/)

    - **Cheat Sheet**
      - [Oracle Cheat Sheet by GoalKicker](https://books.goalkicker.com/OracleDatabaseBook/OracleDatabaseNotesForProfessionals.pdf)

  - #### MongoDB

    - **Documentation**
      - [MongoDB Documentation](https://www.mongodb.com/docs/)
    
    - **Tutorial**
      - [Python MongoDB](https://www.w3schools.com/python/python_mongodb_getstarted.asp)

    - **Cheat Sheet**
      - [MongoDB Cheat Sheet by GoalKicker](https://books.goalkicker.com/MongoDBBook/MongoDBNotesForProfessionals.pdf)

  - #### Redis

    - **Documentation**
      - [Redis Documentation](https://redis.io/docs/)
    
    - **Video**
      - [Redis Crash Course 1](https://www.youtube.com/watch?v=Hbt56gFj998)
      - [Redis Crash Course 2](https://www.youtube.com/watch?v=OqCK95AS-YE)

    - **Article**
      - [How to use redis with python by Brad Solomon](https://realpython.com/python-redis/)

    - **Cheat Sheet**
      - [Redis Cheat Sheet 1](https://cheatography.com/tasjaevan/cheat-sheets/redis/)
      - [Redis Cheat Sheet 2](https://masonoise.files.wordpress.com/2010/03/redis-cheatsheet-v1.pdf)

  - #### MemCached

    - **Documentation**
      - [MemCached Wiki](https://github.com/memcached/memcached/wiki)

  - #### Apache Cassandra

    - **Documentation**
      - [Apache Cassandra Documentation](https://cassandra.apache.org/_/index.html)

- ### Clean Code

  - **Book**
    - ✅ [Clean Code: A Handbook of Agile Software Craftsmanship](https://www.amazon.com/gp/product/0132350882)
    - ✅ [Clean Code in Python by Mariano Anaya](https://www.amazon.com/Clean-Code-Python-maintainable-efficient/dp/1800560214)
    - [Code Complete: A Practical Handbook of Software Construction, Second Edition by Steve Mcconnell](https://www.amazon.com/Code-Complete-Practical-Handbook-Construction/dp/0735619670)

- ### Clean Architecture

  (In Progress)

- ### Caching

  - **Article**
    - [Caching in django with redis by Real Python](https://realpython.com/caching-in-django-with-redis/)

  - **Video**
    - [Redis Course - In-Memory Database Tutorial](https://www.youtube.com/watch?v=XCsS_NVAa1g)

- ### Testing

  - #### Python `unittest` package
  
    - **Documentation**
      - [Testing in Python](https://docs.python.org/3/library/unittest.html)
      - [Getting Started With Testing in Python](https://realpython.com/python-testing/)
  
  - #### `PyTest` Testing Package
    
    - **Documentation**
      - [Official PyTest Documentation](https://docs.pytest.org/en/stable/index.html)

  - #### DRF Test Framework

    - **Documentation**
      - [Testing - Django REST framework](https://www.django-rest-framework.org/api-guide/testing/)

    - **Video**
      - [Pytest Django and Django Rest Framework](https://www.youtube.com/watch?v=KIIdbVs7e8I&list=PLP1DxoSC17LZTTzgfq0Dimkm6eWJQC9ki)

- ### Container Platforms

  - #### Docker
  
    - **Documentation**
      - [Docker Documentation](https://docs.docker.com/)

    - **Book**
      - [Docker in Action, Second Edition](https://www.manning.com/books/docker-in-action-second-edition)
      - [Docker Deep Dive: Zero to Docker in a single book](https://www.amazon.com/Docker-Deep-Dive-Nigel-Poulton-ebook/dp/B01LXWQUFF)

    - **Video**
      - [Docker Mastery With Django - very academy](https://www.youtube.com/watch?v=W5Ov0H7E_o4&list=PLOLrQ9Pn6cazCfL7v4CdaykNoWMQymM_C)
      - [Docker Course by Mosh Hamedani](https://codewithmosh.com/p/the-ultimate-docker-course)
      - [Docker Swarm Step by Step](https://www.youtube.com/watch?v=74p7csxKN8M)

    - **Cheat Sheet**
      - [Docker Cheat Sheet](https://www.docker.com/wp-content/uploads/2022/03/docker-cheat-sheet.pdf)

  - #### Kubernetes
  
    - **Documentation**
      - [Kubernetes Documentation](https://kubernetes.io/docs/home/)

    - **Video**
      - ["Just me and Opensource" YouTube channel](https://www.youtube.com/playlist?list=PL34sAs7_26wNBRWM6BDhnonoA5FMERax0)

    - **Book**
      - [Kubernetes: Up and Running, 2nd Edition](https://www.oreilly.com/library/view/kubernetes-up-and/9781492046523)
      - [Kubernetes in Action, Second Edition](https://www.manning.com/books/kubernetes-in-action-second-edition)

    - **Community**
      - [Kubernetes Discord group](https://discord.gg/k8s-at-home)

- ### Programming Paradigms

  - #### Object-Oriented Programming

      - **Tutorial**
        - [Python Classes and Objects by W3Schools (Beginners)](https://www.w3schools.com/python/python_classes.asp)
        - [Python Object Oriented Programming by programiz.com (Beginners)](https://www.programiz.com/python-programming/object-oriented-programming)

      - **Article**
        - [Python OOPs Concepts 3 by GeeksForGeeks (Beginners)](https://www.geeksforgeeks.org/python-oops-concepts/)
        - [Object-Oriented Programming (OOP) in Python 3 by David Amos (Intermediate)](https://realpython.com/python3-object-oriented-programming/#:~:text=Programming%20with%20Python.-,What%20Is%20Object%2DOriented%20Programming%20in%20Python%3F,are%20bundled%20into%20individual%20objects.)

      - **Book**
        - [Python Object-Oriented Programming](https://www.amazon.com/Python-Object-Oriented-Programming-maintainable-object-oriented/dp/1789615852/ref=pd_sbs_sccl_2_2/138-1551814-9810765?pd_rd_w=jzyei&pf_rd_p=3676f086-9496-4fd7-8490-77cf7f43f846&pf_rd_r=MFK3P1Y675XM2K837YAX&pd_rd_r=392af586-64f4-4790-83f3-4b2ba1954b3d&pd_rd_wg=0Wk4G&pd_rd_i=1789615852&psc=1)

  - #### Functional Programming

    - **Article**
      - [Functional Programming in Python](https://realpython.com/python-functional-programming/)


- ### Architectural Patterns

  - #### Microservice

    - **Book**
      - [Microservice Architecture](https://www.oreilly.com/library/view/microservice-architecture/9781491956328)
      - [Building Microservices, 2nd Edition](https://www.oreilly.com/library/view/building-microservices-2nd/9781492034018/)

  - #### Enterprise Applications

    - **Book**
      - [Patterns of Enterprise Application Architecture](https://www.amazon.de/Patterns-Enterprise-Application-Architecture-Martin/dp/0321127420)
      - [Enterprise Integration Patterns: Designing, Building, and Deploying Messaging Solutions](https://www.amazon.de/-/en/Gregor-Hohpe/dp/0321200683/)

- ### Design Principles

  - #### SOLID

    - **Article**
        - [SOLID Principles In Python by Philip Norton](https://www.hashbangcode.com/article/solid-principles-python)
        - [Uncle Bob's SOLID principles made easy 🍀 - in Python!](https://www.youtube.com/watch?v=pTB30aXS77U)

  - #### KISS

  - #### DRY


- ### Design Patterns

  - **Book**
    - [Head First Design Patterns: Building Extensible and Maintainable Object-Oriented Software](https://www.amazon.com/Head-First-Design-Patterns-Object-Oriented/dp/149207800X)
    - [Django Design Patterns and Best Practices (by Arun Ravindran)](https://www.amazon.com/Django-Design-Patterns-Practices-Industry-standard/dp/1788831349)
    - [Dive Into Design Patterns by Alexander Shvets](https://refactoring.guru/design-patterns/book)

  - **Video**
    - [Design Patterns Course by Mosh Hamedani](https://codewithmosh.com/p/design-patterns)
    - [Become a better software developer](https://www.youtube.com/c/ArjanCodes)

- ### Message Brokers

  - #### RabbitMQ

    - **Documentation**
      - [RabbitMQ Documentation](https://www.rabbitmq.com/documentation.html)

    - **Article**
      - [RabbitMQ Hello World](https://www.rabbitmq.com/tutorials/tutorial-one-python.html)
      - [RabbitMQ Work Queues](https://www.rabbitmq.com/tutorials/tutorial-two-python.html)
      - [RabbitMQ Publish/Subscribe](https://www.rabbitmq.com/tutorials/tutorial-three-python.html)
      - [RabbitMQ Routing](https://www.rabbitmq.com/tutorials/tutorial-four-python.html)
      - [RabbitMQ Topics](https://www.rabbitmq.com/tutorials/tutorial-five-python.html)
      - [RabbitMQ Remote procedure call (RPC)](https://www.rabbitmq.com/tutorials/tutorial-six-python.html)

    - **Cheat Sheet**
      - [RabbitMQ Cheat Sheet 1](https://cheatography.com/francisuk/cheat-sheets/rabbitmq/pdf/)
      - [RabbitMQ Cheat Sheet 2](https://lzone.de/cheat-sheet/RabbitMQ)

  - #### Apache Kafka
 
    - **Documentation**
      - [Apache Kafka Documentation](https://kafka.apache.org/documentation/)

    - **Cheat Sheet**
      - [Apache Kafka Cheat Sheet 1](https://gist.github.com/sahilsk/d2a6ec384f5f2333e3fef40a581a97e1)
      - [Apache Kafka Cheat Sheet 2](https://medium.com/@TimvanBaarsen/apache-kafka-cli-commands-cheat-sheet-a6f06eac01b)

- ### WSGI Servers

  - #### Gunicorn
  
    - **Documentation**
      - [Gunicorn Documentation](https://docs.gunicorn.org/en/stable/)

  - #### uWSGI
  
    - **Documentation**
      - [uWSGI Documentation](https://uwsgi-docs.readthedocs.io/en/latest/)

- ### ASGI Servers

  - #### Uvicorn
  
    - **Documentation**
      - [Uvicorn Documentation](https://www.uvicorn.org/)
    
  - #### Starlette
  
    - **Documentation**
      - [Starlette Documentation](https://www.starlette.io/)

- ### Web Servers

  - #### Nginx
  
    - **Documentation**
      - [NGINX Documentation](http://nginx.org/en/docs/)

    - **Book**
      - [NGINX Cookbook](https://www.nginx.com/resources/library/complete-nginx-cookbook/)

    - **Cheat Sheet**
      - [NGINX CHEAT SHEET](https://kiza.dev/notes/nginx-cheat-sheet)

  - #### Apache
  
    - **Documentation**
      - [Apache Documentation](https://httpd.apache.org/docs/)

    - **Book**
      - [Apache Cookbook: Solutions and Examples for Apache Administrators](https://www.amazon.com/Apache-Cookbook-Solutions-Examples-Administrators/dp/0596529945)

    - **Cheat Sheet**
      - [Apache Cheat Sheet](http://www.cheat-sheets.org/saved-copy/apache-refcard-a4.pdf)

- ### API

  - #### Design
  
    - **Guidelines and Best Practices**
      - [Zalando RESTful API and Event Guidelines](https://opensource.zalando.com/restful-api-guidelines/)
      - [Microsoft REST API Guidelines](https://github.com/microsoft/api-guidelines)

  - #### Security

    - **Checklist**
      - [API Security Checklist](https://github.com/bobycloud/API-Security-Checklist/blob/master/README-en.md)

- ### Availability and Reliability

  (In Progress)

- ### Distributed Systems

  (In Progress)

- ### Reactive Systems

  (In Progress)

- ### Refactoring

  - **Video**
    - [Dive Into REFACTORING](https://refactoring.guru/refactoring/course)

- ### Security

  - **Book**
    - [The Web Application Hacker's Handbook](https://www.amazon.com/Web-Application-Hackers-Handbook-Exploiting/dp/1118026470)
    - [Application_Security_Program_Handbook - a guide for software engineers](https://www.mysterylovescompany.com/book/9781633439818)
    - [Designing secure software - a guide for devlopers](https://www.amazon.com/Designing-Secure-Software-Guide-Developers/dp/1718501927)
    - [Hacking APIs Breaking Web Application Programming Interfaces](https://www.amazon.com/Hacking-APIs-Application-Programming-Interfaces/dp/1718502443)
    - [Web Application Security Exploitation and Countermeasures for Modern Web Applications](https://www.amazon.com/Web-Application-Security-Exploitation-Countermeasures/dp/1492053112)
    - [Web Security for Developers: Real Threats, Practical Defense](https://www.amazon.com/Web-Security-Developers-Malcolm-McDonald/dp/1593279949)
    - [Mastering Modern Web Penetration Testing](https://www.amazon.com/Mastering-Modern-Web-Penetration-Testing/dp/1785284584)
  
  - **WebSite**
    - [OWASP Top 10](https://owasp.org/www-project-top-ten/)
    - [OWASP Top 10 for Web with live training](https://application.security/free/owasp-top-10)
    - [SANS SWAT Checklist](https://www.sans.org/cloud-security/securing-web-application-technologies/)

- ### Monitoring
  
  (In Progress)

- ### Soft Skill

  - **Book**
    - [The Clean Coder: A Code of Conduct for Professional Programmers](https://www.amazon.com/Clean-Coder-Conduct-Professional-Programmers/dp/0137081073)

- ### Public Cloud

  (In Progress)
  
- ### IoT

    - #### Concept
    - #### Protocol
      - [Practical MQTT with Steve](http://www.steves-internet-guide.com/)

##### [BACK TO TOP](#top)
