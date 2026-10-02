# Campus Event AI System

A portfolio showcase of my contributions to a university team project for an Agentic AI campus management system.

## Overview

The original project is a team-based university management application built with **Python, Flask, HTMX, SQLite, Docker, Ollama, RAG, MCP and GitHub Actions**.

My main area was the **Campus Event Management** feature, but my contributions also included early project structure, frontend work, backend/event functionality, AI integration, testing and CI-related work.

> **Note:** This repository is a portfolio summary of my personal contributions to a team project. The original team repository is private.

## My Contributions

Based on my project work and Git history, I contributed to:

- Building the initial frontend and backend structure
- Creating the early navigation/homepage structure
- Implementing event query functionality
- Developing event management CRUD features
- Improving frontend page styling and navigation
- Integrating MCP-based event tools
- Integrating RAG-based event retrieval
- Implementing grounded AI responses using retrieved event information
- Adding integration tests for the Student 4 release
- Contributing to GitHub Actions CI for release testing

## Campus Event Management

The Campus Event Management module was designed to allow users to work with campus event information through a traditional web interface as well as AI-assisted workflows.

Main components included:

- **Frontend** – event pages, navigation and user interaction
- **Backend** – Flask-based event functionality and APIs
- **Database** – SQLite-based event data
- **MCP integration** – tools that allow the AI layer to interact with event functionality
- **RAG integration** – retrieval of relevant event information before generating responses
- **Testing** – integration and release tests

## AI Architecture

### MCP

The Model Context Protocol (MCP) component exposes event-related tools to the AI system, allowing the model to interact with application functionality instead of relying only on free-text generation.

### RAG

The Retrieval-Augmented Generation (RAG) component retrieves relevant campus event information and provides it as context to the AI system.

This helps produce **grounded responses**: answers based on retrieved project data rather than unsupported model output.

### Grounded AI Response Flow

```text
User query
   |
   v
AI / Ollama
   |
   +----> RAG retrieval ----> relevant event information
   |
   +----> MCP tools --------> application/event actions
   |
   v
Grounded response
```

## Tech Stack

| Area | Technologies |
|---|---|
| Backend | Python, Flask |
| Frontend | HTMX, HTML, CSS, JavaScript |
| Database | SQLite |
| AI | Ollama, RAG, MCP |
| DevOps | Docker, Docker Compose |
| CI/CD | GitHub Actions |
| Testing | Python integration tests |
| Version Control | Git, GitHub |

## Original Team Project Structure

The original application was divided into several student modules:

- Student 1 – Course Management
- Student 2 – Assignment Management
- Student 3 – Campus Resource Management
- **Student 4 – Campus Event Management**
- Student 5 – Career and Internship Management

Shared services included dedicated **MCP** and **RAG** servers used across the application.

## Selected Git History

Examples of my commits in the original project include:

- `Create frontend——demo.html`
- `Add student navigation homepage index.html`
- `V1: Add basic frontend/backend and event query feature`
- `update page style`
- `Complete event management CRUD functionality`
- `Add Student 4 MCP event integration`
- `Add Student 4 RAG event integration`
- `Complete Student 4 Release 1 integration and tests`
- `Student 4 Release 1 MCP and RAG Integration`

These commits show that my work covered both the early application structure and later AI/RAG/MCP integration.

## What I Learned

This project gave me practical experience with:

- Working in a multi-developer Git workflow
- Building and integrating Flask services
- Designing REST-style backend functionality
- Containerising application components with Docker
- Connecting application logic to AI services
- Using RAG to improve response grounding
- Using MCP to expose structured tools to an AI system
- Writing integration tests and working with CI pipelines

## About Me

I am currently completing a **Bachelor of Information Technology at the University of Technology Sydney (UTS)**, majoring in **Software Development and Cybersecurity**.

Expected graduation: **May 2027**

I am interested in **backend development, DevOps, software engineering and AI-enabled systems**.
