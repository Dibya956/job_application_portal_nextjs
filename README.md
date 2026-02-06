# Job Application Tracker

A full-stack job application tracking system built with Next.js, featuring a Kanban board interface for managing your job search. This project is part of a YouTube tutorial series where you'll learn how to build this application step by step.



## 🛠️ Tech Stack

- **Framework**: Next.js 16 (App Router)
- **Language**: TypeScript
- **UI Library**: React 19
- **Styling**: Tailwind CSS 4
- **Database**: MongoDB with Mongoose
- **Authentication**: Better Auth
- **Drag & Drop**: dnd-kit
- **UI Components**: Radix UI
- **Icons**: Lucide React

## 🚀 Getting Started


### Installation


1. Install dependencies:

```bash
npm install
```

2. Create a `.env.local` file in the root directory:

```env
MONGODB_URI
BETTER_AUTH_URL
NEXT_PUBLIC_BETTER_AUTH_URL
BETTER_AUTH_SECRET
```

3. Run the development server:

```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in browser.




## 📖 Project Structure

```
job-application-tracker/
├── app/                    # Next.js App Router pages
│   ├── api/               # API routes
│   ├── dashboard/         # Main dashboard page
│   └── sign-in/           # Authentication pages
├── components/            # React components
│   ├── ui/               # Reusable UI components
│   └── kanban-board.tsx  # Main Kanban component
├── lib/
│   ├── actions/          # Server actions
│   ├── auth/             # Authentication setup
│   ├── hooks/            # Custom React hooks
│   ├── models/           # Mongoose models
│   └── db.ts             # Database connection
└── scripts/              # Utility scripts
    └── seed.ts           # Database seeding
```
## Deployed Link
 Open [Link](https://job-application-portal-nextjs.vercel.app) in browser.
