---
name: generate-compose
description: Generate a Docker Compose configuration for multi-service applications
---

Invoke the **compose-architect** agent to create a complete Docker Compose setup.

The agent will:
1. Ask about your application architecture and required services
2. Generate a production-ready docker-compose.yml
3. Provide .env file template
4. Give you docker-compose commands
5. Explain how services communicate

Simply invoke the agent and answer the questions:
```
/agent compose-architect
```

Then say: "I need a Docker Compose setup for my application"
