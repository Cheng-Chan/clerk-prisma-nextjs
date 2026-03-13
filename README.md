# Next.js Authentication System (Clerk + Prisma + Webhooks)

A modern full-stack authentication system built with **Next.js**, **Clerk**, and **Prisma**.  
This project demonstrates how to implement secure authentication, user synchronization via webhooks, and database persistence.

The application uses **Clerk** for authentication and **Prisma** for database access.  
When a user signs up or updates their profile, **Clerk sends a webhook** to the application. The webhook is exposed locally using **ngrok** so Clerk can reach the local development server.

---

# 🚀 Tech Stack

- Frontend / Backend: Next.js (App Router)
- Authentication: Clerk
- ORM: Prisma
- Database: PostgreSQL / MySQL / SQLite
- Webhook Tunnel: ngrok

---

# ⚙️ Setup & Installation

## 1. Clone the repository

```bash
git clone https://github.com/Cheng-Chan/clerk-prisma-nextjs.git
cd clerk-prisma-nextjs
pnpm install

---

.env

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=l
CLERK_WEBHOOK_SIGNING_SECRET=

DATABASE_URL=
