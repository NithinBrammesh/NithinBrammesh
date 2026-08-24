# Hi 👋, I'm Nithin B

### Backend Engineer | Java • Spring Boot • Kafka • Redis • Distributed Systems

I’m a **Backend Engineer** focused on building scalable backend systems, REST APIs, event-driven architectures, and real-time data processing applications.

I enjoy working on systems where **multiple services communicate, data flows through events, and backend services need to remain reliable and scalable**.

Currently focused on:

- ☕ Java & Spring Boot
- 📨 Apache Kafka & Event-Driven Architecture
- ⚡ Redis & Real-Time Systems
- 🐳 Docker & Linux
- 🗄️ PostgreSQL & MySQL
- ☁️ AWS
- 🏗️ Distributed Systems & System Design

---

## 🚀 About Me

- 💻 Backend Engineer with hands-on experience building **REST APIs and real-time backend systems**
- ⚙️ Experience working with **Kafka, Redis, Apache Flink, Docker and Linux**
- 🔄 Built event-driven pipelines for **real-time manufacturing data processing**
- 🏭 Worked on backend systems for **production monitoring and machine reconciliation**
- 🔐 Experience implementing **JWT authentication and Role-Based Access Control**
- 🤖 Built AI-powered backend applications using **RAG and Google Gemini**
- 🧩 Interested in **Distributed Systems, Event-Driven Architecture and Scalable Backend Systems**
- 📚 Strong foundation in **Java, OOP, Data Structures & Algorithms and System Design**

---

## 🛠️ Tech Stack

### Languages

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)

### Backend

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)

### Real-Time & Distributed Systems

![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Apache Flink](https://img.shields.io/badge/Apache%20Flink-E6526F?style=for-the-badge&logo=apacheflink&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

- Event-Driven Architecture
- Stream Processing
- Redis Pub/Sub
- Redis ZSETs
- Server-Sent Events (SSE)
- Distributed Systems Fundamentals

### Databases

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)

### DevOps & Cloud

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

---

# 🔥 Featured Projects

## 🏭 Manufacturing Reconciliation System

**Kafka • Redis • PyFlink • Docker • Flask • Linux • SSE • Node-RED**

A real-time manufacturing reconciliation system designed to process barcode streams from **AOI, SPI and FCR inspection machines** for production monitoring and rework tracking.

### Architecture

```text
Manufacturing Machines
        │
        ▼
     Node-RED
        │
        ▼
      Kafka
        │
        ▼
     PyFlink
        │
        ▼
      Redis
        │
        ▼
    Flask API
        │
        ▼
   React Dashboard
```

### Highlights

- Built event-driven pipelines using **Apache Kafka and Redis Pub/Sub**
- Implemented real-time stream processing using **PyFlink**
- Designed reconciliation logic for tracking machine coverage, barcode mismatches and production losses
- Implemented **24-hour tumbling window processing**
- Built real-time dashboard updates using **Server-Sent Events (SSE)**
- Containerized the complete backend infrastructure using **Docker Compose**
- Designed the system to support dynamic machine configurations

🔗 [View Repository](https://github.com/NithinBrammesh/manufacturing-reconciliation-system)

---

## 🤖 AI Workflow Builder

**Node.js • Nhost Functions • Hasura GraphQL • PostgreSQL • React • GraphQL WebSockets**

A backend workflow execution engine capable of executing ordered workflows containing different types of processing steps.

### Workflow Capabilities

```text
Workflow
   │
   ├── AI / LLM
   ├── HTTP
   ├── Conditional
   ├── Approval
   ├── Database
   └── Notification
```

### Highlights

- Built persistent workflow execution states:
  `running → paused → completed / failed`
- Implemented **human-in-the-loop approval** with pause/resume execution
- Designed organization-level **RBAC and multi-tenant authorization**
- Implemented authenticated workflow triggers through **Hasura GraphQL Actions and HTTP webhooks**
- Added server-side authorization and quota validation
- Implemented real-time execution updates using **GraphQL subscriptions over WebSockets**

🔗 [View Repository](https://github.com/NithinBrammesh/ai-workflow-builder)

---

## ☕ Mysore Real Estate Backend

**Java • Spring Boot • PostgreSQL • JWT • Docker • Swagger**

A backend platform for property listings and real-estate management.

### Highlights

- Built REST APIs using **Spring Boot**
- Implemented **JWT-based authentication**
- Implemented role-based authorization
- Designed relational database models using PostgreSQL
- Added API documentation using Swagger/OpenAPI
- Containerized backend services using Docker

🔗 [View Repository](https://github.com/NithinBrammesh/mysore-realestate-backend)

---

## 📨 Kafka Event Streaming Dashboard

**Apache Kafka • Node-RED • Docker • React • REST APIs**

A real-time event-driven streaming platform that processes live data streams through Kafka and exposes backend APIs for analytics and visualization.

### Highlights

- Implemented Kafka-based event streaming
- Used Node-RED for event/data ingestion
- Containerized services using Docker
- Exposed backend APIs for streaming analytics
- Built a dashboard for real-time data visualization

🔗 [View Repository](https://github.com/NithinBrammesh/kafka-event-streaming-dashboard)

---

# 💼 Experience

### Backend Engineering Intern — Cymbeline Innovation

**May 2026 – July 2026 | Bengaluru**

Worked on real-time backend systems for manufacturing data processing and production monitoring.

- Designed event-driven pipelines using **Kafka and Redis**
- Developed backend services for production reconciliation and machine monitoring
- Worked with real-time metric aggregation
- Containerized backend applications using **Docker Compose**

### Website Developer — Nakshatra Namaha Creations

**June 2025 – April 2026 | Mysore**

- Designed and built **15+ RESTful APIs** using Node.js and Express.js
- Implemented JWT authentication and RBAC
- Designed MongoDB data models
- Deployed applications using **AWS EC2 and S3**
- Worked in Linux-based environments

---

# 📚 Currently Learning

```text
Java
  ↓
Spring Boot
  ↓
REST APIs
  ↓
SQL & PostgreSQL
  ↓
Kafka
  ↓
Redis
  ↓
Docker
  ↓
Distributed Systems
  ↓
System Design
  ↓
AWS
```

My current goal is to deepen my understanding of **backend engineering, distributed systems, scalable architectures and production-grade software development**.

---

# 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=NithinBrammesh&show_icons=true&theme=tokyonight&hide_border=true" height="170"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=NithinBrammesh&layout=compact&theme=tokyonight&hide_border=true" height="170"/>
</p>

---

# 📈 Contribution Streak

<p align="center">
  <img src="https://streak-stats.demolab.com?user=NithinBrammesh&theme=tokyonight&hide_border=true" />
</p>

---

# 🤝 Connect With Me

<p align="center">
  <a href="https://www.linkedin.com/in/nithin-brammesh/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:brammeshnithin@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/NithinBrammesh">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

<p align="center">
  <i>Building backend systems, one event at a time.</i>
</p>
