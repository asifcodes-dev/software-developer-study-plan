# Software Developer Study Plan (Basic to Advanced)

**Pace:** 30 minutes a day on weekdays, 1 hour a day on weekends (4.5 hours a week)  
**Shape:** 45 weeks of core for everyone, then **one track** you pick, plus DSA every weekend  
**Built from:** the files in this Study Material folder. Every PDF is used somewhere below.  
**Web version:** [Software_Developer_Study_Plan.html](Software_Developer_Study_Plan.html) (with ticks, course pages and a track picker)

## At a glance

| Part | What | Weeks | Total time |
|---|---|---|---|
| Core (everyone) | Programming foundations → Java & Python → CS fundamentals → Engineering practice → System design & interviews | 1–45 | about 10 months |
| Track A: Full stack web | Build web apps end to end | 46–79 (34 weeks) | about 18 months |
| Track B: QA / SDET automation | Test and automate software | 46–62 (17 weeks) | about 14 months |
| Track C: DevOps & cloud | Run software in production | 46–62 (17 weeks) | about 14 months |
| Track D: AI / ML engineer | Work with data and models | 46–66 (21 weeks) | about 15 months |
| Every weekend | DSA practice | 1 to the end | — |
| Optional | CS theory, embedded, graphics | any time | — |

**Daily routine:** read your notes for the step, then build the step's project. Commit to GitHub every day.  
**Weekly routine:** Saturday and Sunday include DSA problems; Sunday ends with a self-test from `600 + questions`.

---

## Part 1 — Core (weeks 1–45)

### Core 1 — Programming foundations (Weeks 1–6)

Learn how code works with C, then the terminal and Git you'll use every day.

| Step | Weeks | Topics | Your files | Build |
|---|---|---|---|---|
| 1 | 1–3 | C programming: variables, loops, functions, arrays, strings, pointers, structs, memory | `Crafted_Note Cprogramming` | Solve 20 basic problems in C (patterns, primes, arrays) |
| 2 | 4–6 | Linux commands, file permissions, processes; Git: commit, branch, merge, rebase, GitHub | `Linux pdf`, `Git Notes`, `Git top 20 concepts`, `Git interview` | Create a GitHub repo and push all your C programs |

### Core 2 — Java & Python (Weeks 7–20)

Java is your main language (your strongest notes). Python is the second, for scripts, testing and AI.

| Step | Weeks | Topics | Your files | Build |
|---|---|---|---|---|
| 3 | 7–10 | Java basics and OOP: classes, inheritance, polymorphism, abstraction, interfaces, exceptions | `Java complete`, `Java Interface Abstraction`, `50 Oops question`, `Java Star Pattern` | Bank account console app |
| 4 | 11–14 | Collections, HashMap internals, generics, Streams, lambdas, Optional | `Collections`, `Java collection Shortcuts`, `Java Stream and Lambda expressions`, `Java Tricky` | Student records manager using Streams |
| 5 | 15–17 | JVM memory, garbage collection, multithreading, SOLID, design patterns | `JEV Model`, `SOLID Principle` | Refactor the bank app with SOLID and add a multithreaded report |
| 6 | 18–20 | Python: syntax, lists, dicts, functions, OOP, files, pattern programs | `Python cheat sheet`, `Python Quick Notes`, `Python sheet 2`, `Python part 3`, `Python Pattern` | Script that sorts the files in a folder by type |

### Core 3 — CS fundamentals (Weeks 21–31)

Operating systems, databases and networks. Asked in almost every campus and product-company interview.

| Step | Weeks | Topics | Your files | Build |
|---|---|---|---|---|
| 7 | 21–23 | Operating systems: processes, threads, scheduling, deadlocks, memory and paging | `Crafted_Note Operating system` | A Java demo of threads and a deadlock, with notes on why it happens |
| 8 | 24–26 | SQL: SELECT, JOINs, GROUP BY, subqueries, CTEs, window functions | `Sql Sheet`, `Sql cheat sheet`, `Sql important cheat sheet`, `Sql part 2`, `Advance SQL concepts` | Solve 30 problems from LeetCode SQL 50 |
| 9 | 27–28 | DBMS: ER model, normalization, ACID, transactions, indexing, PostgreSQL | `DBMS`, `Crafted_Note Dbms`, `ACID properties`, `Db indexing`, `PostgreSql` | ER diagram and schema for a library system |
| 10 | 29–31 | Networks: OSI and TCP/IP, HTTP, DNS, TLS, network security basics | `Computer Networks notes 1`, `Network security` | Trace a web request in browser dev tools and explain each step |

### Core 4 — Engineering practice (Weeks 32–38)

How real teams build software: APIs, testing, Agile and containers.

| Step | Weeks | Topics | Your files | Build |
|---|---|---|---|---|
| 11 | 32–33 | REST APIs: methods, status codes, JSON, testing with Postman | `Rest Api`, `Postman Notes` | A Postman collection that tests a public API |
| 12 | 34–35 | Testing basics: test cases, test levels, bug life cycle, unit tests with JUnit | `Manual testing` | Test cases and JUnit tests for the bank app |
| 13 | 36 | Agile, Scrum, Jira boards and sprints; Excel for reports | `Jira notes`, `Excel` | Plan your next 4 weeks as a Jira board |
| 14 | 37–38 | Docker: images, containers, Dockerfile, volumes, docker-compose | `Docker notes`, `Docker Revision notes`, `Docker top 10 concept` | Run your Java app in a Docker container |

### Core 5 — System design & interviews (Weeks 39–45)

Design at scale, then prepare for interviews and aptitude tests.

| Step | Weeks | Topics | Your files | Build |
|---|---|---|---|---|
| 15 | 39–42 | System design: scalability, load balancing, caching, sharding, CAP, microservices, queues | `System design part 1`, `System design part 2`, `System Design 1.png`, `System design 2.png` | Draw designs for a URL shortener and Zomato |
| 16 | 43–45 | Interview revision with 600+ questions; aptitude: time and work, ratio, TCS NQT | `Time & Work`, `Time_and_Work_50_Questions_with_Solutions-1`, `Ratio & Proportion`, `Top 40 TCS NQT problems` | One timed aptitude test and one mock interview each week |

> **Checkpoint:** Core done: you are ready for junior developer interviews. Now pick your track.

---

## Part 2 — Pick one track (starts week 46)

Choose the job you want. Do only that track's steps; the others are optional later.

### Track A — Full stack web (weeks 46–79, about 18 months in total)

*Build web apps end to end.* Frontend, backend and deployment. For the deepest version, see Full_Stack_Study_Plan.html.

**You will have built:**
- A React + Spring Boot + PostgreSQL app with JWT login
- The same API in Node.js + Express
- Deployed on AWS with CI/CD

| Step | Weeks | Topics | Your files | Build |
|---|---|---|---|---|
| A1 | 46–49 | HTML semantics, forms, accessibility; CSS box model, Flexbox, Grid, responsive design | `HTML_CSS_Interview_Questions` | Responsive landing page |
| A2 | 50–55 | JavaScript: closures, this, ES6+, DOM, events, event loop, promises, fetch | `Java script 2`, `JavaScript_Interview_Questions` | Todo app and weather app |
| A3 | 56–57 | TypeScript: types, interfaces, generics, narrowing, utility types | `Typescript`, `Typescript 2` | Convert the weather app to TypeScript |
| A4 | 58–63 | React: components, props, state, hooks, router, data fetching | `Top 30 ReachJs question`, `React_NodeJS_Interview` | Dashboard in React + TypeScript |
| A5 | 64–69 | Spring Boot: DI, REST controllers, JPA, Spring Security, JWT | `Spring boot 30 concepts`, `SpringBoot_Interview_Questions` | REST API with PostgreSQL and JWT login, used by your React app |
| A6 | 70–72 | MongoDB documents and aggregation; Redis caching and TTL | `Mongo db`, `Redis` | Cache your API with Redis |
| A7 | 73–75 | Node.js + Express: event loop, middleware, REST, Mongoose | `NodeJs` | Rebuild the API in Express + MongoDB |
| A8 | 76–79 | Deploy: AWS EC2, RDS, S3; GitHub Actions CI/CD | `Aws notes`, `Cloud computing` | Deploy the full stack app on AWS with a CI/CD pipeline |

