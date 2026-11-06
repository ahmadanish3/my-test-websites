# Engineer Hub ERP
Modern ERP for Engineering Services - Built from GitHub best practices

## Features
- Dashboard with KPIs, Gantt, Utilization
- Projects (CRUD, Status, Progress)
- Engineers (Roles, Skills, Availability)
- Work Orders (Kanban + Table)
- Inventory (Low stock alerts)
- Clients & Ledger

## Tech Stack
- Frontend: React + Tailwind (current MVP as single-file app in index.html)
- Next.js + Prisma ready structure (see /apps)
- DB: PostgreSQL
- Deployment: Vercel / Docker

## How to Run (MVP)
Just open `index.html` or deploy to GitHub Pages:
1. Push this repo to GitHub
2. Settings > Pages > Deploy from main branch

## Next.js Upgrade Path (included scaffold)
```
apps/web -> Next.js app (copy components from index.html)
apps/api -> NestJS API (to be implemented)
packages/db -> Prisma schema
```

## Push to GitHub
```bash
git init
git add .
git commit -m "feat: initial Engineer Hub ERP"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/engineer-hub-erp.git
git push -u origin main
```

## Roadmap
- [ ] Connect Prisma + Postgres
- [ ] Auth (NextAuth)
- [ ] PDF Work Order export
- [ ] Mobile app for field engineers

Built in Sungai Petani, Kedah.
