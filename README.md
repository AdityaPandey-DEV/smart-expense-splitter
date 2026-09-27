# Smart Expense Splitter

**AI-powered expense splitting app with smart categorization, analytics, and a premium glassmorphism UI.**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

---

## What It Does

Goes beyond basic splitting with intelligent AI expense categorization, spending trend analysis, and actionable insights.

**Key Features:**
- **Smart Settlements** — minimizes transactions to settle debts
- **AI Categorization** — auto-tags expenses via keyword analysis
- **Spending Insights** — trends, top categories, food spending alerts
- **Interactive Analytics** — Chart.js Doughnut, Line, and Bar charts
- **Offline First** — localStorage persistence with import/export

## Architecture

```
React UI (Dashboard, Groups, Analytics) ↔ AppContext (useReducer Global State)
                                            ├── AI Categorization Engine
                                            ├── Settlement Optimizer
                                            └── localStorage
```

## Tech Stack

| Component | Technology |
|---|---|
| Framework | React + Vite |
| State | React Context + useReducer |
| Visualization | Chart.js |
| UI | CSS Glassmorphism |

## My Role

I designed the state management model, planned the AI categorization engine, and chose the settlement minimization algorithm. Code generation was accelerated using AI tools; state synchronization and localStorage edge cases are mine.

## Quick Start

```bash
git clone https://github.com/AdityaPandey-DEV/smart-expense-splitter.git && cd smart-expense-splitter
npm install && npm run dev
```

---

<div align="center">

*Architected & built by [Aditya Pandey](https://github.com/AdityaPandey-DEV) — AI-augmented development*

</div>
