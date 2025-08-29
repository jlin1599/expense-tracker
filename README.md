Set-Content -Path README.md -Value @"
# Expense Tracker

## Overview
A personal expense tracking web application that helps users log, categorize, and analyze spending. It gives clear insights into where money goes and helps you stay on budget.

## Problem Statement
People struggle to track daily expenses. Existing solutions can be bloated or not customizable. This app aims to be lightweight and focused on essentials.

## Target Users
- College students on tight budgets
- Young professionals tracking monthly spending
- Families sharing categorized expenses
- Anyone new to budgeting

## Core Features (MVP)
- [ ] Add expense (amount, category, date, note)
- [ ] List & search expenses
- [ ] Category tags (food, transport, bills, etc.)
- [ ] Monthly/weekly summaries
- [ ] Data persistence (local first)
- [ ] Responsive UI

## Technical Stack
| Layer       | Technology              | Justification |
|------------|--------------------------|---------------|
| Frontend   | React                    | Ubiquitous, component-based |
| Styling    | TailwindCSS              | Fast, consistent styling |
| Type Safety| TypeScript               | Fewer runtime bugs |
| State      | React Context / Zustand  | Simple global state |
| Data       | Local (then SQLite/PG)   | Start simple; migrate later |
| Deployment | Vercel                   | Easy, free tier |

## Project Timeline
- **Week 1**: Repo, docs, ADRs, roadmap
- **Week 2**: Expense form + list (React)
- **Week 3**: TypeScript + validation
- **Week 4**: Categories, filters, sorting
- **Week 5**: Summaries + charts
- **Week 6**: SQLite persistence
- **Week 7**: Auth + multi-user
- **Week 8**: Deploy to Vercel
- **Week 9**: Tests + bugfix
- **Week 10**: Final docs + demo

## Getting Started
\`\`\`bash
# (App code starts Week 2+)
npm install
npm run dev
\`\`\`

## Development Process
- Branches: \`main\`, \`develop\`, \`feature/*\`
- Weekly ADRs for big decisions
- Update roadmap + README weekly

## Architecture Decisions
See [docs/decisions](./docs/decisions).

## Contributing
Open issues or PRs with suggestions.

## Learning Goals
- [ ] TypeScript + React
- [ ] ADR writing
- [ ] State management
- [ ] GitHub workflow (branches/PRs)
- [ ] Deploying to Vercel

## Author
**Jackie Lin**  
- GitHub: https://github.com/jlin1599  
- LinkedIn: https://www.linkedin.com/in/jackielin159/

## License
MIT

## Acknowledgments
- ADR patterns, Markdown guides, React/Tailwind docs
"@
