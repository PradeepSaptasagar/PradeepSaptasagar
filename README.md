# Pradeep Saptasagar

### Software Development Engineer | AI & Cloud Systems | Python | Java | C/C++ | DSA

I build software systems across **AI, cloud applications, backend development, automation, data structures, and embedded systems**.

My projects range from AI-powered applications and observability platforms to full-stack systems, algorithmic problem solving, cloud workflows, and electronics research.

## Engineering Focus

* Software Development
* Data Structures & Algorithms
* Python and Java
* AI / LLM Applications
* Backend & Full-Stack Development
* Cloud Engineering
* Distributed Systems
* Developer Tools
* Embedded Systems
* Technical Research

## Technologies

**Languages**

Python, Java, C, C++, Bash, SQL

**Software Development**

Django, Django REST Framework, React, REST APIs, PostgreSQL

**AI / ML**

Generative AI, LLMs, RAG, LangChain, AI APIs

**Cloud & Infrastructure**

AWS, Azure, GCP, Docker, Kubernetes, Terraform, GitLab CI/CD

**Systems & Data**

Kafka, PostgreSQL, Linux, Prometheus, Grafana

**Embedded & Simulation**

Embedded C, Arduino, RTOS, MATLAB/Simulink, Keysight ADS

## Featured Engineering Projects

### 🌱 PhytoAtlas

AI-powered plant intelligence platform that creates a persistent Plant Passport from plant images, combining identification, health observations, taxonomy, context, timelines, and change detection.

**Next.js | TypeScript | Gemini | PlantNet | Vercel**

### 🔎 IncidentPilot

AI-assisted observability platform combining application telemetry with AI-supported incident investigation.

**OpenTelemetry | SigNoz | FastAPI | React | PostgreSQL | Docker**

### 🧩 Buganizer Platform

Cloud-native engineering platform concept combining issue management, development workflows, infrastructure, analytics, and AI capabilities.

### 💰 Expense Tracker

Full-stack finance application with REST APIs, PostgreSQL persistence, filtering, and a React frontend.

**Python | Django | DRF | React | PostgreSQL**

### ⚡ TitanBot

A programming and game-agent project exploring state representation, decision making, and heuristic strategies.

### 🤖 AI Applications

* Auto Reply AI Chatbot
* Jarvis Virtual Assistant
* Gemini-based applications

## Problem Solving

I actively work on Data Structures & Algorithms using Python and Java.

Topics include:

* Arrays and Strings
* Linked Lists
* Hashing
* Recursion
* Searching
* Sorting
* Problem Solving
* LeetCode

## Research

My research work focuses on **matrix converters, BLDC motor drives, SPWM, power electronics, and MATLAB/Simulink simulation**.

Published research includes work presented at IEEE ICCUBEA 2026.

## Current Direction

I am focused on becoming a stronger software engineer by combining:

```text
Strong Fundamentals
        +
Systems Thinking
        +
Software Development
        +
AI
        +
Cloud
        +
Continuous Problem Solving
```

I enjoy understanding systems from first principles and turning ideas into working software.

## Connect

GitHub: PradeepSaptasagar
LinkedIn: Pradeep Saptasagar
LeetCode: PradeepSaptasagar
CodeChef: PradeepSaptasagar

---

## **Build systems. Solve problems. Keep learning.**

# FILE: Advance_DSA_Python/README.md

# Advance DSA Python

A hands-on repository for **Data Structures, Algorithms, Python programming, and systematic problem solving**.

The repository organizes implementations by topic and provides a practical space for understanding algorithms through code.

## Topics

* Data Structures
* Algorithms
* Recursion
* Hashing
* Linked Lists
* Searching
* Sorting
* Python Programming
* LeetCode

## Repository Structure

```text
Advance_DSA_Python/
├── DoublyLinkedList_Extras/
├── Doubly_Linked_List/
├── Hashing_Concepts/
├── LeetcodeSolutions/
├── PythonProblems/
├── Recursion/
├── Searching_Algorithms/
├── Sorting/
├── head_tail_recursion.py
├── leetcode_updates.txt
└── updates.txt
```

## Problem-Solving Workflow

```text
Understand
    ↓
Find the pattern
    ↓
Choose the data structure
    ↓
Implement
    ↓
Test edge cases
    ↓
Analyze complexity
    ↓
Optimize
```

## Engineering Goals

This repository is used to strengthen:

* Algorithmic thinking
* Data structure fundamentals
* Time and space complexity analysis
* Clean implementation
* Python fluency
* Competitive programming skills

## Tech

**Python | DSA | Algorithms | LeetCode**

---

# FILE: BuildwithAI-CyberGiants/README.md

# PhytoAtlas 🌱

### AI-powered Plant Intelligence from a Single Leaf

PhytoAtlas transforms a plant image into a persistent **Plant Passport** containing identity, taxonomy, health observations, context, history, and change over time.

The core idea is simple:

> A plant is not a one-time image. It is a changing system with a history.

## What It Does

### Identify

Analyze a plant image and generate plant identity and taxonomy information.

### Understand

Separate visible observations from AI-generated health inference.

### Remember

Maintain a persistent record for a plant across multiple scans.

### Compare

Compare later scans against previous observations.

### Investigate

Ask questions about the plant and its changes.

## Product Flow

```text
Plant Image
    ↓
Identification
    ↓
Plant Passport
    ↓
Health + Context
    ↓
Timeline
    ↓
New Scan
    ↓
Change Detection
    ↓
Investigation
```

## Technology

* Next.js
* TypeScript
* Gemini
* PlantNet
* Vercel
* Browser Storage

## Architecture

```text
Browser
   │
   ▼
Next.js Application
   │
   ├── Scanner
   ├── Plant Passport
   ├── Timeline
   ├── Comparison
   └── Investigation
   │
   ▼
Server API
   │
   ├── PlantNet
   └── Gemini
```

API credentials remain server-side.

## Current Capabilities

* Plant identification
* Taxonomy
* Health observations
* Health inference
* Context reasoning
* Plant history
* Scan comparison
* Investigation chat
* Demo mode
* Vercel deployment

## Planned Evolution

* Persistent cloud storage
* Supabase PostgreSQL
* Botanical RAG with pgvector
* Curated evidence sources
* Weather enrichment
* Quantitative image-change analysis

## Run Locally

```bash
npm install
cp .env.example .env.local
npm run dev
```

Environment variables:

```env
GEMINI_API_KEY=your_key
PLANTNET_API_KEY=your_optional_key
```

---

# FILE: expense-tracker/README.md

# Expense Tracker

A full-stack personal finance application built to explore **backend development, REST APIs, database design, and frontend integration**.

## Architecture

```text
React
  │
  │ REST
  ▼
Django REST Framework
  │
  ▼
PostgreSQL
```

## Features

* Create expenses
* Update expenses
* Delete expenses
* View expenses
* Categorize expenses
* Filter by category
* Filter by date range
* Calculate totals
* Persist data in PostgreSQL

## Technology

**Backend**

* Python
* Django
* Django REST Framework

**Frontend**

* React

**Database**

* PostgreSQL

## API Design

```text
GET     /api/expenses/
POST    /api/expenses/
GET     /api/expenses/{id}/
PUT     /api/expenses/{id}/
DELETE  /api/expenses/{id}/
```

Filtering is handled through API query parameters rather than requiring the frontend to retrieve and process the entire dataset.

## Engineering Concepts

This project focuses on:

* REST API design
* CRUD operations
* Database modelling
* Backend filtering
* Frontend/API integration
* Full-stack application structure

## Tech Stack

```text
Python
Django
Django REST Framework
React
PostgreSQL
```
