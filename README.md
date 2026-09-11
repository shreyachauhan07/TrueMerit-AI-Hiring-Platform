# TrueMerit — AI-Assisted Hiring Platform

TrueMerit is a collaborative full-stack hiring platform that explores merit-oriented candidate evaluation using verified credentials and technical signals.

## What it demonstrates

- **AI-assisted certificate verification** using Google Gemini
- **Merit scoring** using signals such as GitHub activity, repository/project quality, academic performance and verified certifications
- **Separate student and recruiter workflows**
- **Authentication and protected application flows**
- **Resume and document management**
- **Full-stack architecture** across React, Node.js, Express and MongoDB

## Tech Stack

| Layer | Technologies |
|---|---|
| Frontend | React, Vite, Tailwind CSS, Heroicons |
| Backend | Node.js, Express.js |
| Database | MongoDB, Mongoose |
| AI | Google Gemini |
| Authentication | JWT, secure cookies |

## My Contribution

This was a **team project**. My primary responsibility was **frontend engineering and UI/UX** — structuring the user-facing application, building dashboard and interface components, and connecting frontend flows with the platform's backend APIs.

The backend and AI systems were developed collaboratively by the team, so this repository is presented as evidence of **full-stack collaboration and frontend engineering**, rather than as an independent claim over every subsystem.

## Product Flow

```text
                 TrueMerit
                    │
             Authentication
                    │
          ┌─────────┴─────────┐
          │                   │
       Student             Recruiter
          │                   │
   Profile + Docs       Candidate Review
          │                   │
          └─────────┬─────────┘
                    │
          Verification + Scoring
                    │
             Hiring Insights
```

## Why this project matters

TrueMerit combines application engineering with AI-assisted verification to explore a more structured approach to candidate evaluation. It demonstrates experience with **React-based product development, API-integrated interfaces, authentication, data-driven workflows and collaborative full-stack development**.

## Project Context

Built collaboratively for educational and portfolio purposes. Individual responsibilities are stated explicitly above.

## Local Development

### Backend

```bash
cd backend
npm install
npm run dev
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

Configure the required MongoDB, JWT and Gemini credentials through environment variables before running the application.
