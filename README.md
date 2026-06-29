<h1 align="center">Hey, I'm Tayro Arce 👋</h1>

<p align="center">
  <strong>Full Stack Developer & AI Automation Engineer</strong>
  <br />
  I build production-ready web products and intelligent automation pipelines that optimize business operations.
  <br /><br />
  🟢 <strong>Open to Work</strong> &nbsp;·&nbsp; 🇨🇷 Based in Costa Rica
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/tayro-arce-b0a686372">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:tayroarce@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

---

## ⚡ Executive Summary

I am a product-driven engineer specializing in modern web applications and scalable enterprise automation. I bridge the gap between robust full-stack software and intelligent infrastructure, ensuring code doesn't just pass tests, but directly eliminates operational bottlenecks.

- 📈 **Focus:** High-availability architectures, state-driven backend pipelines, and clean client interfaces.
- 🛠️ **Infrastructure Focus:** Decoupled self-hosted services, relational data integrity, and secure multi-role access controls.
- 🎯 **Goal:** Joining a high-performance engineering team where I can ship high-impact code, tackle complex API architectures, and scale systems.

---

## 🎯 Featured Projects (Pinned Below 📌)

### 1. Plataforma Digital Fundación Exalumnos UCR — AI-Driven Talent Matching Engine
A full-stack MVP designed to bridge the gap between academic talent and market placement by processing and matching alumni profiles using intelligent data pipelines.
- **The Challenge:** Handling multi-role user flows (admins, students, alumni) with sensitive financial verification and employment documents while maintaining strict data isolation and zero leaks.
- **The Solution:** Built a Next.js 14 architecture utilizing Server Actions where authentication is verified strictly on the server-side via `@supabase/ssr` to force Row Level Security (RLS) evaluation. Implemented passwordless Magic Links with NextAuth v5 + Resend, and an asynchronous ATS optimization engine that streams real-time customized CV adaptations via Anthropic's Claude Sonnet.
- **Key Architecture Choice:** Implemented strict server-only Supabase clients to guarantee database-level constraints can never be bypassed via client-side API injections.
- 🛠️ *Next.js 14 (App Router)* · *TypeScript* · *Supabase (PostgreSQL + RLS)* · *Claude Sonnet API* · *NextAuth v5* · *TailwindCSS*

### 2. Chamos House — Real-Time Kitchen Display (KDS) & Restaurant OS
A complete digital management ecosystem that digitizes fast-food restaurant operations, eliminating human error from paper notes and manual cash closings.
- **The Challenge:** Synchronizing real-time asynchronous multi-channel data flows (WhatsApp automated orders, kitchen display updates, and live financial dashboards) without state conflicts or webhook data loss.
- **The Solution:** Engineered a decoupled backend using Node.js and Express following a strict Layered Architecture (Routes ➔ Controller ➔ Service ➔ Model). Orders are captured via n8n workflows, processed atomically in MySQL, and pushed instantly to a React/Vite Kanban-style KDS board via bidirectional Socket.io events.
- **Key Architecture Choice:** Implemented immutable historical snapshots in the order details schema (`p_unitario`) to isolate financial data integrity from future master-catalog product price updates.
- 🛠️ *Node.js* · *Express* · *React (Vite)* · *TypeScript* · *MySQL (Sequelize ORM)* · *Socket.io* · *n8n Automation* · *Zustand*

---

## 🛠️ Tech Stack

### 🌐 Frontend & Client-Side
![Next JS](https://img.shields.io/badge/Next_JS-black?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-black?style=for-the-badge&logo=framer&logoColor=white)

### 🗄️ Backend, Databases & State Management
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=Sequelize&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&logoColor=white)
![Jest](https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white)

### 🤖 Automation & Intelligent Infrastructure
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Make](https://img.shields.io/badge/Make-6D00CC?style=for-the-badge&logo=make&logoColor=white)
![Meta](https://img.shields.io/badge/Meta_Ecosystem-%230467DF.svg?style=for-the-badge&logo=Meta&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)

### ⚙️ DevOps & Cloud Environment
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/UbuntuServer-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-FF9900?style=for-the-badge&logo=amazons3&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

---

## 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.shion.dev/api?username=tayroarce-lab&theme=dark&hide_border=false&include_all_commits=true&count_private=true" style="max-width: 100%;">
  <br />
  <img src="https://streak-stats.demolab.com/?user=tayroarce-lab&theme=dark&hide_border=false" style="max-width: 100%;">
  <br />
  <img src="https://github-readme-stats.shion.dev/api/top-langs/?username=tayroarce-lab&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact" style="max-width: 100%;">
</p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=tayroarce-lab&icon=0&color=12" alt="Profile Views" />
</p>
