<!-- Header -->
<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║        Building backends that don't break under pressure     ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

# Mohd Junaid
### Backend Developer · Java & Spring Boot · Open to Work

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/mohdjunaid04/)
[![Email](https://img.shields.io/badge/Email-Hire_Me-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:mjunaid7082@gmail.com)
[![micro1](https://img.shields.io/badge/Certified-Backend_Developer_(micro1)-22C55E?style=flat)](#)
[![LeetCode](https://img.shields.io/badge/LeetCode-250+_Problems-FFA116?style=flat&logo=leetcode&logoColor=black)](https://leetcode.com/)

</div>

---

## 👋 About Me

I'm a final-year CS student at **Lovely Professional University** who builds backend systems that are actually deployed — not just on localhost.

My focus is on **Java + Spring Boot** backends that solve real engineering problems: concurrent bookings, stateless auth, rate limiting, clean API design. I care about writing code that works in production, not just in demos.

- 🔭 Currently building: **[Hospital Management System](https://github.com/MOHDJUNAID70/Hospital-Management-System---SpringBoot)** — concurrency-safe booking engine with Redis idempotency
- 🎯 Looking for: **Backend Developer / Associate SDE / Java Developer** internship or entry-level role
- 🧠 250+ DSA problems solved on LeetCode & GeeksforGeeks
- 📍 Based in Punjab, India · Available immediately

---

## 🛠️ Tech Stack

```java
public class MohdJunaid {

    String[] languages    = {"Java", "C++"};

    String[] backend      = {"Spring Boot", "Spring Security", "Spring Data JPA",
                             "Hibernate", "JWT", "REST APIs", "Microservices"};

    String[] databases    = {"PostgreSQL", "MySQL", "Redis"};

    String[] devops       = {"AWS (EC2, RDS, S3, Elastic Beanstalk)", "Docker", "Railway",
                             "Git", "GitHub", "Postman", "Swagger"};

    String[] fundamentals = {"DSA", "OOP", "DBMS", "System Design",
                             "OS", "Computer Networks"};
}
```

---

## 🚀 Featured Projects

### 🏥 Hospital Management System
> **Spring Boot · PostgreSQL · Redis · JWT · MapStruct** · [Live on Railway](https://hospital-management-system-production-6d80.up.railway.app) · [Repo](https://github.com/MOHDJUNAID70/Hospital-Management-System---SpringBoot)

The problem most booking systems ignore: **two users booking the same slot at the same millisecond.**

This system solves it with two layers — Redis idempotency keys catch retries before they hit the DB, and a `UNIQUE(doctor_id, date, time_slot)` constraint at the database level guarantees zero race conditions even under concurrent load.

**What's inside:**
- JWT auth with role-based access (`ADMIN`, `DOCTOR`, `PATIENT`) enforced at every endpoint via `@PreAuthorize`
- Dynamic filtering, sorting & pagination using Spring Data JPA Specifications
- MapStruct DTO↔Entity mapping — clean API contracts, zero manual get/set chains
- Global exception handler returning structured JSON errors (no stack traces leaking to clients)
- Swagger UI with full endpoint documentation

---

### 🤖 AI Career Coach — Cheminova AI
> **Spring Boot · PostgreSQL · Redis · JWT** · [Live](https://cheminova-ai-production.up.railway.app/swagger-ui/index.html) · [Repo](https://github.com/MOHDJUNAID70/Cheminova_AI-Backend)

REST API middleware layer connecting a React frontend to a Python AI engine — handling auth, request forwarding, response mapping, and CORS security.

**What's inside:**
- JWT + Redis token blacklisting → immediate session invalidation on logout/deletion
- Cascading deletes via JPA/Hibernate — user deletion auto-removes all linked learning paths
- CORS configured to allowlist specific frontend domains only

---

### 💰 Finance Dashboard System
> **Spring Boot · PostgreSQL · Bucket4j · JWT** · [Live on Railway](https://finance-dashboard-system-backend-production.up.railway.app/swagger-ui/index.html) · [Repo](https://github.com/MOHDJUNAID70/Finance-System---Spring-Boot)

Secure, role-based finance API with **Token Bucket rate limiting** (Bucket4j) to prevent abuse and maintain stability under burst traffic.

**What's inside:**
- Fine-grained `@PreAuthorize` access control per role
- Environment-based config for Railway deployment
- Full Swagger documentation + comprehensive testing

---

## 📊 GitHub Stats

<div align="center">

![Mohd Junaid's GitHub Stats](https://github-readme-stats.vercel.app/api?username=MOHDJUNAID70&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=MOHDJUNAID70&layout=compact&theme=github_dark&hide_border=true&langs_count=6)

</div>

---

## 🏆 Certifications & Achievements

| | |
|---|---|
| 🥇 **Certified Backend Developer** | micro1 · May 2026 |
| 🧩 **250+ DSA Problems Solved** | LeetCode + GeeksforGeeks |
| ⭐ **4 Stars in SQL** | HackerRank |

---

## 📬 Let's Connect

I'm actively looking for **backend / SDE entry-level roles** where I can contribute from day one.

If you're hiring or know someone who is — reach out.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-mohdjunaid04-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/mohdjunaid04/)
[![Email](https://img.shields.io/badge/Gmail-mjunaid7082@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:mjunaid7082@gmail.com)

---

<div align="center">
<sub>⚡ Open to work · Immediate joiner · Backend roles in Java/Spring Boot</sub>
</div>
