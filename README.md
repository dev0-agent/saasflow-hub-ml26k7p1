# SaaSflow Hub

> The command center for your SaaS portfolio.

SaaSflow Hub is a dashboard application designed to help indie developers and agencies manage their software portfolio. It unifies project tracking, financial health (MRR vs Costs), and deployment statuses into a single, relational interface.

## Tech Stack

- **Framework:** Next.js 14+ (App Router)
- **Language:** TypeScript
- **Database:** SQLite (via Prisma ORM)
- **Styling:** Tailwind CSS
- **Components:** Shadcn/ui
- **State/Data:** Server Actions & React Server Components

## Features

- **Portfolio Overview:** See all your apps in one grid with live status indicators.
- **Financial Tracking:** Log MRR and hosting costs to calculate profit per project.
- **Project Management:** Built-in todo lists for every project.
- **Deployment Logs:** Track version history and deployment stability.
- **Aggregate Metrics:** View total business revenue and costs at a glance.

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/saasflow-hub.git
   cd saasflow-hub
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Setup Database**
   ```bash
   npx prisma generate
   npx prisma db push
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Open the app**
   Visit [http://localhost:3000](http://localhost:3000)

## Documentation

- [TASKLIST.md](./TASKLIST.md) - Progress tracking
- [LEARNINGS.md](./LEARNINGS.md) - Dev notes and architectural decisions
- [.dev0/RULES.md](./.dev0/RULES.md) - AI coding guidelines