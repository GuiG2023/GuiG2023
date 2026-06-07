# Hi there, I'm Guiran Liu (GuiG2023) 👋

<p align="center">
  <a href="https://github.com/GuiG2023"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/guiran-liu-232ab228a/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://scholar.google.com/citations?user=RQWgrIsAAAAJ&hl=en"><img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white" /></a>
</p>

---

## 🚀 About Me

<table>
  <tr>
    <td width="65%" valign="top">
      <p>👋 Hi! I'm <b>Guiran Liu</b>, a <b>Backend & Full-Stack Engineer</b> based in the US, specializing in <b>production-grade system design, cloud infrastructure, and cross-module integration</b>.</p>
      <p>💻 I design and ship scalable APIs end-to-end — from architecture through deployment. My core strength is <b>solving complex integration problems under deadline pressure</b> and bridging gaps between system architecture and implementation. I excel at stabilizing systems, debugging cross-layer issues, and shipping demo-critical fixes on tight timelines.</p>
      <p>🔬 I maintain an active <a href="https://scholar.google.com/citations?user=RQWgrIsAAAAJ&hl=en"><b>research profile</b></a> with 11 publications in LLM optimization, RAG architectures, and Edge AI — but my passion is <b>translating research into production systems</b>.</p>
      <p>🎯 <b>Core Strengths</b>: FastAPI backend design, AWS/EC2 deployment, NGINX infrastructure, full-stack debugging, MySQL relational design, secure authentication workflows, and team coordination during critical integration phases.</p>
    </td>
    <td width="35%" valign="top" align="center">
      <img src="./assets/panda.jpg" width="180px" style="border-radius: 12px; border: 2px solid #5c2d91;" />
      <br />
      <sub><i>Code hard, stay sharp. 🚀</i></sub>
    </td>
  </tr>
</table>

---

## 🛠️ Featured Project: GatorMart (Production Campus Marketplace)

**Role**: Backend Lead | **Team Size**: 7 engineers | **Timeline**: Spring 2026 (5 months)

GatorMart is a production-ready student marketplace built exclusively for SFSU students. Users register with verified @sfsu.edu emails, post items (textbooks, furniture, electronics), search by category, and message sellers directly in-app to arrange campus pickups.

