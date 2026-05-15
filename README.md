### Hi there, I'm Qi Lin

I am a Computer Science graduate from the **University of Melbourne**, specializing in **High-Performance Systems**, **Software Architecture**, and **Algorithm Optimization**.

I bridge the gap between low-level system efficiency (C/C++) and high-level full-stack delivery (Node.js/React/Java). Passionate about writing clean, testable code and architecting scalable backend systems.

---

### Featured Projects

**1. Academic Marker Moderation System**
![React](https://img.shields.io/badge/-React-black?style=flat&logo=react) ![Node.js](https://img.shields.io/badge/-Node.js-black?style=flat&logo=nodedotjs) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-black?style=flat&logo=postgresql)

A commercial-grade grading platform used by university staff (University Capstone / Team Repo).
* **Role:** Full-Stack Developer (Client Project).
* **Highlight:** Migrated full-stack to AWS — provisioning RDS, S3, SES (DKIM/DMARC via Route 53), Amplify with CI/CD, and EC2 with PM2. Engineered secure RESTful APIs with JWT-based RBAC and bcrypt password hashing.
* [**View Repository**](https://github.com/qllin2/MarkingApp)

**2. Autonomous Drone Delivery Simulation Engine**
![Java](https://img.shields.io/badge/-Java-orange?style=flat&logo=java) ![Gradle](https://img.shields.io/badge/-Gradle-02303A?style=flat&logo=gradle) ![Simulation](https://img.shields.io/badge/-Discrete%20Event%20Simulation-blue?style=flat)

A cloud-native simulation engine deployed on AWS ECS Fargate, featuring an Apache Kafka event-driven telemetry pipeline, OpenAI GPT-4o-mini business insights integration, and a React/TypeScript dashboard with real-time SSE visualisation.
* **Key Tech:** Java, Spring Boot, Apache Kafka, AWS ECS Fargate, Docker, OpenAI API, React, TypeScript
* **Highlight:** Replaced in-memory telemetry with Kafka (Amazon MSK in production) via pluggable @Profile-activated implementations; deployed with multi-stage Docker build, ECR, and CloudWatch logging. 
* [**View Repository**](https://github.com/qllin2/Autonomous-Drone-Delivery-Simulation-Engine)

**3. HTTP Caching Proxy Service**
![C](https://img.shields.io/badge/-C-black?style=flat&logo=c) ![Network](https://img.shields.io/badge/-Socket-black?style=flat)

A HTTP/1.1 caching proxy server implemented in C with manual header parsing and dual-stack networking support.  
* **Key Tech:** C (C99), BSD Sockets, Manual Memory Management, Dual-stack (IPv4/IPv6).
* **Highlight:** Engineered a custom LRU caching engine to cache HTTP responses under strict memory limits, respecting complex `Cache-Control` directives.
* [**View Repository**](https://github.com/qllin2/http-proxy-server-c)

**4. Bitboard-Optimized Adversarial AI Engine**
![Python](https://img.shields.io/badge/-Python-blue?style=flat&logo=python) ![Algorithms](https://img.shields.io/badge/-Algorithms-green?style=flat) ![Optimization](https://img.shields.io/badge/-Optimization-red?style=flat)

An autonomous agent optimized for strict memory and time constraints.
* **Key Tech:** Python, Bitwise Operations, IDDFS, Alpha-Beta Pruning.
* **Highlight:** Engineered Bitboard representation and Zobrist Hashing for $O(1)$ state lookups, achieving highly efficient adaptive time management.
* [**View Repository**](https://github.com/qllin2/high-perf-game-ai-agent)

**5. Virtual Memory Management Simulator**
![C](https://img.shields.io/badge/-C-black?style=flat&logo=c) ![Systems](https://img.shields.io/badge/-Systems-gray?style=flat)

A hardware-level simulation of a Memory Management Unit (MMU).
* **Key Tech:** C, Operating Systems Concepts, Memory Management.
* **Highlight:** Implemented Hierarchical Page Tables and a Translation Lookaside Buffer (TLB) with custom LRU eviction policies.
* [**View Repository**](https://github.com/qllin2/virtual-memory-simulator)

**6. Shadow Mario: 2D Platformer Engine**
![Java](https://img.shields.io/badge/-Java-orange?style=flat&logo=java) ![Game Dev](https://img.shields.io/badge/-Game%20Dev-green?style=flat) ![OOD](https://img.shields.io/badge/-OOD-blue?style=flat)

A feature-rich game engine built from scratch on top of the Bagel framework.
* **Key Tech:** Java, Object-Oriented Design (OOD), CSV Parsing.
* **Highlight:** Implemented AABB collision detection, projectile physics, and a polymorphic entity system featuring complex Boss AI logic.
* [**View Repository**](https://github.com/qllin2/java-2d-platformer)


---

### Technical Skills

* **Languages:** Java (SE), C (C99), Python, JavaScript/TypeScript, SQL
* **Core Concepts:** Design Patterns (GoF), Data Structures & Algorithms, OOD, Concurrency
* **Systems:** Linux (Ubuntu), Docker, Git, TCP/IP, Valgrind, Bitwise Optimization
* **Web:** React, Node.js, HTML5/CSS3

---
[LinkedIn](https://www.linkedin.com/in/qi-lin-dev/) • [Email](mailto:comttor.lin@gmail.com)
