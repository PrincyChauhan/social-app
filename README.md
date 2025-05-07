# 🚀 Social App

A modern full-stack **Social Networking App** built using **Next.js App Router**, **Prisma**, **Clerk**, **TypeScript**, and **UploadThing**. This app leverages the best practices in UI/UX, server components, and full-stack development to deliver a fast, secure, and beautiful social experience.

---

## 🛠 Tech Stack

- **Framework**: [Next.js 14 (App Router)](https://nextjs.org/docs/app)
- **Language**: TypeScript
- **Auth**: [Clerk](https://clerk.dev/)
- **ORM**: [Prisma](https://www.prisma.io/)
- **Database Hosting**: [neon.tech](https://neon.tech/)
- **Uploads**: [UploadThing](https://uploadthing.com/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) & [shadcn/ui](https://ui.shadcn.dev/)
- **Hosting**: Vercel

---

## ✨ Features

- ✅ Authentication & Authorization (Clerk)
- 📁 File Uploads via UploadThing
- 📡 API Integration using Route Handlers
- 🔁 Data Fetching, Caching & Revalidation
- 🧱 Server Components, Layouts, and Server Actions
- 🚥 Dynamic & Static Routes
- ⚡ Optimistic UI Updates
- 🎨 Tailwind + Shadcn for Modern UI
- 🛠️ Error Handling with `error.tsx`, `not-found.tsx`, and `loading.tsx`

---
## 🔧 Environment Variables

Create a `.env` file in the root directory with the following content:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
DATABASE_URL=your_neon_postgres_url
UPLOADTHING_TOKEN=your_uploadthing_token

