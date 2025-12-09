# 🌟 UPLEVEL AI
## AI-Powered Goal & Life Planning System

UPLEVEL AI is a full-stack, AI-enhanced personal development platform that helps users set goals, generate AI-driven plans, manage tasks, track progress, and receive real-time notifications — all through a clean, modern, responsive UI.

This project demonstrates mid-level full-stack capabilities across Backend, Frontend, AI, DevOps, UX/UI, and product architecture.

---

## 🔥 Core Features

### 🎯 Goal & Plan Management
- Create/edit/delete goals  
- AI-generated action plans (Gemini Free Tier)  
- Automatic steps + tasks generation  
- Dashboard progress tracking  

### ⚡ Real-Time
- WebSocket notifications  
- Deadline alerts  
- Task reminders  
- Multi-device sync  

### 📝 Tasks
- Kanban-like task board  
- Daily/weekly task lists  
- Completion tracking  
- Progress logs  

### 🛡 Authentication
- JWT login  
- Google OAuth  
- Role-based (User / Premium / Admin)

---

## 🏗 Tech Stack

### 🟦 Backend — Django + DRF
- Django REST Framework  
- PostgreSQL  
- Redis (cache, pub/sub, rate limit)  
- Celery (scheduled jobs, reminders)  
- MinIO (S3-compatible storage)  
- JWT Authentication  
- Google OAuth  
- Repository + Service Layer architecture  
- Django Channels (WebSockets)  
- SendGrid/Mailgun emails  
- Logging, validation, pagination  
- Dockerized environment  

---

### 🟩 Frontend — React + TypeScript
- React 19 + TS  
- Redux Toolkit  
- RTK Query  
- React Hook Form  
- Material UI (custom theme)  
- Socket.IO  
- Feature-Sliced Architecture  
- Dashboard components  
- Responsive design  
- Charts + progress indicators  
- Admin dashboard  

---

### 🟧 DevOps & Infrastructure
- Docker Compose (Backend, Frontend, DB, Redis, MinIO, NGINX)  
- GitHub Actions CI/CD  
- Pre-commit hooks (black, flake8, isort, mypy)  
- Pytest + Jest + RTL  
- Logging + monitoring  
- Production-ready builds  
- 12-Factor architecture  

---

## 🎨 Design System & Branding

### Tools
- **Figma** → UI kit, components, tokens, flows  
- **Canva AI** → branding, logos, hero images  
- **Cursor AI** → component generation  
- **NotebookLM** → documentation + summaries  

### Deliverables
- Complete branding kit (logo, colors, typography)  
- Component library (buttons, inputs, cards, modals)  
- Dashboard layouts  
- All app screens  
- Dark/Light mode  
- Accessibility-ready UI  

---

## 🤖 AI Integration (FREE)

UPLEVEL AI uses:
- **Google Gemini Free Tier** (primary)  
- **Local models with Ollama** (optional backup)  

Capabilities:
- Generate structured plans  
- Auto-suggest tasks  
- Summarize weekly progress  
- Provide motivational insights  

**No paid tokens required.**

---

## 📂 Project Structure (High-Level)

/backend
/apps
/users
/goals
/plans
/tasks
/notifications
/core
/repositories
/services
/channels

/frontend
/src
/app
/features
/entities
/widgets
/shared
/pages

/design
/figma
/branding
/docs

---

## 🗺 Roadmap

### ✔ Phase 0 — Setup & Design
- Repo setup, dependencies  
- Django + React init  
- Environment setup  
- Figma + Canva moodboard  
- ERD + system flows  

### ✔ Phase 1 — Backend Foundations
- DRF setup  
- PostgreSQL connection  
- JWT + Google OAuth  
- Repositories + Services  
- Goals CRUD  

### ✔ Phase 2 — AI Plan Generation
- Connect Gemini/local models  
- Prompt engineering  
- Parse → steps/tasks  
- Save to DB  
- `/goals/{id}/generate-plan` endpoint  

### ✔ Phase 3 — Tasks & Progress
- Task CRUD  
- Daily/weekly views  
- Completion logic  
- Dashboard metrics  
- Progress logs  

### ✔ Phase 4 — Notifications
- Django Channels  
- Celery reminders  
- Notification DB  
- Unread counter  
- LocalStorage sync  

### ✔ Phase 5 — Frontend Core
- MUI theme  
- Layout & routing  
- Landing page  
- Dashboard  
- AI plan viewer  
- Task board  
- RHF forms  
- Responsive UI  

### ✔ Phase 6 — Admin Panel + Design System
- User/goal management  
- Statistics & charts  
- Component library  
- Figma documentation export  

### ✔ Phase 7 — Deployment
- Docker Compose full setup  
- Backend → Render  
- Frontend → Netlify  
- NGINX reverse proxy  
- Domain + SEO  
- GitHub Actions  

### ✔ Phase 8 — Final Polish
- Animations  
- UI cleanup  
- Light/Dark mode  
- Accessibility  
- README polish  
- Screenshots  
- Demo video  
- Portfolio PDF  

---

## 🧪 Testing
- Backend → Pytest  
- Frontend → Jest + RTL  

---

## 🌐 Deployment Targets
- Backend → Render  
- Frontend → Netlify  
- Storage → MinIO  
- Optional CDN  

---

## 👑 Author
**Dean Stark**  
Full-Stack Developer • AI-Powered Builder  
Using ChatGPT • Gemini • Cursor • NotebookLM • Docker • Django • React  

---

## ⭐ Support
If you like this project, please ⭐ the repo.  
Every star helps the project shine brighter.