### Track B — QA / SDET automation (weeks 46–62, about 14 months in total)

*Test and automate software.* Your folder is strong here: Selenium, Playwright, Rest Assured, Postman and performance testing notes.

**You will have built:**
- Selenium and Playwright UI test suites
- A REST Assured API test suite
- Load tests and tests running in CI

| Step | Weeks | Topics | Your files | Build |
|---|---|---|---|---|
| B1 | 46–49 | Selenium WebDriver: locators, waits, page object model, TestNG | `Selenium`, `Selenium_Interview_Questions` | Automate login and search on a demo site |
| B2 | 50–53 | Playwright: locators, auto-waiting, fixtures, tracing, parallel runs | `Playwright`, `Playwright cheat sheet`, `Playwright_Interview_Questions` | Playwright suite with page objects and reports |
| B3 | 54–56 | API automation with REST Assured: requests, assertions, auth, JSON schema | `Rest Assured`, `REST_Assured_Interview_Questions`, `Postman Notes` | API test suite for a public API |
| B4 | 57–58 | Performance testing: load, stress, spike tests, metrics, JMeter or k6 | `Performance Testing Notes` | Load test an API and report response times |
| B5 | 59–60 | Run tests in CI: GitHub Actions, reports, test data | — | Run your UI and API suites on every push |
| B6 | 61–62 | AI for testers: generating test cases, test data and reviewing failures with AI | `AI for Testers` | Use an AI tool to draft and review test cases |

### Track C — DevOps & cloud (weeks 46–62, about 14 months in total)

*Run software in production.* Networking, containers, Kubernetes, AWS and pipelines.

**You will have built:**
- Apps running on Kubernetes
- An AWS deployment with load balancing
- CI/CD pipelines and a Kafka setup

| Step | Weeks | Topics | Your files | Build |
|---|---|---|---|---|
| C1 | 46–48 | Advanced networking: subnetting, routing, switching, VLANs, firewalls (CCNP notes) | `CCNP notes`, `Network security` | Subnet a network for a small office on paper |
| C2 | 49–52 | Kubernetes: pods, deployments, services, ingress, ConfigMaps, Helm | `Kubernates Notes` | Run your Dockerized app on minikube |
| C3 | 53–57 | AWS and cloud: EC2, S3, RDS, IAM, VPC, load balancers, auto scaling, Lambda | `Aws notes`, `Cloud computing` | Deploy an app on AWS behind a load balancer |
| C4 | 58–59 | CI/CD: GitHub Actions pipelines, secrets, Docker image builds | — | Pipeline that builds, tests and deploys on every push |
| C5 | 60–62 | Kafka, RabbitMQ, Elasticsearch and Redis in production | `Kafka cheat sheet`, `Kafka RabitMQ`, `Elastic search`, `Redis` | Run Kafka with docker-compose and send events between two services |

### Track D — AI / ML engineer (weeks 46–66, about 15 months in total)

*Work with data and models.* Uses your maths, ML, deep learning, data mining and GenAI notes.

**You will have built:**
- Classic ML models on Kaggle datasets
- A deep learning image or text model
- A RAG app with a vector database

| Step | Weeks | Topics | Your files | Build |
|---|---|---|---|---|
| D1 | 46–50 | Maths for ML: linear algebra, calculus, limits, integrals, probability basics | `Linear algebra notes`, `Calculus Notes`, `Calculus`, `Limit Continuity`, `Integral top 15`, `Crafted_Note Mathematics part1` | Implement vectors, matrix multiply and gradient descent in Python |
| D2 | 51–55 | Machine learning: regression, classification, trees, clustering, evaluation | `Machine Learning` | Train and compare models on a Kaggle dataset |
| D3 | 56–57 | Data mining: preprocessing, association rules, clustering, pandas | `Crafted_Note Data Mining` | Clean and analyse a real dataset with pandas |
| D4 | 58–62 | Deep learning: neural networks, backprop, CNNs, RNNs, transformers | `Crafted_Note Deep Learning Part 1`, `Deep Learning Part 3` | Image or text classifier in PyTorch |
| D5 | 63–66 | GenAI: LLM APIs, prompting, embeddings, vector databases, RAG, agents, MCP | `GenAi`, `AI Agent For Developers`, `Mcp for dev`, `Vector database notes`, `Ai handbook` | RAG app that answers questions from your own PDFs |

---

## Every weekend — DSA

30 minutes on Saturday and Sunday, from week 1 to the end. Follow the DSASheet order on LeetCode or GeeksforGeeks.

| Weeks | Topic | Your files |
|---|---|---|
| 1–20 | Time complexity, arrays, strings, patterns | `Time complexity`, `Array & String problems`, `Java Star Pattern` |
| 21–35 | Recursion, sorting, searching, two pointers, hashing | `Recursion`, `Sorting And Searching`, `Coding Pattern` |
| 36–45 | Stack, queue, linked list, trees | `Stack & Quoue`, `Tree & Graph` |
| 46–end of your track | Graphs, heaps, dynamic programming, greedy, backtracking; then mixed practice | `Tree and Graph`, `DSASheet`, `70 DSA Java Interview Solutions` |

## Optional side tracks

For GATE, college exams or curiosity. Not needed for developer jobs.

