# RepoShield - SaaS AI Security Dashboard

RepoShield is a fullstack SaaS project for analyzing the security posture of GitHub repositories.

The goal is to build a practical DevSecOps learning and portfolio project that connects GitHub repositories, runs security checks, calculates risk scores, and turns findings into clear remediation guidance.

## Project Status

This project is currently in early setup phase.

Current progress:

- Local project folder created
- Git repository initialized safely inside the project folder
- Unsafe parent Git root detected and avoided
- Initial `.gitignore` created
- GitHub repository connected

## Planned MVP

The first MVP will include:

- GitHub OAuth login
- Repository import from GitHub
- Manual security scan trigger
- Background scan worker
- Security findings dashboard
- Repository risk score
- AI-assisted remediation suggestions
- Markdown report export

## Planned Tech Stack

- Next.js
- TypeScript
- Tailwind CSS
- PostgreSQL
- Prisma
- Redis / BullMQ
- GitHub API
- OpenAI API
- Docker Compose

## Security Focus

RepoShield is designed around secure handling of sensitive data.

The project must never commit or expose:

- `.env` files
- API keys
- OAuth client secrets
- GitHub tokens
- database credentials
- private repository contents
- discovered secrets from scanned repositories

## Why This Project Exists

Many small teams use GitHub but do not have a dedicated security team. RepoShield is built as a learning project to explore how a real-world security SaaS could help teams understand repository risks and improve their security posture.

## Roadmap

1. Project setup
2. Next.js application scaffold
3. Database and Prisma setup
4. GitHub authentication
5. Repository import
6. Scan queue and worker
7. Security check engine
8. Dashboard UI
9. AI remediation
10. Report export
11. Tests and deployment documentation