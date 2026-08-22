<div align="center">

<!-- ANIMATED HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:1f6feb&height=220&section=header&text=Burakcan%20Aksoy&fontSize=42&fontColor=e6edf3&fontAlignY=35&desc=Backend%20Engineer%20%7C%20Distributed%20Systems%20%7C%20AI%20Integration&descSize=16&descAlignY=55&descColor=8b949e&animation=fadeIn" width="100%"/>

<br/>

<!-- TYPING ANIMATION -->
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=80&lines=Architecting+scalable+backend+systems+with+Java+%26+Spring;Building+AI-powered+products+from+zero+to+production" alt="Typing SVG" /></a>

<br/>

<!-- SOCIAL BADGES -->
[![Website](https://img.shields.io/badge/burakcanaksoy.dev-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white)](https://burakcanaksoy.dev/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/burakcan-aksoy-ba0132259/)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@burakcnaksy)
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aksoyburak808@gmail.com)

</div>

<br/>

## `> whoami`

```java
public final class BurakcanAksoy {

    private final String role        = "Backend Engineer";
    private final String location    = "Kocaeli, Turkey";
    private final String education   = "B.Sc. Computer Engineering — Celal Bayar University";
    private final String[] focus     = { "Distributed Systems", "Microservices", "AI-Powered Products" };

    public String getCurrentMission() {
        return "Building production-grade systems that solve real-world problems at scale.";
    }
}
```

> I design and build backend architectures that power AI-driven products — from voice platforms processing thousands of concurrent calls to intelligent document pipelines. I care about **clean abstractions**, **system reliability**, and **shipping fast without cutting corners**.

---

## 🏗️ Architecture & Stack

<table>
<tr>
<td width="50%" valign="top">

### ⚙️ Backend Core
![Java](https://img.shields.io/badge/Java_17/21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=google&logoColor=white)

**Patterns:** DDD · CQRS · Saga · Outbox · Circuit Breaker  
**API Design:** REST (HATEOAS) · GraphQL · gRPC (Protobuf)  
**Security:** Spring Security · JWT · OAuth2 · RBAC · AES-256

</td>
<td width="50%" valign="top">

### 🗄️ Data Layer
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)

**ORM:** Hibernate · JPA · Prisma  
**Search:** pgvector (Semantic) · PostGIS (Spatial)  
**Queues:** Apache Kafka · RabbitMQ · BullMQ

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ☁️ DevOps & Cloud
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/K8s-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)

**Observability:** ELK · Prometheus · Grafana · OpenTelemetry  
**Infra:** Nginx · HikariCP · Vercel Edge

</td>
<td width="50%" valign="top">

### 🤖 AI & Integration
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Vapi](https://img.shields.io/badge/Vapi-5046E5?style=flat-square&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)

**Techniques:** RAG · Semantic Embeddings · Structured Prompting  
**Voice AI:** Vapi · Twilio · Real-time Telephony

</td>
</tr>
</table>

---

## 🚀 Featured Projects

> Production-level systems designed with real-world scale in mind.

<table>
<tr>
<td width="50%" valign="top">

### 🗣️ [VoxAgent](https://github.com/burakcnaksy0/VoxAgent)
**White-Label AI Voice Platform**

Multi-tenant B2B SaaS enabling agencies to deploy, manage, and resell AI voice receptionists & outbound sales dialers under their own brand.

`Next.js` `Supabase` `Vapi` `Stripe` `pgvector`

**Highlights:**
- 🔐 AES-256 encrypted API key storage per tenant
- 📞 Bulk outbound campaigns — 1,000+ parallel calls
- 🧠 RAG-powered knowledge bases (PDF/CSV → embeddings)
- 💳 Stripe-integrated subscription & minute packages
- 🏢 Full white-labeling: custom domain, logo, branding

</td>
<td width="50%" valign="top">

### 🤖 [SupportAI MVP](https://github.com/burakcnaksy0/SupportAI-MVP)
**AI-Powered Customer Support Platform**

Intelligent support system with automated ticket routing, AI response generation, and real-time analytics dashboard. Built with CI/CD pipeline.

`NestJS` `Docker` `GitHub Actions` `AI/LLM`

**Highlights:**
- 🎫 Automated ticket classification & priority routing
- 💬 AI-generated response suggestions for agents
- 📊 Real-time support analytics & SLA tracking
- 🐳 Fully containerized with Docker Compose
- ⚡ CI/CD pipeline with GitHub Actions

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📄 [ResuMatch AI](https://github.com/burakcnaksy0/ResuMatch-AI)
**AI-Driven CV Tailoring Engine**

Maintains a single Master Profile and generates job-specific CVs using LLMs. Asynchronous processing with BullMQ, SHA-256 based caching for idempotent generation.

`NestJS` `Next.js` `PostgreSQL` `Redis` `BullMQ`

**Highlights:**
- 🧩 Async pipeline: Redis queue → Worker → LLM → Cache
- 🔒 SHA-256 hashing for idempotent O(1) cache hits
- 📐 4 professional React templates with PDF export
- ✅ Dual-layer validation (Zod + Class-Validator)
- 🗃️ Automated daily `pg_dump` with 10-day rotation

</td>
<td width="50%" valign="top">

### 🏠 [Vesta](https://github.com/burakcnaksy0/Vesta)
**Full-Stack Real Estate Marketplace**

Production marketplace with real-time WebSocket chat, PostGIS spatial queries, and a dedicated admin panel. Spring Boot backend with React frontend.

`Spring Boot` `PostgreSQL` `PostGIS` `WebSocket` `React`

**Highlights:**
- 💬 Real-time chat with STOMP — typing indicators & read receipts
- 🗺️ PostGIS spatial queries for location-based search
- 🛡️ RBAC with Admin/User/Moderator roles
- 📋 Swagger/OpenAPI documented REST API
- 🐳 Dockerized full-stack deployment

</td>
</tr>
<tr>
<td colspan="2" align="center">

### 🗺️ [SmartRoute](https://github.com/burakcnaksy0/SmartRoute)
**Intelligent Journey Planning Platform**

AI-powered route optimization system with NLP-based destination parsing, real-time geocoding, and smart multi-stop journey planning.  
Combines natural language understanding with geospatial algorithms to create optimized travel itineraries.

`Spring Boot` `NLP` `Geocoding API` `React Native` `PostgreSQL`

</td>
</tr>
</table>

---

## 📊 GitHub Analytics

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=burakcnaksy0&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9&ring_color=58a6ff&count_private=true" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=burakcnaksy0&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=8" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=burakcnaksy0&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=30363d&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=burakcnaksy0&theme=github-compact&hide_border=true&bg_color=0d1117&color=58a6ff&line=58a6ff&point=c9d1d9&area=true&area_color=1f6feb" width="95%"/>
</div>

---

<div align="center">

### 💡 Engineering Philosophy

```
"Make it work, make it right, make it fast."  — Kent Beck
```

*I build systems where every component earns its place in the architecture.*

<br/>

<img src="https://komarev.com/ghpvc/?username=burakcnaksy0&style=for-the-badge&color=1f6feb&label=PROFILE+VIEWS" alt="Profile Views"/>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:1f6feb&height=100&section=footer" width="100%"/>

</div>