- **[CS theory for GATE](#cs-theory-for-gate):** Theory of computation, compiler design and discrete maths. Needed for GATE and exams, rarely for jobs. Files: `TheoryOfComputation Part-1`, `Crafted_Note CompilerDesign`, `Crafted_Note Discrete Mathematics Part2`
- **[Digital electronics & embedded](#digital-electronics--embedded):** Logic gates up to microprocessors and IoT boards. Fun projects, mostly for ECE or IoT roles. Files: `Crafted_Note Digital`, `Digital Project Ideas`, `8086 project ideas`, `ESP32 & LoRa project`
- **[Computer graphics](#computer-graphics):** How shapes and images are drawn on screen: transforms, projections and rendering. Files: `Crafted_Note ComputerGraphics`

---

## Part 3 — Course details

Each course lists its topics (required or optional, and whether your folder covers them), your files and the best outside sources.

Legend: **In your notes** = covered by your PDFs · **Q&A only** = only in interview question files · **Not in folder** = use the sources listed.

### Core 1 — Programming foundations

#### C programming

**Required** · Basic

Your first language for understanding how programs use memory. Pointers and arrays here make every other language easier.

| Topic | Required? | Coverage |
|---|---|---|
| Variables, data types, operators | Required | In your notes |
| Conditions and loops | Required | In your notes |
| Functions and recursion | Required | In your notes |
| Arrays and strings | Required | In your notes |
| Pointers | Required | In your notes |
| Structures and unions | Required | In your notes |
| Dynamic memory (malloc, free) | Required | In your notes |
| File handling | Optional | In your notes |
| Preprocessor and macros | Optional | In your notes |

**Your notes:** `Crafted_Note Cprogramming`  
**Interview Q&A:** —

**Best sources:**
- Course: [CS50x (Harvard)](https://cs50.harvard.edu/x/) — The best intro to programming, starts in C
- Book: [Beej's Guide to C](https://beej.us/guide/bgc/) — Free
- Practice: [HackerRank C](https://www.hackerrank.com/domains/c)

#### Linux & command line

**Required** · Basic

Use the terminal to move around files, run programs and manage servers.

| Topic | Required? | Coverage |
|---|---|---|
| Files, folders and navigation | Required | In your notes |
| File permissions | Required | In your notes |
| Processes and signals | Required | In your notes |
| Pipes, grep, find | Required | In your notes |
| Environment variables | Required | In your notes |
| SSH | Required | In your notes |
| Shell scripting | Optional | In your notes |
| Cron jobs | Optional | In your notes |

**Your notes:** `Linux pdf`  
**Interview Q&A:** —

**Best sources:**
- Course: [Linux Journey](https://linuxjourney.com) — Short lessons
- Book: [The Linux Command Line](https://linuxcommand.org/tlcl.php) — Free PDF
- Practice: [OverTheWire: Bandit](https://overthewire.org/wargames/bandit/) — Learn by solving levels

#### Git & GitHub

**Required** · Basic

Track every change to your code and collaborate through pull requests.

| Topic | Required? | Coverage |
|---|---|---|
| init, add, commit, log | Required | In your notes |
| Branching | Required | In your notes |
| Merge vs rebase | Required | In your notes |
| Resolving conflicts | Required | In your notes |
| Push, pull, fetch | Required | In your notes |
| Pull requests | Required | In your notes |
| Reset vs revert | Required | In your notes |
| Stash and cherry-pick | Optional | In your notes |

**Your notes:** `Git Notes`, `Git top 20 concepts`, `Git interview`  
**Interview Q&A:** `Git_GitHub_Interview_Questions`

**Best sources:**
- Practice: [Learn Git Branching](https://learngitbranching.js.org) — Visual and interactive
- Book: [Pro Git](https://git-scm.com/book) — Chapters 1–3 to start
- Course: [GitHub Skills](https://skills.github.com)

### Core 2 — Java & Python

#### Java

**Required** · Basic · Learn first: [C programming](#c-programming)

Your main language. Strong typing, OOP and a huge job market in India and abroad.

| Topic | Required? | Coverage |
|---|---|---|
| Syntax and control flow | Required | In your notes |
| Classes and objects | Required | In your notes |
| Inheritance and polymorphism | Required | In your notes |
| Abstraction and interfaces | Required | In your notes |
| Exception handling | Required | In your notes |
| Strings | Required | In your notes |
| Collections and HashMap internals | Required | In your notes |
| Generics | Required | In your notes |
| Streams and lambdas | Required | In your notes |
| JVM memory model | Required | In your notes |
| Multithreading | Required | In your notes |
| Garbage collection | Optional | In your notes |
| Pattern programs | Optional | In your notes |

**Your notes:** `Java complete`, `Collections`, `Java collection Shortcuts`, `Java Stream and Lambda expressions`, `Java Tricky`, `JEV Model`, `Java Interface Abstraction`, `Java Star Pattern`  
**Interview Q&A:** `Java_Interview_Questions`

**Best sources:**
- Course: [MOOC.fi Java Programming](https://java-programming.mooc.fi) — University of Helsinki, many exercises
- Docs: [dev.java/learn](https://dev.java/learn/) — Official
- Docs: [Baeldung](https://www.baeldung.com) — Quick answers on any Java topic

#### OOP & design principles

**Required** · Intermediate · Learn first: [Java](#java)

Structure code so it stays easy to change: the four pillars, SOLID and design patterns.

| Topic | Required? | Coverage |
|---|---|---|
| Four pillars of OOP | Required | In your notes |
| SOLID principles | Required | In your notes |
| Design patterns: Singleton, Factory, Builder, Strategy | Required | Not in folder |
| Clean code | Optional | Not in folder |
| UML class diagrams | Optional | Not in folder |

**Your notes:** `SOLID Principle`, `50 Oops question`  
**Interview Q&A:** —

**Best sources:**
- Docs: [Refactoring.Guru: design patterns](https://refactoring.guru/design-patterns) — With diagrams
- Docs: [Baeldung: SOLID](https://www.baeldung.com/solid-principles)
- Book: [Head First Design Patterns](https://www.oreilly.com/library/view/head-first-design/9781492077992/) — Paid

#### Python

**Required** · Basic · Learn first: [C programming](#c-programming)

A second language for scripts, automation, testing and AI. Quick to write and read.

| Topic | Required? | Coverage |
|---|---|---|
| Syntax and data types | Required | In your notes |
| Lists, dicts, sets, tuples | Required | In your notes |
| Functions and modules | Required | In your notes |
| OOP in Python | Required | In your notes |
| File handling | Required | In your notes |
| Exceptions | Required | In your notes |
| List comprehensions | Required | In your notes |
| Pattern programs | Optional | In your notes |
| Virtual environments and pip | Optional | Not in folder |

**Your notes:** `Python cheat sheet`, `Python cheat Sheet notes`, `Python Quick Notes`, `Python sheet 2`, `Python part 3`, `Python Pattern`  
**Interview Q&A:** `Python_Interview_Questions`

**Best sources:**
- Course: [Python for Everybody](https://www.py4e.com) — Free, beginner friendly
- Docs: [Official Python tutorial](https://docs.python.org/3/tutorial/)
- Book: [Automate the Boring Stuff](https://automatetheboringstuff.com) — Free online

### Core 3 — CS fundamentals

#### Operating systems

**Required** · Intermediate · Learn first: [C programming](#c-programming)

How the computer runs your programs: processes, threads, memory and deadlocks.

| Topic | Required? | Coverage |
|---|---|---|
| Processes vs threads | Required | In your notes |
| CPU scheduling | Required | In your notes |
| Synchronization, mutex, semaphore | Required | In your notes |
| Deadlocks | Required | In your notes |
| Memory management and paging | Required | In your notes |
| Virtual memory | Required | In your notes |
| File systems | Optional | In your notes |

**Your notes:** `Crafted_Note Operating system`  
**Interview Q&A:** —

**Best sources:**
- Video: [Gate Smashers OS (YouTube)](https://www.youtube.com/@GateSmashers) — Hindi, exam style
- Book: [Operating Systems: Three Easy Pieces](https://pages.cs.wisc.edu/~remzi/OSTEP/) — Free

#### SQL

**Required** · Basic

Ask questions of relational data. Joins, grouping and window functions come up in almost every interview.

| Topic | Required? | Coverage |
|---|---|---|
| SELECT, WHERE, ORDER BY | Required | In your notes |
| JOINs | Required | In your notes |
| GROUP BY and HAVING | Required | In your notes |
| Subqueries | Required | In your notes |
| CTEs | Required | In your notes |
| Window functions | Required | In your notes |
| Views | Optional | In your notes |
| Stored procedures and triggers | Optional | In your notes |

**Your notes:** `Sql Sheet`, `Sql cheat sheet`, `Sql important cheat sheet`, `Sql part 2`, `Copy of Sql part 2`, `Advance SQL concepts`  
**Interview Q&A:** `SQL_Interview_Questions`

**Best sources:**
- Practice: [SQLBolt](https://sqlbolt.com) — Interactive basics
- Practice: [LeetCode SQL 50](https://leetcode.com/studyplan/top-sql-50/) — Interview practice
- Course: [Mode SQL tutorial](https://mode.com/sql-tutorial/) — Window functions

#### DBMS

**Required** · Intermediate · Learn first: [SQL](#sql)

The theory behind databases: normalization, transactions, ACID and indexing.

| Topic | Required? | Coverage |
|---|---|---|
| ER model | Required | In your notes |
| Keys and constraints | Required | In your notes |
| Normalization | Required | In your notes |
| ACID properties | Required | In your notes |
| Transactions and isolation levels | Required | In your notes |
| Indexing | Required | In your notes |
| Query optimization | Optional | In your notes |
| PostgreSQL basics | Required | In your notes |

**Your notes:** `DBMS`, `Crafted_Note Dbms`, `ACID properties`, `Db indexing`, `PostgreSql`  
**Interview Q&A:** —

**Best sources:**
- Video: [Gate Smashers DBMS (YouTube)](https://www.youtube.com/@GateSmashers)
- Docs: [Use The Index, Luke](https://use-the-index-luke.com) — Indexing
- Docs: [PostgreSQL tutorial](https://www.postgresql.org/docs/current/tutorial.html)

#### Computer networks

**Required** · Intermediate

How data moves between computers: the layers, the protocols, and how the web works on top of them.

| Topic | Required? | Coverage |
|---|---|---|
| OSI and TCP/IP models | Required | In your notes |
| IP addressing | Required | In your notes |
| TCP vs UDP | Required | In your notes |
| HTTP and HTTPS | Required | In your notes |
| DNS | Required | In your notes |
| TLS | Required | In your notes |
| Network security basics | Required | In your notes |
| Firewalls | Optional | In your notes |

**Your notes:** `Computer Networks notes 1`, `Network security`  
**Interview Q&A:** —

**Best sources:**
- Video: [Gate Smashers Computer Networks (YouTube)](https://www.youtube.com/@GateSmashers)
- Docs: [Cloudflare Learning Center](https://www.cloudflare.com/learning/) — DNS, CDN and TLS explained simply
- Docs: [MDN: How the web works](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Web_standards/How_the_web_works)

### Core 4 — Engineering practice

#### REST APIs & Postman

**Required** · Intermediate · Learn first: [Computer networks](#computer-networks)

How programs talk to each other over HTTP, and how to test those APIs in Postman.

| Topic | Required? | Coverage |
|---|---|---|
| REST principles | Required | In your notes |
| HTTP methods | Required | In your notes |
| Status codes | Required | In your notes |
| JSON | Required | In your notes |
| Idempotency | Required | In your notes |
| Postman collections and environments | Required | In your notes |
| OpenAPI / Swagger | Optional | Not in folder |

**Your notes:** `Rest Api`, `Postman Notes`  
**Interview Q&A:** —

**Best sources:**
- Docs: [MDN HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP) — Methods and status codes
- Docs: [restfulapi.net](https://restfulapi.net)
- Course: [Postman Learning Center](https://learning.postman.com)

#### Software testing basics

**Required** · Basic · Learn first: [Java](#java)

Every developer tests. Learn test cases, test levels and how to write unit tests.

| Topic | Required? | Coverage |
|---|---|---|
| SDLC and STLC | Required | In your notes |
| Test cases and test plans | Required | In your notes |
| Test levels and types | Required | In your notes |
| Bug life cycle | Required | In your notes |
| Unit testing with JUnit | Required | Not in folder |
| Mocking with Mockito | Optional | Not in folder |
| TDD | Optional | Not in folder |

**Your notes:** `Manual testing`  
**Interview Q&A:** —

**Best sources:**
- Docs: [ISTQB Foundation syllabus](https://www.istqb.org/certifications/certified-tester-foundation-level-ctfl-v4-0/) — Testing vocabulary
- Docs: [JUnit 5 user guide](https://junit.org/junit5/docs/current/user-guide/)
- Docs: [Mockito](https://site.mockito.org)

#### Agile, Jira & Excel

**Required** · Basic

How software teams plan work in sprints, track it in Jira and report it in Excel.

| Topic | Required? | Coverage |
|---|---|---|
| Agile and Scrum | Required | In your notes |
| User stories and sprints | Required | In your notes |
| Jira boards and workflows | Required | In your notes |
| Excel formulas and pivots | Optional | In your notes |

**Your notes:** `Jira notes`, `Excel`  
**Interview Q&A:** —

**Best sources:**
- Docs: [Atlassian Agile Coach](https://www.atlassian.com/agile)
- Docs: [The Scrum Guide](https://scrumguides.org/scrum-guide.html)
- Course: [Microsoft Excel training](https://support.microsoft.com/en-us/excel)

#### Docker

**Required** · Intermediate · Learn first: [Linux & command line](#linux--command-line)

Package an app and everything it needs into a container that runs the same everywhere.

| Topic | Required? | Coverage |
|---|---|---|
| Images and containers | Required | In your notes |
| Dockerfile | Required | In your notes |
| Volumes | Required | In your notes |
| Networks | Required | In your notes |
| docker-compose | Required | In your notes |
| Docker Hub | Required | In your notes |
| Multi-stage builds | Optional | In your notes |

**Your notes:** `Docker notes`, `Docker Revision notes`, `Docker top 10 concept`  
**Interview Q&A:** `Docker_Interview_Questions`

**Best sources:**
- Docs: [Docker get started](https://docs.docker.com/get-started/)
- Video: [TechWorld with Nana (YouTube)](https://www.youtube.com/@TechWorldwithNana)
- Practice: [Play with Docker](https://labs.play-with-docker.com) — In the browser

### Core 5 — System design & interviews

#### System design

**Required** · Advanced · Learn first: [DBMS](#dbms), [Computer networks](#computer-networks), [Docker](#docker)

Design apps that serve millions of users: load balancers, caches, queues, sharding and microservices.

| Topic | Required? | Coverage |
|---|---|---|
| Vertical vs horizontal scaling | Required | In your notes |
| Load balancing | Required | In your notes |
| Caching and CDN | Required | In your notes |
| Replication and sharding | Required | In your notes |
| CAP theorem | Required | In your notes |
| Microservices vs monolith | Required | In your notes |
| API gateway and rate limiting | Required | In your notes |
| Message queues | Required | In your notes |
| Case study: Zomato | Required | In your notes |
| Case study: URL shortener | Required | Q&A only |

**Your notes:** `System design part 1`, `System design part 2`, `System Design 1.png`, `System design 2.png`  
**Interview Q&A:** `System_Design_Interview_Questions`

**Best sources:**
- Docs: [System Design Primer](https://github.com/donnemartin/system-design-primer)
- Video: [ByteByteGo (YouTube)](https://www.youtube.com/@ByteByteGo) — Short visual explainers
- Course: [Hello Interview: system design](https://www.hellointerview.com/learn/system-design)
- Book: [Designing Data-Intensive Applications](https://dataintensive.net) — Paid

#### Interview preparation

**Required** · Intermediate · Learn first: [Java](#java), [DSA](#dsa)

Revise every topic with your 600+ questions and practise explaining answers out loud.

| Topic | Required? | Coverage |
|---|---|---|
| Core Java questions | Required | Q&A only |
| OOP questions | Required | Q&A only |
| SQL and DBMS questions | Required | Q&A only |
| DSA questions | Required | Q&A only |
| Git and Docker questions | Required | Q&A only |
| System design questions | Required | Q&A only |
| Track-specific questions | Required | Q&A only |
| HR and behavioural questions | Required | Not in folder |
| Mock interviews | Required | Not in folder |

**Your notes:** —  
**Interview Q&A:** `Java_Interview_Questions`, `Python_Interview_Questions`, `SQL_Interview_Questions`, `DSA_Interview_Questions`, `70 DSA Java Interview Solutions`, `Git_GitHub_Interview_Questions`, `Docker_Interview_Questions`, `System_Design_Interview_Questions`, `HTML_CSS_Interview_Questions`, `JavaScript_Interview_Questions`, `React_NodeJS_Interview`, `SpringBoot_Interview_Questions`, `Selenium_Interview_Questions`, `Playwright_Interview_Questions`, `REST_Assured_Interview_Questions`, `50 Oops question`, `Java Tricky`, `Top 30 ReachJs question`

**Best sources:**
- Docs: [Tech Interview Handbook](https://www.techinterviewhandbook.org) — Free
- Practice: [Pramp](https://www.pramp.com) — Free mock interviews
- Practice: [InterviewBit](https://www.interviewbit.com)

#### Aptitude & placement tests

**Required** · Basic

Quantitative aptitude for TCS NQT and other campus tests: time and work, ratios and timed problems.

| Topic | Required? | Coverage |
|---|---|---|
| Time and work | Required | In your notes |
| Ratio and proportion | Required | In your notes |
| Percentages and profit and loss | Required | Not in folder |
| Speed, time and distance | Required | Not in folder |
| TCS NQT coding problems | Required | In your notes |
| Logical reasoning | Optional | Not in folder |
| Verbal ability | Optional | Not in folder |

**Your notes:** `Time & Work`, `Time_and_Work_50_Questions_with_Solutions-1`, `Ratio & Proportion`, `Top 40 TCS NQT problems`  
**Interview Q&A:** —

**Best sources:**
- Practice: [IndiaBIX aptitude](https://www.indiabix.com/aptitude/questions-and-answers/)
- Practice: [PrepInsta TCS NQT](https://prepinsta.com/tcs-nqt/)

### Every weekend

#### DSA

**Required** · Basic

Problem solving with data structures and algorithms. The main filter in coding interviews, so practise every weekend.

| Topic | Required? | Coverage |
|---|---|---|
| Time and space complexity | Required | In your notes |
| Arrays and strings | Required | In your notes |
| Recursion | Required | In your notes |
| Sorting and searching | Required | In your notes |
| Two pointers and sliding window | Required | In your notes |
| Hashing | Required | In your notes |
| Stack and queue | Required | In your notes |
| Linked list | Required | In your notes |
| Trees and BST | Required | In your notes |
| Heaps | Required | In your notes |
| Graphs: BFS, DFS, shortest path | Required | In your notes |
| Dynamic programming | Required | In your notes |
| Greedy | Optional | In your notes |
| Backtracking | Optional | In your notes |

**Your notes:** `DSASheet`, `Time complexity`, `Array & String problems`, `Recursion`, `Sorting And Searching`, `Stack & Quoue`, `Tree & Graph`, `Tree and Graph`, `Coding Pattern`  
**Interview Q&A:** `70 DSA Java Interview Solutions`, `DSA_Interview_Questions`

**Best sources:**
- Course: [Striver's A2Z DSA sheet](https://takeuforward.org/strivers-a2z-dsa-course/strivers-a2z-dsa-course-sheet-2) — Videos for every topic
- Course: [NeetCode roadmap](https://neetcode.io/roadmap)
- Practice: [LeetCode](https://leetcode.com)
- Practice: [VisuAlgo](https://visualgo.net) — See algorithms animate

### Track A — Full stack web

#### HTML & CSS

**Required** · Basic · Learn first: [Computer networks](#computer-networks)

The structure and look of every web page, from semantic HTML to responsive layouts with Flexbox and Grid.

| Topic | Required? | Coverage |
|---|---|---|
| Semantic HTML | Required | Q&A only |
| Forms and validation | Required | Q&A only |
| Accessibility basics | Required | Q&A only |
| Box model | Required | Q&A only |
| Selectors and specificity | Required | Q&A only |
| Flexbox | Required | Q&A only |
| Grid | Required | Q&A only |
| Responsive design | Required | Q&A only |
| Tailwind CSS | Optional | Not in folder |

**Your notes:** —  
**Interview Q&A:** `HTML_CSS_Interview_Questions`

**Best sources:**
- Course: [freeCodeCamp Responsive Web Design](https://www.freecodecamp.org/learn/2022/responsive-web-design/) — Projects and a certificate
- Course: [web.dev Learn CSS](https://web.dev/learn/css)
- Practice: [Flexbox Froggy](https://flexboxfroggy.com) — Game
- Practice: [Grid Garden](https://cssgridgarden.com) — Game

#### JavaScript

**Required** · Basic · Learn first: [HTML & CSS](#html--css)

The language of the browser and the base for React, TypeScript and Node.js.

| Topic | Required? | Coverage |
|---|---|---|
| Types, scope and hoisting | Required | In your notes |
| Closures and this | Required | In your notes |
| ES6+ features | Required | In your notes |
| DOM and events | Required | In your notes |
| Event loop | Required | In your notes |
| Promises and async/await | Required | In your notes |
| fetch and APIs | Required | In your notes |
| Modules | Required | In your notes |

**Your notes:** `Java script 2`  
**Interview Q&A:** `JavaScript_Interview_Questions`

**Best sources:**
- Docs: [javascript.info](https://javascript.info) — Read parts 1 and 2
- Book: [Eloquent JavaScript](https://eloquentjavascript.net) — Free online
- Course: [The Odin Project](https://www.theodinproject.com)

#### TypeScript

**Required** · Intermediate · Learn first: [JavaScript](#javascript)

JavaScript with types, the default for modern React projects.

| Topic | Required? | Coverage |
|---|---|---|
| Basic types | Required | In your notes |
| Interfaces vs types | Required | In your notes |
| Generics | Required | In your notes |
| Unions and narrowing | Required | In your notes |
| Utility types | Required | In your notes |
| Decorators | Optional | In your notes |

**Your notes:** `Typescript`, `Typescript 2`  
**Interview Q&A:** —

**Best sources:**
- Docs: [TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html)
- Course: [Total TypeScript free tutorials](https://www.totaltypescript.com/tutorials)

#### React

**Required** · Intermediate · Learn first: [JavaScript](#javascript), [TypeScript](#typescript)

The most popular library for building user interfaces from components.

| Topic | Required? | Coverage |
|---|---|---|
| JSX and components | Required | Q&A only |
| Props and state | Required | Q&A only |
| useEffect | Required | Q&A only |
| Lists and forms | Required | Q&A only |
| useContext and useRef | Required | Q&A only |
| useMemo and useCallback | Required | Q&A only |
| Custom hooks | Required | Not in folder |
| React Router | Required | Not in folder |
| Data fetching (TanStack Query) | Required | Not in folder |
| Next.js | Optional | Not in folder |

**Your notes:** —  
**Interview Q&A:** `Top 30 ReachJs question`, `React_NodeJS_Interview`

**Best sources:**
- Docs: [react.dev/learn](https://react.dev/learn) — The official tutorial
- Course: [Full Stack Open](https://fullstackopen.com/en/) — React + Node
- Docs: [TanStack Query](https://tanstack.com/query/latest)

#### Spring Boot

**Required** · Intermediate · Learn first: [Java](#java), [REST APIs & Postman](#rest-apis--postman), [DBMS](#dbms)

The most used Java framework for REST APIs, databases and security.

| Topic | Required? | Coverage |
|---|---|---|
| IoC and dependency injection | Required | In your notes |
| Beans and auto-configuration | Required | In your notes |
| REST controllers and validation | Required | In your notes |
| Exception handling | Required | In your notes |
| Spring Data JPA | Required | In your notes |
| Transactions | Required | In your notes |
| Spring Security | Required | In your notes |
| JWT authentication | Required | Not in folder |
| Microservices with Spring Cloud | Optional | Not in folder |

**Your notes:** `Spring boot 30 concepts`  
**Interview Q&A:** `SpringBoot_Interview_Questions`

**Best sources:**
- Docs: [Spring guides](https://spring.io/guides)
- Course: [Spring Academy](https://spring.academy/courses) — Official, free
- Video: [Amigoscode (YouTube)](https://www.youtube.com/@amigoscode)

#### MongoDB & Redis

**Required** · Intermediate · Learn first: [DBMS](#dbms)

A document database for flexible data, and an in-memory store for caching.

| Topic | Required? | Coverage |
|---|---|---|
| MongoDB CRUD and schema design | Required | In your notes |
| Aggregation pipeline | Required | In your notes |
| Indexes | Required | In your notes |
| Redis data types | Required | In your notes |
| Caching patterns and TTL | Required | In your notes |
| Pub/Sub | Optional | In your notes |

**Your notes:** `Mongo db`, `Redis`  
**Interview Q&A:** —

**Best sources:**
- Course: [MongoDB University](https://learn.mongodb.com) — Free
- Course: [Redis University](https://redis.io/university/)

#### Node.js & Express

**Optional** · Intermediate · Learn first: [JavaScript](#javascript), [REST APIs & Postman](#rest-apis--postman)

JavaScript on the server, a common second backend in startups.

| Topic | Required? | Coverage |
|---|---|---|
| Event loop and async I/O | Required | In your notes |
| Modules and npm | Required | In your notes |
| Express routing | Required | Not in folder |
| Middleware | Required | Not in folder |
| Mongoose | Optional | Not in folder |

**Your notes:** `NodeJs`  
**Interview Q&A:** `React_NodeJS_Interview`

**Best sources:**
- Docs: [Node.js Learn](https://nodejs.org/en/learn)
- Course: [Full Stack Open part 3](https://fullstackopen.com/en/part3)

#### Angular

**Optional** · Intermediate · Learn first: [TypeScript](#typescript)

A full frontend framework from Google. Learn only if a target company uses it.

| Topic | Required? | Coverage |
|---|---|---|
| Components and templates | Optional | In your notes |
| Services and DI | Optional | In your notes |
| RxJS | Optional | In your notes |
| Routing | Optional | In your notes |
| Reactive forms | Optional | In your notes |

**Your notes:** `Angular`  
**Interview Q&A:** —

**Best sources:**
- Course: [angular.dev tutorials](https://angular.dev/tutorials)
- Docs: [RxJS](https://rxjs.dev/guide/overview)

### Track B — QA / SDET automation

#### Selenium

**Required** · Intermediate · Learn first: [Java](#java), [Software testing basics](#software-testing-basics)

The classic browser automation tool, still asked in most QA interviews.

| Topic | Required? | Coverage |
|---|---|---|
| WebDriver setup | Required | In your notes |
| Locators (XPath, CSS) | Required | In your notes |
| Waits | Required | In your notes |
| Page Object Model | Required | In your notes |
| TestNG | Required | In your notes |
| Handling frames, alerts, windows | Required | In your notes |
| Selenium Grid | Optional | In your notes |

**Your notes:** `Selenium`  
**Interview Q&A:** `Selenium_Interview_Questions`

**Best sources:**
- Docs: [Selenium documentation](https://www.selenium.dev/documentation/)
- Course: [Test Automation University](https://testautomationu.applitools.com) — Free courses
- Practice: [The Internet (demo site)](https://the-internet.herokuapp.com) — Practice pages

#### Playwright

**Required** · Intermediate · Learn first: [Software testing basics](#software-testing-basics)

The modern end-to-end testing tool: fast, reliable and with built-in waiting.

| Topic | Required? | Coverage |
|---|---|---|
| Locators and auto-waiting | Required | In your notes |
| Assertions | Required | In your notes |
| Fixtures | Required | In your notes |
| Page objects | Required | In your notes |
| Tracing and reports | Required | In your notes |
| Parallel runs | Optional | In your notes |
| API testing in Playwright | Optional | In your notes |

**Your notes:** `Playwright`, `Playwright cheat sheet`  
**Interview Q&A:** `Playwright_Interview_Questions`

**Best sources:**
- Docs: [Playwright docs](https://playwright.dev/docs/intro)
- Course: [Test Automation University](https://testautomationu.applitools.com)

#### REST Assured

**Required** · Intermediate · Learn first: [REST APIs & Postman](#rest-apis--postman), [Java](#java)

Automate API tests in Java: send requests and check responses in code.

| Topic | Required? | Coverage |
|---|---|---|
| Given/When/Then syntax | Required | In your notes |
| Request and response specs | Required | In your notes |
| Assertions and JSON path | Required | In your notes |
| Authentication | Required | In your notes |
| JSON schema validation | Optional | In your notes |
| Data-driven tests | Optional | In your notes |

**Your notes:** `Rest Assured`, `Postman Notes`  
**Interview Q&A:** `REST_Assured_Interview_Questions`

**Best sources:**
- Docs: [REST Assured](https://rest-assured.io)
- Practice: [Restful Booker API](https://restful-booker.herokuapp.com) — Practice API
- Course: [Postman Learning Center](https://learning.postman.com)

#### Performance testing

**Optional** · Advanced · Learn first: [REST APIs & Postman](#rest-apis--postman)

Find out how many users your app can handle before it slows down.

| Topic | Required? | Coverage |
|---|---|---|
| Load, stress, spike tests | Required | In your notes |
| Response time and throughput | Required | In your notes |
| JMeter basics | Required | In your notes |
| k6 basics | Optional | Not in folder |
| Reading results | Required | In your notes |

**Your notes:** `Performance Testing Notes`  
**Interview Q&A:** —

**Best sources:**
- Docs: [Apache JMeter user manual](https://jmeter.apache.org/usermanual/index.html)
- Docs: [k6 docs](https://grafana.com/docs/k6/latest/)

#### AI for testers

**Optional** · Advanced · Learn first: [Software testing basics](#software-testing-basics)

Use AI tools to write test cases, generate test data and review failures faster.

| Topic | Required? | Coverage |
|---|---|---|
| Prompting for test cases | Optional | In your notes |
| Generating test data | Optional | In your notes |
| AI in test automation tools | Optional | In your notes |
| Reviewing AI output | Optional | In your notes |

**Your notes:** `AI for Testers`  
**Interview Q&A:** —

**Best sources:**
- Docs: [Prompt engineering guide](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview)
- Course: [DeepLearning.AI short courses](https://www.deeplearning.ai/short-courses/)

### Track C — DevOps & cloud

#### Advanced networking

**Required** · Advanced · Learn first: [Computer networks](#computer-networks)

Routing, switching and subnetting, from your CCNP notes. The base of cloud networking.

| Topic | Required? | Coverage |
|---|---|---|
| Subnetting | Required | In your notes |
| Routing protocols | Required | In your notes |
| Switching and VLANs | Required | In your notes |
| NAT | Required | In your notes |
| Firewalls and ACLs | Required | In your notes |
| VPN | Optional | In your notes |

**Your notes:** `CCNP notes`, `Network security`  
**Interview Q&A:** —

**Best sources:**
- Video: [Jeremy's IT Lab (YouTube)](https://www.youtube.com/@JeremysITLab) — Free CCNA course
- Course: [Cisco Networking Academy](https://www.netacad.com) — Free intro courses

#### Kubernetes

**Required** · Advanced · Learn first: [Docker](#docker)

Run and scale many containers across machines.

| Topic | Required? | Coverage |
|---|---|---|
| Pods | Required | In your notes |
| Deployments | Required | In your notes |
| Services | Required | In your notes |
| Ingress | Required | In your notes |
| ConfigMaps and Secrets | Required | In your notes |
| Helm | Optional | Not in folder |

**Your notes:** `Kubernates Notes`  
**Interview Q&A:** —

**Best sources:**
- Docs: [Kubernetes basics](https://kubernetes.io/docs/tutorials/kubernetes-basics/)
- Practice: [Killercoda playgrounds](https://killercoda.com) — Free clusters in the browser
- Video: [TechWorld with Nana (YouTube)](https://www.youtube.com/@TechWorldwithNana)

#### AWS & cloud computing

**Required** · Advanced · Learn first: [Docker](#docker), [Linux & command line](#linux--command-line)

Run software on rented servers: compute, storage, databases, networks and permissions.

| Topic | Required? | Coverage |
|---|---|---|
| IaaS, PaaS, SaaS | Required | In your notes |
| EC2 | Required | In your notes |
| S3 | Required | In your notes |
| RDS | Required | In your notes |
| IAM | Required | In your notes |
| VPC | Required | In your notes |
| Load balancers and auto scaling | Required | In your notes |
| Lambda | Optional | In your notes |

**Your notes:** `Aws notes`, `Cloud computing`  
**Interview Q&A:** —

**Best sources:**
- Course: [AWS Skill Builder: Cloud Practitioner Essentials](https://skillbuilder.aws) — Free
- Docs: [AWS free tier](https://aws.amazon.com/free/)
- Docs: [AWS documentation](https://docs.aws.amazon.com)

#### CI/CD

**Required** · Intermediate · Learn first: [Git & GitHub](#git--github), [Docker](#docker)

Build, test and deploy automatically every time code is pushed.

| Topic | Required? | Coverage |
|---|---|---|
| GitHub Actions workflows | Required | Not in folder |
| Build, test, deploy pipeline | Required | Not in folder |
| Secrets and environments | Required | Not in folder |
| Jenkins | Optional | Not in folder |

**Your notes:** —  
**Interview Q&A:** —

**Best sources:**
- Docs: [GitHub Actions docs](https://docs.github.com/en/actions)
- Course: [GitHub Skills](https://skills.github.com)

#### Kafka, RabbitMQ & Elasticsearch

**Optional** · Advanced · Learn first: [System design](#system-design)

Send events between services and search large amounts of data fast.

| Topic | Required? | Coverage |
|---|---|---|
| Kafka topics and partitions | Optional | In your notes |
| Consumer groups | Optional | In your notes |
| RabbitMQ exchanges | Optional | In your notes |
| Kafka vs RabbitMQ | Optional | In your notes |
| Elasticsearch indexing and search | Optional | In your notes |

**Your notes:** `Kafka cheat sheet`, `Kafka RabitMQ`, `Elastic search`  
**Interview Q&A:** —

**Best sources:**
- Course: [Confluent Developer: Kafka courses](https://developer.confluent.io/courses/)
- Docs: [RabbitMQ tutorials](https://www.rabbitmq.com/tutorials)
- Docs: [Elasticsearch reference](https://www.elastic.co/guide/en/elasticsearch/reference/current/index.html)

### Track D — AI / ML engineer

#### Maths for ML

**Required** · Intermediate

The maths behind machine learning: vectors and matrices, derivatives and integrals.

| Topic | Required? | Coverage |
|---|---|---|
| Vectors and matrices | Required | In your notes |
| Eigenvalues and eigenvectors | Required | In your notes |
| Limits and continuity | Required | In your notes |
| Derivatives and gradients | Required | In your notes |
| Integrals | Optional | In your notes |
| Probability and statistics | Required | Not in folder |
| Trigonometry | Optional | In your notes |

**Your notes:** `Linear algebra notes`, `Calculus Notes`, `Calculus`, `Limit Continuity`, `Integral top 15`, `Crafted_Note Mathematics part1`, `Crafted_Note Engineering Mathematics Part 2`, `Trigonometry sheet`  
**Interview Q&A:** —

**Best sources:**
- Video: [3Blue1Brown: Essence of linear algebra](https://www.3blue1brown.com/topics/linear-algebra) — Visual intuition
- Course: [Khan Academy Calculus](https://www.khanacademy.org/math/calculus-1)
- Book: [Mathematics for Machine Learning](https://mml-book.github.io) — Free PDF

#### Machine learning

**Required** · Advanced · Learn first: [Python](#python), [Maths for ML](#maths-for-ml)

Teach computers to learn from data: predict numbers, classify things and find groups.

| Topic | Required? | Coverage |
|---|---|---|
| Supervised vs unsupervised | Required | In your notes |
| Linear and logistic regression | Required | In your notes |
| Decision trees and random forests | Required | In your notes |
| Clustering (k-means) | Required | In your notes |
| Overfitting and regularization | Required | In your notes |
| Evaluation metrics | Required | In your notes |
| scikit-learn | Required | Not in folder |

**Your notes:** `Machine Learning`  
**Interview Q&A:** —

**Best sources:**
- Course: [Machine Learning Specialization (Andrew Ng)](https://www.coursera.org/specializations/machine-learning-introduction) — Free to audit
- Course: [Kaggle Learn](https://www.kaggle.com/learn) — Short, hands-on
- Docs: [scikit-learn user guide](https://scikit-learn.org/stable/user_guide.html)

#### Data mining

**Optional** · Intermediate · Learn first: [Python](#python), [SQL](#sql)

Find useful patterns in large datasets, and clean data before modelling.

| Topic | Required? | Coverage |
|---|---|---|
| Data preprocessing | Required | In your notes |
| Association rules | Optional | In your notes |
| Classification and clustering | Optional | In your notes |
| pandas for data analysis | Required | Not in folder |

**Your notes:** `Crafted_Note Data Mining`  
**Interview Q&A:** —

**Best sources:**
- Course: [Kaggle Learn: pandas](https://www.kaggle.com/learn/pandas)
- Book: [Mining of Massive Datasets](http://www.mmds.org) — Free

#### Deep learning

**Required** · Advanced · Learn first: [Machine learning](#machine-learning)

Neural networks that power image recognition, translation and LLMs.

| Topic | Required? | Coverage |
|---|---|---|
| Neural networks and backpropagation | Required | In your notes |
| Activation and loss functions | Required | In your notes |
| CNNs | Required | In your notes |
| RNNs and LSTMs | Required | In your notes |
| Transformers and attention | Required | In your notes |
| PyTorch | Required | Not in folder |

**Your notes:** `Crafted_Note Deep Learning Part 1`, `Deep Learning Part 3`  
**Interview Q&A:** —

**Best sources:**
- Course: [fast.ai Practical Deep Learning](https://course.fast.ai) — Free
- Course: [Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning) — Free to audit
- Docs: [PyTorch tutorials](https://pytorch.org/tutorials/)

#### Generative AI & agents

**Required** · Advanced · Learn first: [Python](#python), [REST APIs & Postman](#rest-apis--postman)

Build with LLMs: prompting, embeddings, vector databases, RAG, agents and MCP.

| Topic | Required? | Coverage |
|---|---|---|
| Calling LLM APIs | Required | In your notes |
| Prompt engineering | Required | In your notes |
| Embeddings | Required | In your notes |
| Vector databases | Required | In your notes |
| RAG | Required | In your notes |
| AI agents | Required | In your notes |
| MCP | Optional | In your notes |

**Your notes:** `GenAi`, `AI Agent For Developers`, `Mcp for dev`, `Vector database notes`, `Ai handbook`  
**Interview Q&A:** —

**Best sources:**
- Course: [Anthropic courses](https://github.com/anthropics/courses) — Prompting and tool use
- Course: [Hugging Face courses](https://huggingface.co/learn)
- Docs: [Model Context Protocol](https://modelcontextprotocol.io)
- Course: [DeepLearning.AI short courses](https://www.deeplearning.ai/short-courses/) — RAG and agents

### Optional side tracks

#### CS theory for GATE

**Optional** · Advanced · Learn first: [C programming](#c-programming)

Theory of computation, compiler design and discrete maths. Needed for GATE and exams, rarely for jobs.

| Topic | Required? | Coverage |
|---|---|---|
| Automata (DFA, NFA) | Optional | In your notes |
| Regular expressions and grammars | Optional | In your notes |
| Turing machines | Optional | In your notes |
| Lexing and parsing | Optional | In your notes |
| Code generation | Optional | In your notes |
| Sets, relations, graphs | Optional | In your notes |
| Logic and proofs | Optional | In your notes |

**Your notes:** `TheoryOfComputation Part-1`, `Crafted_Note CompilerDesign`, `Crafted_Note Discrete Mathematics Part2`  
**Interview Q&A:** —

**Best sources:**
- Video: [Neso Academy (YouTube)](https://www.youtube.com/@nesoacademy) — TOC and digital
- Book: [Crafting Interpreters](https://craftinginterpreters.com) — Free, compilers made practical
- Course: [MIT 6.042J Mathematics for CS](https://ocw.mit.edu/courses/6-042j-mathematics-for-computer-science-fall-2010/)

#### Digital electronics & embedded

**Optional** · Intermediate · Learn first: [C programming](#c-programming)

Logic gates up to microprocessors and IoT boards. Fun projects, mostly for ECE or IoT roles.

| Topic | Required? | Coverage |
|---|---|---|
| Logic gates and Boolean algebra | Optional | In your notes |
| Combinational and sequential circuits | Optional | In your notes |
| 8086 architecture and assembly | Optional | In your notes |
| ESP32 programming | Optional | In your notes |
| LoRa and IoT projects | Optional | In your notes |

**Your notes:** `Crafted_Note Digital`, `Digital Project Ideas`, `8086 project ideas`, `ESP32 & LoRa project`  
**Interview Q&A:** —

**Best sources:**
- Course: [Nand2Tetris](https://www.nand2tetris.org) — From logic gates to a computer
- Docs: [ESP32 get started (Espressif)](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/get-started/)
- Video: [Neso Academy Digital Electronics](https://www.youtube.com/@nesoacademy)

#### Computer graphics

**Optional** · Advanced · Learn first: [C programming](#c-programming)

How shapes and images are drawn on screen: transforms, projections and rendering.

| Topic | Required? | Coverage |
|---|---|---|
| Line and circle drawing | Optional | In your notes |
| 2D and 3D transforms | Optional | In your notes |
| Projections | Optional | In your notes |
| Clipping | Optional | In your notes |
| Shading basics | Optional | In your notes |

**Your notes:** `Crafted_Note ComputerGraphics`  
**Interview Q&A:** —

**Best sources:**
- Book: [Ray Tracing in One Weekend](https://raytracing.github.io) — Free
- Book: [Learn OpenGL](https://learnopengl.com) — Free

---

## Every file in your folder and where it's used

122 distinct files (duplicates such as `Copy of Sql part 2` count once).

| File | Used in |
|---|---|
| `50 Oops question` | OOP & design principles, Interview preparation |
| `70 DSA Java Interview Solutions` | Interview preparation, DSA |
| `8086 project ideas` | Digital electronics & embedded |
| `ACID properties` | DBMS |
| `Advance SQL concepts` | SQL |
| `AI Agent For Developers` | Generative AI & agents |
| `AI for Testers` | AI for testers |
| `Ai handbook` | Generative AI & agents |
| `Angular` | Angular |
| `Array & String problems` | DSA |
| `Aws notes` | AWS & cloud computing |
| `Calculus` | Maths for ML |
| `Calculus Notes` | Maths for ML |
| `CCNP notes` | Advanced networking |
| `Cloud computing` | AWS & cloud computing |
| `Coding Pattern` | DSA |
| `Collections` | Java |
| `Computer Networks notes 1` | Computer networks |
| `Copy of Sql part 2` | SQL |
| `Crafted_Note CompilerDesign` | CS theory for GATE |
| `Crafted_Note ComputerGraphics` | Computer graphics |
| `Crafted_Note Cprogramming` | C programming |
| `Crafted_Note Data Mining` | Data mining |
| `Crafted_Note Dbms` | DBMS |
| `Crafted_Note Deep Learning Part 1` | Deep learning |
| `Crafted_Note Digital` | Digital electronics & embedded |
| `Crafted_Note Discrete Mathematics Part2` | CS theory for GATE |
| `Crafted_Note Engineering Mathematics Part 2` | Maths for ML |
| `Crafted_Note Mathematics part1` | Maths for ML |
| `Crafted_Note Operating system` | Operating systems |
| `Db indexing` | DBMS |
| `DBMS` | DBMS |
| `Deep Learning Part 3` | Deep learning |
| `Digital Project Ideas` | Digital electronics & embedded |
| `Docker notes` | Docker |
| `Docker Revision notes` | Docker |
| `Docker top 10 concept` | Docker |
| `Docker_Interview_Questions` | Docker, Interview preparation |
| `DSA_Interview_Questions` | Interview preparation, DSA |
| `DSASheet` | DSA |
| `Elastic search` | Kafka, RabbitMQ & Elasticsearch |
| `ESP32 & LoRa project` | Digital electronics & embedded |
| `Excel` | Agile, Jira & Excel |
| `GenAi` | Generative AI & agents |
| `Git interview` | Git & GitHub |
| `Git Notes` | Git & GitHub |
| `Git top 20 concepts` | Git & GitHub |
| `Git_GitHub_Interview_Questions` | Git & GitHub, Interview preparation |
| `HTML_CSS_Interview_Questions` | Interview preparation, HTML & CSS |
| `Integral top 15` | Maths for ML |
| `Java collection Shortcuts` | Java |
| `Java complete` | Java |
| `Java Interface Abstraction` | Java |
| `Java script 2` | JavaScript |
| `Java Star Pattern` | Java |
| `Java Stream and Lambda expressions` | Java |
| `Java Tricky` | Java, Interview preparation |
| `Java_Interview_Questions` | Java, Interview preparation |
| `JavaScript_Interview_Questions` | Interview preparation, JavaScript |
| `JEV Model` | Java |
| `Jira notes` | Agile, Jira & Excel |
| `Kafka cheat sheet` | Kafka, RabbitMQ & Elasticsearch |
| `Kafka RabitMQ` | Kafka, RabbitMQ & Elasticsearch |
| `Kubernates Notes` | Kubernetes |
| `Limit Continuity` | Maths for ML |
| `Linear algebra notes` | Maths for ML |
| `Linux pdf` | Linux & command line |
| `Machine Learning` | Machine learning |
| `Manual testing` | Software testing basics |
| `Mcp for dev` | Generative AI & agents |
| `Mongo db` | MongoDB & Redis |
| `Network security` | Computer networks, Advanced networking |
| `NodeJs` | Node.js & Express |
| `Performance Testing Notes` | Performance testing |
| `Playwright` | Playwright |
| `Playwright cheat sheet` | Playwright |
| `Playwright_Interview_Questions` | Interview preparation, Playwright |
| `PostgreSql` | DBMS |
| `Postman Notes` | REST APIs & Postman, REST Assured |
| `Python cheat sheet` | Python |
| `Python cheat Sheet notes` | Python |
| `Python part 3` | Python |
| `Python Pattern` | Python |
| `Python Quick Notes` | Python |
| `Python sheet 2` | Python |
| `Python_Interview_Questions` | Python, Interview preparation |
| `Ratio & Proportion` | Aptitude & placement tests |
| `React_NodeJS_Interview` | Interview preparation, React, Node.js & Express |
| `Recursion` | DSA |
| `Redis` | MongoDB & Redis |
| `Rest Api` | REST APIs & Postman |
| `Rest Assured` | REST Assured |
| `REST_Assured_Interview_Questions` | Interview preparation, REST Assured |
| `Selenium` | Selenium |
| `Selenium_Interview_Questions` | Interview preparation, Selenium |
| `SOLID Principle` | OOP & design principles |
| `Sorting And Searching` | DSA |
| `Spring boot 30 concepts` | Spring Boot |
| `SpringBoot_Interview_Questions` | Interview preparation, Spring Boot |
| `Sql cheat sheet` | SQL |
| `Sql important cheat sheet` | SQL |
| `Sql part 2` | SQL |
| `Sql Sheet` | SQL |
| `SQL_Interview_Questions` | SQL, Interview preparation |
| `Stack & Quoue` | DSA |
| `System Design 1.png` | System design |
| `System design 2.png` | System design |
| `System design part 1` | System design |
| `System design part 2` | System design |
| `System_Design_Interview_Questions` | System design, Interview preparation |
| `TheoryOfComputation Part-1` | CS theory for GATE |
| `Time & Work` | Aptitude & placement tests |
| `Time complexity` | DSA |
| `Time_and_Work_50_Questions_with_Solutions-1` | Aptitude & placement tests |
| `Top 30 ReachJs question` | Interview preparation, React |
| `Top 40 TCS NQT problems` | Aptitude & placement tests |
| `Tree & Graph` | DSA |
| `Tree and Graph` | DSA |
| `Trigonometry sheet` | Maths for ML |
| `Typescript` | TypeScript |
| `Typescript 2` | TypeScript |
| `Vector database notes` | Generative AI & agents |

---

*Most PDFs are scanned images, so coverage is matched from file names and the readable interview PDFs. Use the sources above to fill the gaps.*
