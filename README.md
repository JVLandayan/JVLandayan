<div align="center">

# JUAQUIN VICTOR LANDAYAN

**Full Stack Engineer → System Design Enthusiast**

Building distributed systems • Async messaging • Microservices architecture

<br>

<a href="https://jvlandayan-portfolio.vercel.app"><img src="https://img.shields.io/badge/PORTFOLIO-000?style=flat&logo=vercel&logoColor=fff" height="24"/></a>
<a href="mailto:jvlandayaaan@gmail.com"><img src="https://img.shields.io/badge/EMAIL-EA4335?style=flat&logo=gmail&logoColor=fff" height="24"/></a>
<a href="https://linkedin.com/in/jvlandayan"><img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=flat&logo=linkedin&logoColor=fff" height="24"/></a>

</div>

---

<br>

```yaml
current_focus:
  learning: "System Design & Distributed Systems Architecture"
  reading: 
    - "Designing Data-Intensive Applications (Martin Kleppmann)"
    - "Building Microservices (Sam Newman)"
  practicing:
    - "Event-driven architectures"
    - "Async messaging patterns (Pub/Sub, Message Queues)"
    - "Distributed transaction patterns (Saga, 2PC)"
    - "Service mesh and API Gateway patterns"
    
roles:
  - company: "China Bank PH"
    position: "Full Stack Engineer (Contract)"
    timeline: "Oct 2025 - Present"
    building: ["ETL Pipelines", "Microservices with gRPC", "Azure Service Bus integration"]
    
  - company: "Dub Lab Philippines"
    position: "Full Stack Engineer"
    timeline: "July 2025 - Present"
    building: ["Sports CMS", "Real-time event streaming", "WebSocket architecture"]
```

<br>

---

## 🏗️ System Design Focus

Currently deep-diving into distributed systems architecture and async communication patterns.

<table>
<tr>
<td width="50%">

### Building Right Now
```
┌─ Microservices Platform
│  ├── gRPC inter-service communication
│  ├── Azure Service Bus (async messaging)
│  ├── Event-driven workflows
│  └── Saga pattern for distributed transactions
│
├─ Real-time Systems
│  ├── WebSocket event streaming
│  ├── Pub/Sub with Redis
│  └── Message broker patterns
│
└─ Data Pipelines
   ├── ETL orchestration (SSIS)
   ├── CDC patterns
   └── Data consistency strategies
```

</td>
<td width="50%">

### Learning & Experimenting
```
System Design Patterns
├── API Gateway & BFF
├── Service Discovery
├── Circuit Breaker
├── CQRS + Event Sourcing
└── Distributed Caching

Async Communication
├── Message Queues (Azure Service Bus)
├── Pub/Sub (Redis)
├── Event-driven Architecture
└── Dead Letter Queues

Data Consistency
├── Saga Pattern
├── 2-Phase Commit
├── Eventual Consistency
└── Idempotency patterns
```

</td>
</tr>
</table>

<br>

---

## ⚡ Technical Arsenal

<table>
<tr>
<td valign="top" width="33%">

### Languages & Frameworks
```
TypeScript/JavaScript
├── Angular (2-18)
├── Next.js
├── React
└── Vue.js

C# / .NET
├── .NET 5, 8, 9, 10
├── ASP.NET Core
├── Entity Framework Core
└── Minimal APIs

Node.js
└── Express
```

</td>
<td valign="top" width="33%">

### Architecture & Messaging
```
Microservices
├── gRPC
├── REST APIs
├── Domain-Driven Design
└── Clean Architecture

Async Messaging
├── Azure Service Bus
├── Redis Pub/Sub
├── WebSockets
└── Socket.io

Patterns
├── CQRS
├── Event Sourcing
├── Saga Pattern
└── API Gateway
```

</td>
<td valign="top" width="33%">

### Infrastructure & Data
```
Cloud (Azure)
├── AKS (Kubernetes)
├── Service Bus
├── Azure DevOps
├── App Service
└── Key Vault

Databases
├── MSSQL
├── MongoDB
├── Redis
└── Qdrant (Vector DB)

DevOps
├── Docker
├── Kubernetes
└── CI/CD Pipelines
```

