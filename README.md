# Sameer's World

A Node.js web application built with **Next.js** and **TypeScript**.

## About

This project is a personal web application by **Jyotirmoy Sarker Sameer**. It uses modern JavaScript tooling and is designed to scale with a clean, component-based architecture.

## Tech Stack

| Category        | Technology        |
| --------------- | ----------------- |
| Runtime         | Node.js           |
| Language        | TypeScript        |
| Framework       | Next.js (React)   |
| Package Manager | npm               |
| Environment     | dotenv            |

## Prerequisites

Before you begin, make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v18 or later recommended)
- npm (comes with Node.js)

## Getting Started

### 1. Clone the repository

```bash
git clone <repository-url>
cd test-project
```

### 2. Install dependencies

```bash
npm install
```

### 3. Set up environment variables

Create a `.env` file in the project root:

```env
# Add your environment variables here
```

> **Note:** Never commit `.env` files or secrets to version control.

### 4. Run the development server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

## Available Scripts

| Command         | Description                          |
| --------------- | ------------------------------------ |
| `npm install`   | Install project dependencies         |
| `npm run dev`   | Start the development server         |
| `npm run build` | Build the app for production         |
| `npm start`     | Start the production server          |
| `npm run lint`  | Run ESLint                           |
| `npm test`      | Run tests                            |

## Project Structure

```
test-project/
├── src/
│   ├── app/              # Next.js App Router pages and layouts
│   ├── components/       # Reusable UI components
│   └── lib/              # Utilities and shared logic
├── public/               # Static assets
├── cursor.md             # AI assistant project guide
├── package.json          # Dependencies and scripts
└── README.md             # Project documentation
```

## Development Guidelines

- Keep changes focused and minimal.
- Follow existing naming and code style in the repo.
- Add comments only when logic is not obvious.
- Do not commit secrets (API keys, passwords, `.env` files).

## Author

**Jyotirmoy Sarker Sameer**

## License

ISC
