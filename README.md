🚀 AI Career Coach

An intelligent, AI-powered career development platform designed to help users prepare, improve, and succeed in their professional journey.
Built with modern web technologies and production-grade architecture, this app combines AI, data insights, and interactive tools into a seamless experience.

✨ Key Features
🤖 AI-Powered Career Guidance
Personalized career insights based on user profile
Industry-specific trends, demand, and growth analysis
Weekly updated data using background jobs
📄 Smart Resume Builder
Dynamic resume creation with structured inputs
AI-assisted content generation (ATS-friendly descriptions)
Markdown-based editing with live preview
Export resumes as PDF
💼 AI Cover Letter Generator
Generate tailored cover letters using job description
Ready-to-use professional formatting
Editable and reusable templates
🧠 Interview Preparation System
AI-generated quizzes based on selected skills
Real-time scoring and performance tracking
Detailed explanations + improvement suggestions
Historical performance analytics
📊 Industry Insights Dashboard
Market trends, job demand, and salary insights
Top skills and role-based breakdown
Continuously updated via automated cron jobs
🔐 Authentication & User Management
Secure login (Google + Email)
Profile onboarding with skills, experience, and bio
Account & session management

🛠️ Tech Stack
Frontend
Next.js 15 (App Router)
React 19
TypeScript
Tailwind CSS
Radix UI + shadcn components
Recharts (data visualization)
Backend & Database
PostgreSQL (via Prisma ORM)
Inngest (background jobs / cron workflows)
AI Integration
Google Gemini API (@google/generative-ai)
Forms & Validation
React Hook Form
Zod (schema validation)
Authentication
Clerk Auth
Additional Tools
Markdown rendering (react-markdown, @uiw/react-md-editor)
PDF generation (html2pdf.js)
Notifications (sonner)
📂 Project Structure

The project follows a scalable, production-ready architecture:

app/ → Next.js App Router pages & layouts
components/ → Reusable UI components
actions/ → Server actions
lib/ → Utilities & configs
hooks/ → Custom React hooks
prisma/ → Database schema & client
data/ → Static/config data
🎯 Why This Project Stands Out
Combines AI + real-world career workflows
Implements background jobs (cron) — rarely seen in tutorials
Uses modern full-stack architecture (Next.js 15 + Prisma)
Focused on real user value (resume, interview prep, insights)
