<div align="center">

# Julián David Ovalle Parra

### Software Developer · Java & Spring Boot · JavaScript · AI Automation

I build backend services with Java and Spring Boot, web interfaces with JavaScript,<br>
and AI-driven workflows that automate real processes.

📍 Colombia

<a href="https://julianovalle23.github.io/Portafolio_JulianOv/"><img src="https://img.shields.io/badge/Portfolio-0d1117?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio"></a>
<a href="YOUR_LINKEDIN_URL"><img src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="mailto:YOUR_EMAIL"><img src="https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>

</div>

---

## About Me

I'm a software developer with a technical degree in software development (*Técnico laboral en desarrollo de software*), focused on building applications that solve concrete problems rather than isolated exercises.

Most of my current work is on the **backend with Java and Spring Boot**: designing REST APIs, modeling data with JPA/Hibernate and PostgreSQL, and securing endpoints with Spring Security and JWT. On the **frontend**, I work with JavaScript, HTML and CSS to build clear, usable interfaces.

I'm also exploring how **artificial intelligence and automation** can reduce repetitive work — building workflows with n8n, integrating AI APIs and experimenting with retrieval-augmented generation (RAG).

I care about how software is structured, not only whether it runs. That's why I'm deliberately strengthening my understanding of software architecture, clean code and engineering practices with every project I build.

---

## Tech Stack

| Area | Technologies |
| :--- | :--- |
| **Languages** | ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white) |
| **Backend** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white) ![Hibernate](https://img.shields.io/badge/JPA_/_Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white) ![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black) |
| **Frontend** | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| **Databases** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) |
| **AI & Automation** | ![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white) ![AI APIs](https://img.shields.io/badge/AI_APIs-412991?style=flat-square&logo=openai&logoColor=white) ![RAG](https://img.shields.io/badge/RAG-1f2937?style=flat-square) |
| **Tools** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) |

---

## Featured Projects

### 🗂️ CampusDesk

A RESTful incident management system for registering, tracking and resolving incidents within an institution.

**Problem** — Incident reports handled through informal channels get lost, have no clear owner and leave no traceable history.

**Solution** — A centralized backend API where incidents are created, assigned and updated through secured endpoints, with every change persisted in a relational database.

**Tech Stack** — Java · Spring Boot · Spring Security · JWT · PostgreSQL · JPA/Hibernate · Swagger

**Key Features**
- REST API for creating, querying and updating incidents
- Stateless authentication and authorization with Spring Security and JWT
- Relational persistence with PostgreSQL through JPA/Hibernate
- Interactive API documentation with Swagger
- Centralized exception handling with consistent error responses

**What I learned** — Layered architecture (controller → service → repository), separation of concerns, securing a REST API end-to-end, entity modeling with JPA and designing predictable error handling.

---

### 🤖 TRAMIA / JARVIS

An AI-powered assistant designed to guide users through administrative procedures and automate parts of the process.

**Problem** — Administrative procedures are often confusing: requirements are scattered across documents, and people spend time searching for information instead of completing the task.

**Solution** — An assistant that retrieves relevant information from a knowledge base and answers in context, combined with automated workflows that handle repetitive steps.

**Tech Stack** — n8n · AI APIs · RAG · REST APIs

**Key Features**
- Context-aware answers using retrieval-augmented generation (RAG)
- Automated workflows orchestrated with n8n
- Integration of external services through APIs
- Processing and structuring of procedure-related information

**What I learned** — Designing automation pipelines, connecting AI models to real data sources, and the practical trade-offs of building LLM-based systems that need to give reliable answers.

---

### 💰 Expense Tracker

A web application for recording and organizing personal expenses.

**Problem** — Without a simple way to log spending, it's hard to know where money actually goes.

**Solution** — A lightweight, browser-based interface that makes registering and reviewing expenses quick and readable.

**Tech Stack** — JavaScript · HTML5 · CSS3

**Key Features**
- Register and manage expenses through a clean interface
- Organized presentation of spending data
- Client-side data handling with vanilla JavaScript
- Focus on usability and clear visual hierarchy

**What I learned** — DOM manipulation, managing application state without frameworks, and designing interfaces around how users actually read information.

---

### 🌐 Portfolio

My personal portfolio — the central place to see my projects, skills and contact information.

**Tech Stack** — HTML5 · CSS3 · JavaScript · GitHub Pages

**Live Demo** — [julianovalle23.github.io/Portafolio_JulianOv](https://julianovalle23.github.io/Portafolio_JulianOv/)

---

## Engineering Practices

My projects explore the practices that make software maintainable over time:

- **Layered architecture** — controllers, services and repositories with clear responsibilities
- **RESTful API design** — consistent resources, HTTP methods and status codes
- **DTOs and validation** — keeping the API contract separate from persistence entities
- **Dependency injection** — loosely coupled components through Spring's IoC container
- **Global exception handling** — predictable, well-structured error responses
- **Security** — authentication and authorization with Spring Security and JWT
- **API documentation** — self-documented endpoints with Swagger / OpenAPI
- **Version control** — meaningful commits and organized repositories with Git

I'm currently strengthening my application of **SOLID principles** and clean code, refactoring earlier work as my understanding grows.

---

## Currently Learning

- **Software architecture** — designing systems that scale beyond a single service
- **Docker** — containerizing Spring Boot applications and their databases
- **Testing** — unit and integration tests with JUnit and Mockito
- **AI engineering** — more robust RAG pipelines and AI-driven automation

---

## GitHub Activity

I use GitHub as a working record: each repository reflects a problem I set out to solve and the engineering decisions behind it. Feel free to explore the code, open an issue or reach out with feedback.

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=julianovalle23&show_icons=true&hide_border=true&theme=github_dark&hide_title=true" alt="GitHub stats">
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=julianovalle23&layout=compact&hide_border=true&theme=github_dark" alt="Top languages">

</div>

---

## Professional Goals

- Join an engineering team where I can contribute to production software and learn from experienced developers
- Deepen my backend expertise with Java and Spring Boot
- Write cleaner, better-tested and better-architected code with every project
- Build practical solutions that combine traditional software with AI and automation

---

## Connect With Me

- **Portfolio** — [julianovalle23.github.io/Portafolio_JulianOv](https://julianovalle23.github.io/Portafolio_JulianOv/)
- **GitHub** — [github.com/julianovalle23](https://github.com/julianovalle23)
- **LinkedIn** — [LinkedIn](YOUR_LINKEDIN_URL)
- **Email** — [YOUR_EMAIL](mailto:YOUR_EMAIL)

Open to junior software development opportunities, collaborations and technical conversations.

---

<div align="center">
<sub>Building software with Java, JavaScript and AI · Colombia</sub>
</div>
