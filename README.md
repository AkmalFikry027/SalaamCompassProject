# Salaam Compass

"Guiding communities safely through crisis, together."

## Overview

Salaam Compass is a production-quality, portfolio-grade AI agent platform built for the Google + Kaggle AI Agents Intensive Vibe Coding Capstone Competition. It acts as an intelligent community companion that helps individuals and families navigate crises safely and compassionately.

## Architecture

- Backend: FastAPI, PostgreSQL with pgvector for emergency knowledge.
- Frontend: React, TypeScript, Vite.
- Agents: Built using LangGraph. Features a Supervisor Agent coordinating specialized sub-agents (Weather, Shelter, Medical, Resource, Translation, Communication, Safety).
- Deployment: Docker, Docker Compose, Kubernetes.

## Quick Start

1. Clone the repository:

   ```bash
   git clone https://github.com/AkmalFikry027/SalaamCompassProject.git
   cd SalaamCompassProject
   ```

2. Build and run with Docker Compose:

   ```bash
   docker-compose up --build
   ```

3. Access the application:

   - Frontend: http://localhost:5173
   - Backend API docs (FastAPI): http://localhost:8000/docs


## Notes

- The backend uses PostgreSQL with pgvector for storing emergency knowledge vectors.
- Agents are orchestrated using LangGraph and include specialized sub-agents for different crisis needs.

---

If you'd like, I can also add more sections (Contributing, License, Environment Variables, or Deployment instructions for Kubernetes).