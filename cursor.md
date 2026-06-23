# Cursor Project Guide

This file provides context and instructions for AI assistants working in this project.

## Project Overview

- **Name:** test project
- **Purpose:** A Node.js web application built with Next.js and TypeScript.

## Tech Stack

- **Runtime:** Node.js
- **Language:** TypeScript
- **Framework:** Next.js (React)
- **Package Manager:** npm
- **Styling:** (add later — e.g. Tailwind CSS, CSS Modules)
- **Linting:** ESLint (Next.js default setup)

## Project Structure

```
test project/
├── src/
│   ├── app/              # Next.js App Router pages and layouts
│   ├── components/       # Reusable UI components
│   └── lib/              # Utilities and shared logic
├── public/               # Static assets
├── cursor.md             # AI assistant guide (this file)
├── next.config.ts        # Next.js configuration
├── tsconfig.json         # TypeScript configuration
└── package.json          # Project dependencies and scripts
```

## Development Guidelines

- Keep changes focused and minimal.
- Follow existing naming and code style in the repo.
- Add comments only when logic is not obvious.
- Do not commit secrets (API keys, passwords, `.env` files).

## Commands

Add common commands for this project, for example:

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build

# Start production server
npm start

# Run linting
npm run lint
```

## AI Assistant Notes

When working in this project:

1. Read surrounding code before making changes.
2. Prefer small, targeted diffs over large refactors.
3. Ask before adding new dependencies or changing architecture.
4. Run relevant tests or checks after changes when available.

## Conventions

- **Branch naming:** `feature/...`, `fix/...`, `chore/...`
- **Commit messages:** Short, clear, and focused on why the change was made.

---

Update this file as the project evolves so AI assistants stay aligned with your workflow.
