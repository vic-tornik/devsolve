# DevSolve

**Same problem. Different approaches. Understand the trade-offs.**

DevSolve is a cross-domain coding-pattern platform where developers publish multiple working implementations of the same engineering problem and explain when each approach is appropriate.

## Project status

This repository is being prepared for the professional source release. The application archive has been located and reviewed at a file-manifest level; its source files still need to be imported and validated before this repository can be described as a complete runnable release.

## Planned stack

- Next.js App Router, React and TypeScript
- PostgreSQL with Prisma
- Auth.js with GitHub OAuth
- Tailwind CSS
- Sanitized Markdown and Shiki syntax highlighting
- Optional Upstash Redis rate limiting

## Intended repository layout

```text
app/             Routes, pages and API handlers
components/      Reusable UI components
lib/             Database, security and server actions
prisma/          Schema, migrations and seed data
tests/           Automated tests
docs/            Architecture, setup and operations
```

## Local setup

The exact setup instructions will be finalized after the application source is imported and its package scripts and dependencies are verified.

Never commit real environment files, OAuth secrets, database credentials, or API tokens. Use a local `.env` file and keep it out of version control.

## Engineering standards

- Validate and constrain all user-controlled input on the server.
- Never execute user-submitted code in the application process.
- Keep authentication secrets and database credentials server-side.
- Add tests for security-sensitive input handling and server actions.
- Run linting, type checking, and tests before merging.

## Security

See [SECURITY.md](SECURITY.md) for vulnerability reporting guidance. Do not open public issues containing credentials, personal data, or exploit details.

## License

No license has been selected yet. All rights remain with the project owner; do not assume permission to reuse or redistribute this code.
