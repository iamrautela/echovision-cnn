# vibe-ai

**vibe-ai** is an AI-powered platform that generates **full-stack applications** from simple prompts using **programmable AI agents** and **secure cloud sandboxes**.  

Built with the **latest AI-first toolchain**, it leverages **OpenAI, Anthropic, and Grok** for code generation, **Inngest** for background job orchestration, and **Docker** + **E2B** for runtime execution — all while providing a seamless developer experience.

---

## ✨ Key Features

- **🚀 Next.js 15 + React 19** – Modern, blazing-fast web stack.
- **🎨 Tailwind v4 + Shadcn/ui** – Fully customizable, responsive UI.
- **📡 tRPC** – End-to-end type safety for APIs.
- **🔁 Inngest Background Jobs** – Reliable job scheduling & orchestration.
- **🧠 Inngest Agent Toolkit** – Programmable AI agents for code generation.
- **🔐 Clerk Authentication** – Secure sign-in with OAuth & multi-device support.
- **💳 Clerk Billing** – Subscription management & usage-based billing.
- **🧱 AI-Powered Code Generation** – Generate apps, components, and APIs from prompts.
- **🗂️ Live Project Preview** – Shareable URLs with instant updates.
- **🖥️ E2B Cloud Sandboxes** – Safe, isolated runtime environments.
- **🐳 Docker-based Sandboxing** – Reproducible and scalable deployments.
- **🧠 Multi-Model AI Support** – OpenAI, Anthropic, and Grok integration.
- **📦 Prisma + Neon** – Type-safe database with serverless PostgreSQL.
- **🤖 CodeRabbit PR Reviews** – AI-assisted code review & GitHub workflow.
- **🧾 Credit System** – Built-in usage tracking & billing transparency.
- **🧪 Preview & Code Explorer** – Toggle between app preview and generated code.

---

## 📐 Architecture Overview

- **Frontend:** Next.js 15, React 19, Tailwind v4, Shadcn/ui
- **Backend:** tRPC, Inngest, Docker, E2B
- **Database:** Prisma + NeonDB (serverless PostgreSQL)
- **Auth & Billing:** Clerk
- **AI Models:** OpenAI, Anthropic, Grok
- **DevOps:** GitHub Actions, AI-powered PR reviews with CodeRabbit

**Agent Workflow:**
1. User submits prompt → AI agent plans full-stack app.
2. Background jobs handled by **Inngest**.
3. Code generated, tested, and deployed in **E2B sandboxes**.
4. Live preview shared via unique URL.
5. User can view code, request edits, or push via Git.

---

## 🛠️ Getting Started

### Prerequisites
- Node.js 20+
- Docker
- NeonDB account
- Clerk API keys
- Inngest setup
- E2B sandbox credentials

### Installation
```bash
git clone https://github.com/iamrautela/vibe-ai.git
cd vibe-ai
npm install
npm run dev
