# Askademia

A modern academic question-and-answer platform built with  **Next.js 14**, **Clerk**, **ShadCN UI**, **Prisma**, and **UploadThing** , designed to connect students, educators, and researchers in a collaborative learning environment.

![Next.js](https://img.shields.io/badge/Next.js-14-blue?logo=nextdotjs)
![Clerk](https://img.shields.io/badge/Auth-Clerk-blueviolet?logo=clerk)
![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-3.x-06b6d4?logo=tailwindcss)
![Prisma](https://img.shields.io/badge/Prisma-ORM-2d3748?logo=prisma)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178c6?logo=typescript)

---

## ✨ Features

- 🔐 **Authentication** with Clerk (Sign in / Sign up / Middleware Protected Routes)
- 🎨 **Modern UI** with ShadCN, TailwindCSS & Lucide Icons
- 🧠 **Type-safe database access** using Prisma ORM
- ☁️ **File uploads** via UploadThing
- 🌙 **Dark/Light mode toggle** with `next-themes`
- ⚡ App Router + Server Actions + `use client` components

---

## 🧩 Tech Stack

| Layer           | Tech                        |
|-----------------|-----------------------------|
| Frontend        | Next.js 14 (App Router)     |
| Styling         | Tailwind CSS, ShadCN UI     |
| Auth            | Clerk                        |
| ORM / Database  | Prisma + PostgreSQL         |
| File Upload     | UploadThing                 |
| Icons           | Lucide React                |
| Language        | TypeScript                  |

---

## Installation
1. Clone the repository
git clone https://github.com/mmarseal/Askademia.git
cd Askademia

2. Install dependencies
npm install
# or
yarn install
# or
pnpm install
# or
bun install

3. Setup your .env file with:
# - CLERK keys
# - DATABASE_URL
# - UPLOADTHING_TOKEN

npx prisma generate
npm run dev

4. Run the development server:
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev

5. Open http://localhost:3000 in your browser

📸 Screenshots

