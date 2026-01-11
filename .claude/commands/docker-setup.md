---
description: Generate complete Docker setup - Dockerfile + Docker Compose + configs for Python applications
---

# Full Stack Docker Setup

Generate a complete Docker setup for your Python application in one go.

## What This Command Does

This command will help you create:
1. A production-ready **Dockerfile** with multi-stage builds and security best practices
2. A complete **docker-compose.yml** for multi-service orchestration
3. Supporting files: `.env`, `.dockerignore`
4. Complete setup and deployment instructions

## Getting Started

To create your complete Docker setup, I need to understand your application. Please answer these questions:

### Application Questions:
1. **What Python framework are you using?** (Flask, Django, FastAPI, Streamlit, CLI tool, etc.)
2. **Do you have a requirements.txt or pyproject.toml?**
3. **What port should the application run on?**
4. **Does your app need any system dependencies?** (PostgreSQL client, image libraries, etc.)

### Infrastructure Questions:
5. **Which database do you need?** (PostgreSQL, MySQL, MongoDB, SQLite, none)
6. **Do you need caching?** (Redis, Memcached, none)
7. **Do you have background workers?** (Celery, RQ, none)
8. **Any additional services?** (Nginx, message queues, etc.)

### Environment Questions:
9. **Is this for development, production, or both?**
10. **What should the project/container be named?**

## What You'll Receive

After answering these questions, I will generate:

### 1. Dockerfile
- Multi-stage build for minimal image size
- Non-root user for security
- Health checks for web applications
- Proper dependency caching
- Framework-specific optimizations

### 2. docker-compose.yml
- All required services configured
- Health checks for all services
- Named volumes for data persistence
- Proper networking between services
- Environment variable management

### 3. .env File Template
- All required environment variables
- Secure default placeholders
- Documentation comments

### 4. .dockerignore
- Optimized for Python projects
- Excludes unnecessary files from build context

### 5. Instructions
- Build commands
- Run commands
- Common docker-compose operations
- Troubleshooting tips

## Example Output Structure

```
your-project/
├── Dockerfile           # Production-ready Dockerfile
├── docker-compose.yml   # Multi-service orchestration
├── .env                 # Environment variables (template)
├── .dockerignore        # Build context exclusions
└── README-docker.md     # Setup instructions (optional)
```

## Ready to Start?

Tell me about your application by answering the questions above, or simply describe your project and I'll ask clarifying questions as needed.

**Example:** "I have a FastAPI application with PostgreSQL database and Redis for caching. I need both development and production configurations."