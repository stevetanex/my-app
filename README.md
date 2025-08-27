## Tech Stack

- Backend: Node.js, Express
- Database: PostgreSQL (accessed via Prisma)
- Frontend: React (Create React App)
- ORM: Prisma
- Authentication: JWT (Access + Refresh), bcryptjs / crypto
- Rate Limiting & Validation: express-rate-limit, express-validator
- Security Middleware: helmet, cookie-parser

## Setup & Installation
## 4. Document Folder Layout

Provide a simple tree or list of the project structure:

```markdown
## Folder Layout

my-app/
├── client/           # React frontend
│   ├── public/
│   └── src/
├── server/           # Node.js backend
│   ├── prisma/       # Schema & migrations
│   └── src/
│       ├── utils/    # Security helpers
│       ├── index.js  # Express entrypoint
│       └── routes/
├── README.md         # This file
└── Evidence.md       # Links to screenshots/logs
