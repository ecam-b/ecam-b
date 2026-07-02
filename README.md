# Elian Camilo Angarita

**QA Automation Engineer · SDET · Python**  
I build systems — and the frameworks that test them.

Three years automating test suites for SaaS products in Chile and Canada taught me something most QA engineers don't get to learn: what the code looks like from the inside. I've shipped features in FastAPI and Django, designed indexes, and debugged production incidents — because I sat next to the developers, not across from them. That's my edge.

---

### 🧪 What I've Shipped in QA

**Whis — AI QA Autopilot** *(Adereso, Chile)*  
Internal Python agent with a hybrid architecture (deterministic layer + LLM) that generates E2E test cases automatically. Reduced test creation from **1 hour → 15 minutes per batch**. Adopted by dev and product teams.

**E2E Suite from Zero** *(Adereso)*  
120 manual cases → **220 automated tests** in Playwright + Python with Clean Architecture and POM.  
Regression cycle: **2 days → 35 minutes**.

**AR/CRM Regression Framework** *(Prisma Digital, Canada)*  
Selenium + Python for critical billing and CRM systems. **−70% regression time · −30% recurring incidents.**  
Also optimized internal API queries: **−40% response time**.

---

### 🚀 Featured Project

**[Contámelo — Case Study](https://github.com/elian-camilo/contamelo)**  
*Production SaaS built solo. My QA lab and backend proof of work, in one.*

A debt-tracking app with real users — not a tutorial project. I built it to have a system I understand at every layer, so I could test it that way too.

What's inside from a quality engineering perspective:
- Unit tests mocking at interface boundaries (no framework imports in domain)
- Integration tests against a real PostgreSQL instance with `create_all/drop_all` per test
- CI pipeline (pytest unit + `tsc --noEmit`) before every merge
- A mass assignment vulnerability I introduced, detected, and fixed in production — now documented
- Rate limiting, magic byte file validation, SQL injection defense, and JWT rotation — all tested

**Stack:** Python · FastAPI · SQLModel · PostgreSQL · React 19 · TanStack Query · OpenAI · Whisper · Capacitor (Android) · Docker · Railway · Vercel · Neon  
→ [Live app](https://app.contamelo.com.co) · [Landing](https://contamelo.com.co) · [Case study](https://github.com/elian-camilo/contamelo)

---

### 🛠️ Stack

| Area | Tools |
|---|---|
| **Test Automation** | Playwright · Selenium · Pytest · Postman · POM · Page Screenplay |
| **Languages** | Python (main) · TypeScript · SQL |
| **CI/CD & Infra** | GitHub Actions · Docker · Railway · Vercel |
| **AI applied to QA** | OpenAI API · Whisper · Anthropic API · Claude Code · Prompt Engineering |
| **Backend** | FastAPI · SQLModel · PostgreSQL · Clean Architecture · Alembic |
| **Frontend** | React 19 · TanStack Query v5 · Tailwind v4 · shadcn/ui |
| **Mobile** | Capacitor (Android) |

---

### 🔨 Currently Working On

- Performance testing layer for Contámelo (K6 — load, stress, baseline documentation)
- Mobile E2E suite for the Android app (Maestro + Appium + Python)
- OWASP ZAP security scan against staging with mapped controls

---

### 📫 Let's Talk

- ✉️ ec.angaritas@gmail.com
- 💼 [linkedin.com/in/elian-camilo-angarita](https://www.linkedin.com/in/elian-camilo-angarita/)
- 🌎 100% remote · Colombia (GMT-5) · LATAM, Spain & global teams
- 🗣️ English B2 — comfortable in technical interviews and documentation

**Open to:** QA Automation Engineer · SDET · Test Automation Engineer · Python  
*Also available for backend roles — but QA is where I hit the ground running.*
