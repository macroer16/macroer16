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

**☸️ [Kubernetes GitOps Platform](https://github.com/macroer16/k8s-gitops-platform)**

A production-style Kubernetes platform run entirely from Git with ArgoCD. It runs my full-stack app with keyless-signed images (Cosign), Kyverno admission policies, Pod Security "restricted", NetworkPolicies, HTTPS through the Gateway API (Envoy Gateway and cert-manager), Sealed Secrets, autoscaling, and Prometheus and Grafana with alerts. Every push builds a fresh 3-node cluster in CI and runs smoke, security-policy and load tests against it.

🧰 Built with: Kubernetes, ArgoCD, Helm, Envoy Gateway, Kyverno, Cosign, Trivy, Prometheus, Grafana, k6, GitHub Actions.

**👪 [CareCircle](https://github.com/macroer16/carecircle)** · [Live demo](https://carecircle-self.vercel.app) (in progress)

A private shared space for families coordinating care: medications, appointments and notes, with invitations and member roles. Each family's data is protected by PostgreSQL row-level security, covered by 24 automated tests that found and fixed a real access gap.

🧰 Built with: React, Vite, Supabase (Postgres, Auth, Edge Functions), PGlite, GitHub Actions, PWA.

**📅 [Due: deadline tracker](https://github.com/macroer16/uni-deadline-tracker-api)**

A full-stack app (React front end, FastAPI, PostgreSQL) for coursework deadlines: Argon2 and JWT login, strict per-user data isolation, urgency labels and a private calendar feed. 54 tests (API and front end); the API suite runs against SQLite and real PostgreSQL in CI, alongside a Docker smoke test of the whole stack. AWS infrastructure is in Terraform (Lambda, API Gateway, CloudWatch alarms, a budget alert, and GitHub OIDC deploys with no stored keys).

🧰 Built with: React, TypeScript, Python, FastAPI, SQLAlchemy, PostgreSQL, Prometheus metrics, pytest, Docker, Terraform, GitHub Actions.

**🛡️ [Cyber Security Readiness Checker](https://github.com/macroer16/cyber-security-readiness-checker)** · [Live demo](https://macroer16.github.io/cyber-security-readiness-checker/)

A 10-question self-assessment based on the UK Cyber Essentials controls and the NCSC Small Business Guide. Weighted scoring, a ranked action plan, results by area and saved history, with 13 automated tests running in GitHub Actions.

🧰 Built with: JavaScript (ES modules), HTML, CSS, Node test runner, GitHub Actions.

**🔐 [Starters and Leavers Access Tracker](https://github.com/macroer16/employee-access-checklist)** · [Live demo](https://macroer16.github.io/employee-access-checklist/)

Tracks Microsoft 365 access for people joining and leaving: tasks with owners and due dates, sign-off with initials, overdue alerts and an audit log exported to CSV. 14 automated tests in GitHub Actions.

🧰 Built with: JavaScript (ES modules), HTML, CSS, Node test runner, GitHub Actions.

<details>
<summary><b>More projects</b></summary>

- [How Computers Store Numbers](https://github.com/macroer16/number-systems-converter) · [Live demo](https://macroer16.github.io/number-systems-converter/): interactive base converter, two's complement and IEEE 754 explorer where you click bits to flip them (17 tests)
- [Backup Monitor](https://github.com/macroer16/backup-monitoring-dashboard) · [Live dashboard](https://macroer16.github.io/backup-monitoring-dashboard/): nightly GitHub Actions job that backs up all my repos, restore-tests every backup and emails me through a GitHub issue if one fails (23 tests)
- [Password and Passphrase Generator](https://github.com/macroer16/password-generator) · [Live demo](https://macroer16.github.io/password-generator/): secure generation with the Web Crypto API, entropy in bits, and a private breach check via Have I Been Pwned (18 tests)
- [Algorithms and data structures practice](https://github.com/macroer16/dsa-practice): my own Python solutions to interview problems, grouped by pattern, with tests and an auto-updating progress table
- [Portfolio website](https://github.com/macroer16/victor-cloud-portfolio) · [Live site](https://macroer16.github.io/victor-cloud-portfolio/): my personal portfolio site

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
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit%20site-111111?style=for-the-badge&logo=github&logoColor=white)](https://macroer16.github.io/victor-cloud-portfolio/)

*Build → Test → Fix → Learn*
