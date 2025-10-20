---
name: generate-dockerfile
description: Generate an optimized, production-ready Dockerfile for Python applications
---

Invoke the **dockerfile-expert** agent to create an optimized Dockerfile.

The agent will:
1. Ask about your Python application (framework, dependencies, ports)
2. Generate a multi-stage Dockerfile with security best practices
3. Provide .dockerignore file
4. Give you build and run commands
5. Optionally build the image and verify it works

Simply invoke the agent and answer the questions:
```
/agent dockerfile-expert
```

Then say: "I need a Dockerfile for my Python application"
