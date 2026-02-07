# .github
Central repository for managing common GitHub configurations and contributing guidelines across all projects.
---

[Project CodeGuard](https://github.com/cosai-oasis/project-codeguard) is an open-source, model-agnostic security framework that embeds secure-by-default practices into AI coding agent workflows. It provides comprehensive security rules that guide AI assistants to generate more secure code automatically.

## Why Project CodeGuard?

AI coding agents are transforming software engineering, but this speed can introduce security vulnerabilities. Is your AI coding agent implementation introducing security vulnerabilities?

- ❌ Skipping input validation
- ❌ Hardcoding secrets and credentials
- ❌ Using weak cryptographic algorithms
- ❌ Relying on unsafe functions
- ❌ Missing authentication/authorization checks
- ❌ Missing any other security best practice

Project CodeGuard solves this by embedding security best practices directly into AI coding agent workflows. 

**Before, During, and After Code Generation.**

Project CodeGuard can be used **before**, **during** and **after** code generation. They can be used at the AI agent planning phase or for initial specification-driven engineering tasks. Project CodeGuard rules can also be used to prevent vulnerabilities from being introduced during code generation. They can also be used by automated code-review AI agents. 

For example, a rule focused on input validation could work at multiple stages. It might suggest secure input handling patterns during code generation, flag potentially unsafe user or AI agent input processing in real-time, and then validate that proper sanitization and validation logic is present in the final code. Another rule targeting secret management could prevent hardcoded credentials from being generated, alert developers when sensitive data patterns are detected, and verify that secrets are properly externalized using secure configuration management.

This multi-stage methodology ensures that security considerations are woven throughout the development process rather than being an afterthought, creating multiple layers of protection while maintaining the speed and productivity that make AI coding tools so valuable. 