</td>
</tr>
</table>

<details>
<summary><b>Extended Tooling</b></summary>

**Data & Integration**  
SSIS • Azure Data Factory • ETL Patterns • CDC • Message Brokers

**Web3 & AI**  
Solidity • Polygon Network • OpenAI API • Anthropic Claude • RAG Pipelines

**Styling & Frontend**  
TailwindCSS • Component Libraries • Responsive Design

</details>

<br>

---

## 💼 Professional Experience

<table>
<tr><td>

**Willis Towers Watson** • *Full Stack .NET Engineer*  
`Aug 2022 - Jan 2024`

- Architected migration from HTTP to gRPC for inter-service communication
- Developed microservices with Azure Kubernetes Service and Redis caching
- Implemented async patterns for improved system resilience
- Built Angular frontends integrated with distributed backend services

</td></tr>
<tr><td>

**Agora Hive** • *Full Stack Engineer (Freelance)*  
`Jan 2024 - July 2025`

- Designed end-to-end orchestration system for crypto research bot (RAG pipeline)
- Built event-driven data collection with async processing
- Deployed smart contracts on Polygon Network
- Architected full-stack applications with serverless patterns

</td></tr>
<tr><td>

**Manulife** • *Full Stack Engineer Intern*  
`March 2022 - July 2022`

- Developed REST APIs with Node.js/Express for KPI dashboards
- Worked with Azure Data Factory ETL pipelines
- Implemented CI/CD workflows with Jenkins

</td></tr>
</table>

<br>

---

## 🚀 Architecture in Action

<table>
<tr>
<td width="50%">
<h3><a href="https://dublab.com.ph/">Dub Lab Sports CMS</a></h3>

**System Design:**
```
Client Layer
    ↓
Next.js (SSR)
    ↓
API Layer (Controller-Service)
    ↓
┌─────────────┬──────────────┐
│   MongoDB   │  WebSockets  │
│  (Prisma)   │  (Socket.io) │
└─────────────┴──────────────┘
```

**Patterns:** Repository Pattern • Real-time Event Broadcasting • Role-based Access Control

**Stack:** `Next.js` `Prisma` `MongoDB` `Socket.io` `Docker`

</td>
<td width="50%">
<h3>Sports CMS API (Microservices)</h3>

**System Design:**
```
API Gateway
    ↓
┌──────────┬──────────┬──────────┐
│ Service1 │ Service2 │ Service3 │
└────┬─────┴────┬─────┴────┬─────┘
     │          │          │
   gRPC    Azure Bus   gRPC
     │          │          │
   ┌─┴──────────┴──────────┴─┐
   │      MSSQL Cluster       │
   └──────────────────────────┘
```

**Patterns:** DDD • CQRS • Service Discovery • Distributed Tracing

**Stack:** `.NET 9` `gRPC` `Azure K8s` `Service Bus`

</td>
</tr>

<tr>
<td width="50%">
<h3>China Bank ETL Platform</h3>

**System Design:**
```
Source Systems
    ↓
Azure Data Pipeline
    ↓
┌─────────────┬──────────────┐
│ Validation  │ Transform    │
└──────┬──────┴──────┬───────┘
       │             │
   Service Bus   Event Grid
       │             │
   ┌───┴─────────────┴────┐
   │  Microservices Layer │
   └──────────────────────┘
```

**Patterns:** Event-driven ETL • Saga Pattern • Dead Letter Handling • Retry Logic

**Stack:** `.NET 8/10` `SSIS` `Azure Service Bus` `gRPC`

</td>
<td width="50%">
<h3>Crypto Research Bot</h3>

