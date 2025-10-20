---
name: full-stack-setup
description: Generate complete Docker setup - Dockerfile + Docker Compose + configs
---

Generate a complete Docker setup for your application in one go.

This command will:
1. First invoke **dockerfile-expert** to create your Dockerfile
2. Then invoke **compose-architect** to create docker-compose.yml
3. Generate all supporting files (.env, .dockerignore, etc.)
4. Provide complete setup instructions

Process:
1. Answer questions about your Python application
2. Answer questions about required services (database, cache, etc.)
3. Receive complete Docker configuration

Start by describing your application and what services it needs.
