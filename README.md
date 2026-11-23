## Hi, I'm Victor 👋

**First-year BSc Computer Science student at the University of Westminster, London**

☁️ **AWS Certified Solutions Architect – Associate** · **AWS Certified Cloud Practitioner**

I'm interested in cloud computing, cyber security and software engineering. I learn by building projects, then testing them honestly to find out what actually works.

### 💻 Tech stack

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo%20CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### 🛠️ What I work with

- ☁️ **Cloud:** AWS (Lambda, API Gateway, ECR, IAM, SSM, CloudWatch, SNS, S3, EC2, VPC), Terraform, Docker, GitHub Actions
- ☸️ **Platform:** Kubernetes, ArgoCD (GitOps), Helm, Gateway API (Envoy), cert-manager, Prometheus, Grafana
- 🐍 **Languages:** Python, JavaScript, HTML/CSS, SQL
- ⚛️ **Web:** FastAPI, React, Vite, Node.js, Express
- 🗄️ **Data:** PostgreSQL, Supabase (row-level security), Prisma
- 🔐 **Security:** supply-chain security (Cosign, SBOMs, Trivy), Kyverno and Pod Security policies, NetworkPolicies, Sealed Secrets, least privilege, MFA

### 📌 Featured projects

**🛡️ [aws-guard](https://github.com/macroer16/aws-guard)** — AWS security and cost scanner

A read-only command-line tool that finds security risks and wasted money in an AWS account: public S3 buckets, SSH open to the internet, root without MFA, databases without backups, forgotten volumes still billing. 22 checks mapped to AWS Security Hub (FSBP) controls, a terminal table plus an HTML report with a score out of 100, `--fail-on` for CI, an anonymised AI summary, and a `--demo` mode you can run without AWS. 18 tests against a mocked AWS account (moto) in GitHub Actions.

🧰 Built with: Python, boto3, rich, Jinja2, pytest + moto, ruff, GitHub Actions.

**☸️ [Kubernetes GitOps Platform](https://github.com/macroer16/k8s-gitops-platform)**

A production-style Kubernetes platform run entirely from Git with ArgoCD. It runs my full-stack app with keyless-signed images (Cosign), Kyverno admission policies, Pod Security "restricted", NetworkPolicies, HTTPS through the Gateway API (Envoy Gateway and cert-manager), Sealed Secrets, autoscaling, and Prometheus and Grafana with alerts. Every push builds a fresh 3-node cluster in CI and runs smoke, security-policy and load tests against it.

🧰 Built with: Kubernetes, ArgoCD, Helm, Envoy Gateway, Kyverno, Cosign, Trivy, Prometheus, Grafana, k6, GitHub Actions.

**🔌 [CS Visualiser](https://github.com/macroer16/cs-visualiser)** · [Live site](https://cs-visualiser.vercel.app)

A six-chapter path from a single switch to a working CPU, for first-year Computer Science. Flip bits, drag and wire logic gates, build truth tables, shade Venn diagrams and step through a tiny CPU register by register. Each chapter ends with a challenge that checks your answer, and progress is saved.

🧰 Built with: React, TypeScript, Vite, Tailwind CSS, Vercel.

**🗂️ [StudyBuddy](https://github.com/macroer16/studybuddy)** · [Try the demo](https://studybuddy-vb.vercel.app)

Turns lecture PDFs into a summary, spaced-repetition flashcards, timed mock exams scored by topic, and a weekly plan that works back from your exam date. It uses Claude when an API key is set and a built-in offline generator when not, so the demo needs no sign-up. Accounts use Supabase with row-level security on every table, rate limiting, and server-side PDF validation.

🧰 Built with: Next.js, TypeScript, Supabase, Claude API, Tailwind CSS, Vitest, GitHub Actions.

**🎮 [Neon Runner](https://github.com/macroer16/neon-runner)** · [Play it](https://neon-runner-vb.vercel.app)

A synthwave endless runner in the browser built with Three.js and no game engine: a fixed-step game loop, a seeded procedural track (`?seed=`), input buffering and coyote time, bloom, and sound synthesised with Web Audio. Ships with ARCHITECTURE.md, KNOWN_GAPS.md, a `?debug=1` performance overlay, unit tests and a Playwright screenshot harness.

🧰 Built with: TypeScript, Three.js, Vite, Web Audio, Vitest, Playwright, GitHub Actions.

**🎲 [Dots & Boxes](https://github.com/macroer16/dots-and-boxes)** — minimax AI

The classic game against Easy, Medium and Hard AIs. Hard searches to the end of the game with negamax, alpha-beta pruning and a transposition table in a Web Worker, and finds double-dealing by itself. It beat Medium 20–0 on 3×3 and 11–0 on 4×4. Switching to make/unmake made the search 5× faster.

**🕶️ [Secret Masker](https://github.com/macroer16/secret-masker)** · [Download](https://github.com/macroer16/secret-masker/releases/latest) — Chrome extension

Catches API keys, passwords, card numbers and UK NI numbers when you paste into ChatGPT, Claude or Gemini, and swaps them for typed placeholders like `[AWS_ACCESS_KEY_1]` before the site sees them. When you copy the reply, the real values come back. Luhn-checked cards, mod-97 IBANs and HMRC prefix rules keep false alarms rare. It runs entirely on your device. 26 unit tests plus a real-paste Playwright test.

**✅ [ApplyTrack](https://github.com/macroer16/applytrack)** — Chrome extension

Tracks spring week and internship applications for UK students: save a role from the current tab, a kanban board and sortable table, notifications 3 days and 1 day before online tests and deadlines, stats, and a HireVue prep checklist per application. Manifest V3; all data stays in `chrome.storage.local`. I use it for my own applications.

🧰 Built with: TypeScript, React, Vite, Tailwind CSS, Chrome Extensions API (MV3), Vitest, GitHub Actions.

**📅 [Due: deadline tracker](https://github.com/macroer16/uni-deadline-tracker-api)**

A full-stack app (React front end, FastAPI, PostgreSQL) for coursework deadlines: Argon2 and JWT login, strict per-user data isolation, urgency labels and a private calendar feed. 54 tests (API and front end); the API suite runs against SQLite and real PostgreSQL in CI, alongside a Docker smoke test of the whole stack. AWS infrastructure is in Terraform (Lambda, API Gateway, CloudWatch alarms, a budget alert, and GitHub OIDC deploys with no stored keys).

🧰 Built with: React, TypeScript, Python, FastAPI, SQLAlchemy, PostgreSQL, Prometheus metrics, pytest, Docker, Terraform, GitHub Actions.

**🖥️ [VictorOS — my portfolio](https://github.com/macroer16/personal-website)** · [Live site](https://victor-benson.vercel.app)

My personal site as a working desktop in the browser: a live London sky, draggable windows, a terminal with real commands, a browser running my projects, live GitHub data and a basketball mini-game. Turns into a phone home screen on mobile.

🧰 Built with: Next.js, TypeScript, Tailwind CSS, GitHub API, Vercel.

<details>
<summary><b>More projects</b></summary>

- [Cyber Security Readiness Checker](https://github.com/macroer16/cyber-security-readiness-checker) · [Live demo](https://macroer16.github.io/cyber-security-readiness-checker/): 10-question self-assessment based on UK Cyber Essentials and the NCSC Small Business Guide, with weighted scoring and a ranked action plan (13 tests)
- [Starters and Leavers Access Tracker](https://github.com/macroer16/employee-access-checklist) · [Live demo](https://macroer16.github.io/employee-access-checklist/): Microsoft 365 joiner/leaver access tasks with owners, sign-off, overdue alerts and a CSV audit log (14 tests)
- [CareCircle](https://github.com/macroer16/carecircle) · [Live demo](https://carecircle-self.vercel.app) (in progress): shared care space for families, protected by PostgreSQL row-level security (24 tests)
- [How Computers Store Numbers](https://github.com/macroer16/number-systems-converter) · [Live demo](https://macroer16.github.io/number-systems-converter/): interactive base converter, two's complement and IEEE 754 explorer where you click bits to flip them (17 tests)
- [Backup Monitor](https://github.com/macroer16/backup-monitoring-dashboard) · [Live dashboard](https://macroer16.github.io/backup-monitoring-dashboard/): nightly GitHub Actions job that backs up all my repos, restore-tests every backup and emails me through a GitHub issue if one fails (23 tests)
- [Password and Passphrase Generator](https://github.com/macroer16/password-generator) · [Live demo](https://macroer16.github.io/password-generator/): secure generation with the Web Crypto API, entropy in bits, and a private breach check via Have I Been Pwned (18 tests)
- [Algorithms and data structures practice](https://github.com/macroer16/dsa-practice): my own Python solutions to interview problems, grouped by pattern, with tests and an auto-updating progress table
- [First portfolio site](https://github.com/macroer16/victor-cloud-portfolio) · [Live site](https://macroer16.github.io/victor-cloud-portfolio/): my earlier portfolio

</details>

### 📚 Currently learning

- Python, properly, through my degree, plus [interview problems](https://github.com/macroer16/dsa-practice) every week
- Kubernetes platform engineering: GitOps, policy as code and observability
- Putting my Solutions Architect knowledge into real, deployed projects
- Microsoft Azure

### 🎯 What I'm looking for

Insight programmes, work experience and internships in cloud, cyber security or software engineering.

### 🔗 Find me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Victor%20Benson-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/victor-benson-b2a07b283/)
[![Portfolio](https://img.shields.io/badge/Portfolio-victor--benson.vercel.app-111111?style=for-the-badge&logo=vercel&logoColor=white)](https://victor-benson.vercel.app)

*Build → Test → Fix → Learn*
