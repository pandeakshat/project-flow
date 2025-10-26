# ProjectFlow

> Centralized project tracking system for managing all PandeAkshat projects.

---

## 📘 Overview

ProjectFlow is a lightweight internal management tool designed to track progress, milestones, and dependencies across multiple active projects. It brings visibility and structure to your portfolio, ensuring that development remains organized, measurable, and consistent with long-term goals.

- Type: Web App  
- Tech Stack: Next.js, Supabase, TailwindCSS  
- Status: Active  

---

## ⚙️ Features

- CRUD operations for projects, milestones, and updates.  
- Dashboard view with project cards and progress tracking.  
- Scalable backend using Supabase for real-time data sync.  

---

## 🧩 Architecture / Design

```text
projectflow/
├── pages/
│   ├── index.tsx
│   ├── projects/
├── components/
│   ├── ProjectCard.tsx
│   └── ProgressBar.tsx
├── lib/
│   └── supabaseClient.ts
└── README.md
