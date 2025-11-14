<picture> <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/9113740/201498864-2a900c64-d88f-4ed4-b5cf-770bcb57e1f5.png"> <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/9113740/201498152-b171abb8-9225-487a-821c-6ff49ee48579.png"> </picture> <div align="center"> <strong>Next.js Admin Dashboard Template with Shadcn UI</strong> <br /> Powered by the Next.js App Router <br /><br /> <a href="https://next-shadcn-admin-dashboard.vercel.app/dashboard/default">View Demo</a> </div>

 Overview

This is a modern and customizable Admin Dashboard Template built with cutting-edge technologies:

Framework: Next.js

Language: TypeScript

UI Components: Shadcn UI

Styling: Tailwind CSS v4

Charts: Recharts

Forms: React Hook Form + Zod

Tables: Tanstack Table

State Management: Zustand

Command Palette: Kbar

Routing: Next.js App Router (parallel routes, error boundaries, loading UI)

This template is ideal for:
✔ Admin dashboards
✔ CRM & Finance panels
✔ Analytics dashboards
✔ Professional portfolio / showcase projects
📂 Project Structure
src
├── app                      # Next.js App Router
│   ├── (auth)               # Authentication pages
│   ├── (main)               # Authenticated application
│   │   └── (dashboard)
│   │       ├── default
│   │       ├── crm
│   │       ├── finance
│   │       └── ...
│   └── layout.tsx
├── components               # Reusable UI components
├── hooks                    # Custom hooks
├── lib                      # Utilities & configurations
├── styles                   # Global styles & theme settings
└── types                    # TypeScript definitions
🚀 Features

⚡ Modern Next.js app router structure

🎨 Beautiful UI with Shadcn

🌗 Built-in dark & light themes

📊 Recharts for analytics dashboards

📁 Modular feature-based structure

🧩 Tanstack Tables (sorting, filtering, pagination)

📝 Forms with validation using Zod

🔍 Command palette with Kbar

🧠 Zustand store for global state

❗ Custom error & 404 pages

📄 Pages Included
Page	Description
Dashboard – Default	KPI cards, analytics graphs, clean layout
CRM	UI examples for customer/sales management
Finance	Financial charts, stats, and widgets
Profile	Editable user profile page
Kanban	Drag and drop task board (dnd-kit + Zustand)
Table	Data table using Tanstack Table
Form	React Hook Form + Zod form example
Not Found	Custom 404
Error Page	Global error boundary
📦 Installation
git clone https://github.com/YOUR_USERNAME/next-js-admin-dashboard.git
cd next-js-admin-dashboard
npm install
npm run dev


Then open:

http://localhost:3000

🧰 Scripts
Command	Action
npm run dev	Run development server
npm run build	Build for production
npm run start	Start production build
npm run lint	Run ESLint
📜 License

This project is licensed under the MIT License.