**System Design:**
```
Data Sources (APIs/Web)
    ↓
Async Orchestrator
    ↓
┌──────────┬──────────┬──────────┐
│ Scraper  │  Parser  │  Tagger  │
└────┬─────┴────┬─────┴────┬─────┘
     │          │          │
  Message Queue (Async)
     │          │          │
   ┌─┴──────────┴──────────┴─┐
   │   Vector DB (Qdrant)     │
   └──────────────────────────┘
```

**Patterns:** Event-driven Processing • RAG Pipeline • Async Workers

**Stack:** `Next.js` `Qdrant` `OpenAI` `Solidity`

</td>
</tr>
</table>

<br>

---

## 📚 System Design Journey

```typescript
const currentLearningPath = {
  
  // What I'm actively studying
  theory: [
    "CAP theorem and distributed consistency models",
    "Consensus algorithms (Raft, Paxos)",
    "Distributed caching strategies (Cache-aside, Write-through)",
    "Load balancing algorithms (Round-robin, Consistent hashing)",
    "Rate limiting patterns (Token bucket, Leaky bucket)"
  ],
  
  // What I'm building to learn
  practice: [
    "Implementing Saga pattern for distributed transactions",
    "Building event-driven microservices with Azure Service Bus",
    "Designing systems with eventual consistency",
    "Creating API Gateways with routing and aggregation",
    "Experimenting with CQRS and Event Sourcing"
  ],
  
  // Real production experience
  applied: [
    "Migrated monolithic HTTP to distributed gRPC microservices",
    "Architected async messaging with Azure Service Bus",
    "Built real-time systems with WebSocket event streaming",
    "Designed ETL pipelines handling cross-system data consistency",
    "Implemented service discovery and health checks in K8s"
  ],
  
  // What's next
  exploring: [
    "Service mesh patterns (Istio, Linkerd)",
    "Distributed tracing (OpenTelemetry)",
    "Stream processing (Kafka, Event Hubs)",
    "GraphQL federation for microservices"
  ]
};
```

<br>

---

## 🎯 Core Competencies

| Distributed Systems | Async Messaging | Architecture Patterns | Data Engineering |
|:---:|:---:|:---:|:---:|
| Microservices Design | Azure Service Bus | Domain-Driven Design | ETL Pipelines |
| gRPC Communication | Pub/Sub (Redis) | CQRS + Event Sourcing | Data Consistency |
| Service Discovery | Message Queues | Clean Architecture | CDC Patterns |
| Load Balancing | Event-driven Flows | API Gateway / BFF | Stream Processing |

<br>

---

## 🎓 Education & Continuous Learning

**University of Santo Tomas**  
Bachelor of Information and Technology • `2018 - 2022`

### Certifications & Courses

<table>
<tr>
<td width="50%">

**Completed (2024-2025)**
- ✓ Software Architecture & Design of Modern Large Scale Systems
- ✓ Docker Mastery with Kubernetes
- ✓ Complete C# Masterclass
- ✓ Entity Framework: A Full Tour
- ✓ Building Web Applications with Angular 12
- ✓ Developing ASP.NET MVC Web Applications

</td>
<td width="50%">

**In Progress**
- 🔄 Angular Deep Dive
- 🔄 System Design Interview Prep
- 📖 Designing Data-Intensive Applications
- 📖 Building Microservices (2nd Edition)

**Queued**
- 📋 Master ASP.NET Core Identity
- 📋 Advanced SQL Querying Techniques
- 📋 Kafka: The Definitive Guide

</td>
</tr>
</table>

<br>

---

<div align="center">

### 📊 GitHub Activity

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=JVLandayan&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=1f6feb&text_color=c9d1d9)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=JVLandayan&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9)

<br>

<a href="https://app.daily.dev/jvlndyn">
<img src="https://api.daily.dev/devcards/v2/v3ccSWObzxRNwd11OVgu8.png?r=0rv" width="356" alt="JV Landayan's Dev Card"/>
</a>

<br><br>

**Currently obsessed with:** Distributed Systems • Event-Driven Architecture • Async Messaging Patterns

![Profile Views](https://komarev.com/ghpvc/?username=JVLandayan&color=58a6ff&style=flat)

</div>