**Live Demo**: [54.193.192.172](http://54.193.192.172/) | **GitHub**: [csc648-sp26-145-team03](https://github.com/CSC-648-SFSU/csc648-sp26-145-team03)

### Technical Architecture & Accomplishments

**Backend System Design**
- Designed layered FastAPI backend from scratch with clean MVC separation: REST API layer → Business logic → Data access layer
- Implemented secure authentication: JWT token handling, bcrypt password hashing, @sfsu.edu domain validation, protected route interception
- Built 8+ production API endpoints with proper error handling, input validation, and response consistency

**Database Architecture**
- Architected MySQL relational schema with 7 core tables: `users`, `posts`, `conversations`, `messages`, `meetup_locations`, `meetup_requests`, `categories`
- Enforced referential integrity through foreign keys and cascading rules; implemented state machines for post and request workflows
- **Security**: 100% parameterized queries at code level — zero SQL injection vulnerabilities

**Cloud Deployment & Infrastructure**
- **AWS EC2 Linux**: Full production server setup, environment configuration, dependency management, instance-level security
- **NGINX Reverse Proxy**: Unified frontend (React) and backend (FastAPI) under single domain, eliminating CORS complexity and improving security
- **End-to-End Testing**: Validated every feature in production environment; caught and fixed environment-specific bugs before demo

**Advanced Feature Implementation**
- **Secure Image Upload**: Multipart file streaming, MIME type validation, UUID-based storage with symlink access control, rate limiting
- **Real-Time In-App Messaging**: Conversation threads with unread message tracking; integrated buyer-seller communication (replaced external email workflow)
- **Admin Dashboard**: Post approval workflow with queue management; category and location maintenance with data validation

### Leadership & Impact

**GitHub Contributions**
- **54+ commits** to main development branch (1st contributor by activity)
- **100% P1 Feature Delivery**: All 15 committed Priority 1 requirements shipped, tested, and deployed
- **Multi-Module Integration Lead**: Resolved routing inconsistencies, frontend-backend state synchronization issues, API failures across 3+ milestone deadlines
- **System Stabilization**: Led debugging and coordination during final integration phases; assigned and triaged critical bug fixes

**Production Quality**
- **0 Security Incidents**: Parameterized queries, input validation, secure file handling, and JWT token management prevented vulnerabilities
- **Demo Success**: Stabilized system to showcase complete user workflows (register → create post → search → message seller → arrange meetup)

### Key Challenges & Solutions

1. **JWT Token & Session Persistence** → Debugged token refresh logic and React state persistence across page refreshes; validated across login/logout cycles
2. **Cross-Origin Overhead** → Transitioned from separate frontend/backend origins to unified NGINX reverse proxy; reduced complexity and improved security
3. **Late-Stage Integration** → Coordinated multi-module integration during final days; prioritized and fixed demo-blocking issues
4. **Deployment Validation** → Tested every feature in EC2 production environment; caught environment-specific bugs (permissions, symlinks, package versions)

---

## 💻 Tech Stack & Skills

### Backend & Infrastructure
- **Languages & Frameworks**: Python, FastAPI (async, Pydantic validation, auto-generated docs)
- **Databases**: MySQL (relational schema design, parameterized queries, foreign keys, indexing)
- **Cloud & DevOps**: AWS EC2, Linux (Ubuntu), NGINX (reverse proxy, load balancing), environment configuration
- **Security & Auth**: JWT tokens, bcrypt password hashing, domain validation, CORS handling, file upload validation

### Full-Stack Integration
- **Frontend Integration**: React state management, REST API integration, component lifecycle, form handling
- **API Testing & Debugging**: Postman, curl, browser dev tools, Flask/FastAPI debug mode, error logging
- **Version Control**: Git (branches, pull requests, merge conflict resolution, rebase workflows), GitHub

### Related Skills
- **Project Management**: Discord async coordination, milestone planning, team communication, technical documentation
- **Code Quality**: Parameterized queries, error handling, input validation, code review, naming conventions
- **LLM & Optimization** (Research Background): PyTorch, LLM fine-tuning, RAG architectures, Edge AI

---

## 📊 Key Metrics

| Metric | Value |
|--------|-------|
| **GitHub Commits** | 54+ to main branch |
| **P1 Features Shipped** | 15/15 (100% completion) |
| **Team Coordination** | 7 engineers, weekly standups, async Discord |
| **Code Security** | Zero SQL injection (parameterized queries), zero CORS issues (unified proxy) |
| **API Endpoints** | 8+ production endpoints (auth, posts, search, messaging, meetups) |
| **Database Tables** | 7 (users, posts, conversations, messages, locations, requests, categories) |
| **Deployment Environment** | AWS EC2 Linux, NGINX, MySQL |

---

## 🔬 Research & Publications

11 peer-reviewed publications in:
- **LLM Structural Pruning**: Joint pruning and parameter sharing for model compression
- **Retrieval-Augmented Generation (RAG)**: Context-guided dynamic retrieval to reduce hallucinations
- **Edge AI Agents**: Decentralized multi-agent systems for spectrum sensing and resource management

[View on Google Scholar →](https://scholar.google.com/citations?user=RQWgrIsAAAAJ&hl=en)

---

## 🎯 What I'm Looking For

Backend/Full-Stack SWE roles where I can:
- Own backend systems end-to-end (architecture → implementation → deployment)
- Solve complex integration and infrastructure problems
- Ship features on tight timelines without sacrificing quality
- Work on problems that scale (concurrency, data pipelines, cloud infrastructure)
- Grow as both an engineer and a technical leader

---

## 📚 Resources & Links

- **GatorMart GitHub**: [https://github.com/CSC-648-SFSU/csc648-sp26-145-team03](https://github.com/CSC-648-SFSU/csc648-sp26-145-team03)
- **Live Demo**: [http://54.193.192.172/](http://54.193.192.172/)
- **Google Scholar**: [https://scholar.google.com/citations?user=RQWgrIsAAAAJ&hl=en](https://scholar.google.com/citations?user=RQWgrIsAAAAJ&hl=en)
- **LinkedIn**: [guiran-liu-232ab228a](https://www.linkedin.com/in/guiran-liu-232ab228a/)
