<p align="right">
  <a href="./README.md">한국어</a> | <b>English</b>
</p>

<div align="center">

# Junseop Kim | Agentic Software Engineer

### I design systems that enable AI agents to develop software reliably

### within consistent rules and rigorous verification processes.

<br>

`Agentic Engineering` · `Android` · `Backend` · `Web` · `DevOps` · `C++` · `MFC` · `OpenCV`

</div>

---

## 👋 About Me

Hello, I'm Junseop Kim, an Agentic Software Engineer focused on reducing recurring challenges in AI-assisted development—**context loss**, **unpredictable quality**, **unintended code changes**, and **maintenance issues**—through carefully designed development harnesses.

I build development environments where agents work with sufficient context and limited permissions, and where their output is verified against clear criteria. I achieve this through role-specific agents, persistent instructions, reusable skills, execution hooks, and verification gates. These systems enable a single developer to reliably handle a broader scope spanning **Android, backend, web, and deployment**.

My experience includes computer vision, Windows applications, web development, backend systems, and server operations. I have consistently translated diverse requirements into working software, with an emphasis on solving real problems rather than merely creating polished interfaces.

<br>

---

# 🚀 Current Work

## 🚑 EMS Platform

> An integrated emergency medical response platform combining an Android app for field responders, an administrative web application, a FastAPI backend, and the deployment environment.

The platform manages the entire workflow—from emergency event creation and dispatch to hospital transport, vital-sign and device-status monitoring, and integration with external systems.

As the sole developer, I used agentic engineering to deliver features across Android, backend, and web, while also handling system integration, verification, deployment, and operations. To manage these different technology domains under consistent standards, I designed a project-specific agentic development harness.

### 🛠️ My Role & Responsibilities

* Developed a Kotlin-based Android field response application
* Built FastAPI and PostgreSQL backend APIs with real-time status processing
* Integrated authentication and data contracts between the Android app and backend
* Developed and integrated administrative web features using React and TypeScript
* Unified data flows across emergency events, dispatch stages, vehicles, devices, and external systems
* Automated builds and deployments with Docker and Jenkins
* Implemented health checks, incident alerts, and deployment and operations history tracking
* Performed integration testing and production-environment verification across Android, backend, and web

### 🤖 Agentic Engineering

* Separated roles and permissions among specialized Android, backend, and web subagents and read-only review agents
* Maintained architecture and execution context through persistent instructions at the root and subproject levels, together with task-specific skills
* Controlled parallel work and change scope through staged delegation, worktree isolation, and execution hooks
* Established a verification pipeline connecting builds, tests, contract gates, and independent reviews

<br>

---

## 🖥️ [SageTaechang](https://github.com/JakeKim4926/SageTaechang)

> A Windows business automation application that integrates recurring spreadsheet checks, price lookup, document generation, and file validation into a single workflow for printing and document operations.

I analyzed the client's real-world workflows and requirements and managed the complete development lifecycle, from application design and implementation to verification and deployment.

### 🛠️ My Role & Responsibilities

* Identified repetitive tasks and manual validation points
* Designed and developed a Windows desktop application using C++20 and MFC
* Separated the UI, business logic, and data access layers
* Managed pricing, user, and sorting-rule data with SQLite
* Automated Excel and document workflows through PowerShell and Office integration
* Implemented generation of accounts-receivable statements, delivery notes, and quotations
* Verified consistency between existing business data and application output
* Improved features and delivered releases based on user feedback

<br>

---

# 🧰 Technologies

| Category                   | Technologies                                                               |
| -------------------------- | -------------------------------------------------------------------------- |
| **Agentic Development**    | Claude Code                                                                |
| **Languages**              | C++ · C# · Python · Java · Kotlin · TypeScript                             |
| **Frameworks & Platforms** | MFC · Win32 · .NET Desktop · Android · FastAPI · Spring Boot · React · Vue |
| **Data & Infrastructure**  | PostgreSQL · MySQL · SQLite · Docker · Jenkins · Linux                     |
| **Computer Vision**        | OpenCV                                                                     |

<br>

---

# 🤖 How I Engineer with Agents

<div align="center">

### Define Goals & Contracts → Implement with Role-Specific Subagents → Automate Verification

### → Conduct Read-Only Reviews → Feed Deployment & Operational Results Back into Development

</div>

Rather than simply giving agents more autonomy, I first define clear boundaries for their **roles, context, permissions, and verification**.

### 🧠 Preventing Context Loss

I use `CLAUDE.md` to establish shared rules and architecture, while skills define their activation conditions, reference documents, execution procedures, and verification methods. This ensures that each subagent receives the context required for its task.

### 🎯 Reducing Quality Variability

Because agent output is inherently nondeterministic, I standardize code rules and test procedures for Android, backend, and web development as reusable skills. Builds, tests, contract verification, and independent code reviews are required completion criteria for every task.

### 🛡️ Preventing Destructive Code Changes

The main agent divides work into Android, backend, and web units and delegates each unit to a specialized subagent. Every agent is restricted to its assigned paths and tool permissions, while pre-execution and Git hooks detect out-of-scope edits and risky changes.

### 🔄 Ensuring Maintainability

Architecture decisions and established rules are maintained as reusable skills and continuously updated checklists. Verification and operational results are incorporated into documentation synchronization, issues, and technical-debt tracking.

<br>

---

# 🧩 Algorithm Practice

* **[Algorithm_CPP](https://github.com/JakeKim4926/Algorithm_CPP)**
  C++ solutions for algorithms and data structures

* **[Algorithm](https://github.com/JakeKim4926/Algorithm)**
  A collection of algorithm solutions written in Java

<br>

---

<div align="center">

### I strive to build reliable software that helps people.

</div>
