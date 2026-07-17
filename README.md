<div align="center">

# ðï¸ HIKARI PropTech Starter

**Template de dÃ©marrage SaaS PropTech â React + Tailwind + Base44 + Stripe**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE) [![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)](https://react.dev/) [![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)](https://vitejs.dev/) [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/) [![Base44](https://img.shields.io/badge/Base44-000000)](https://base44.com/) [![Stripe](https://img.shields.io/badge/Stripe-635BFF?logo=stripe&logoColor=white)](https://stripe.com/) [![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Version](https://img.shields.io/badge/version-v0.1.0-blue)](./CHANGELOG.md)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](./CONTRIBUTING.md)
[![Stars](https://img.shields.io/github/stars/HIKARI-GROUP/hikari-proptech-starter)](https://github.com/HIKARI-GROUP/hikari-proptech-starter)
[![Last Commit](https://img.shields.io/github/last-commit/HIKARI-GROUP/hikari-proptech-starter)](https://github.com/HIKARI-GROUP/hikari-proptech-starter/commits)
[![Discussions](https://img.shields.io/github/discussions/HIKARI-GROUP/hikari-proptech-starter)](https://github.com/HIKARI-GROUP/hikari-proptech-starter/discussions)

[ð Documentation](./docs/) Â· [ðºï¸ Roadmap](./ROADMAP.md) Â· [ð¤ Contributing](./CONTRIBUTING.md) Â· [ð» Examples](./examples/) Â· [ð§ª Tests](./tests/) Â· [ð¤ AI](./ai/) Â· [ð¼ Careers](./CAREERS.md)

</div>

---

## ð Overview

A production-ready SaaS starter template for PropTech applications. Includes auth, payments, dashboard, SEO, and the HIKARI design system.

## â¨ Features

- ð Authentication (email + Google OAuth + OTP)
- ð³ Stripe subscriptions
- ð Dashboard layout
- ð¨ HIKARI design system (dark theme)
- ð SEO optimized (meta tags, sitemap)
- ð± Responsive (mobile + desktop)
- ð¤ AI-ready (LLM integration patterns)

## ðï¸ Architecture

```mermaid
graph TD
    subgraph "HIKARI HIKARI PropTech Starter"
        A[Frontend] --> B[Backend]
        B --> C[Database]
        B --> D[Integrations]
        B --> E[AI/LLM]
    end
```

See [Architecture](./docs/Architecture.md) for full details.

## ð Installation

```bash
npx degit HIKARI-GROUP/hikari-proptech-starter my-proptech
```

## ð Usage

```javascript
cd my-proptech
npm install
npm run dev
```

## ð Project Structure

```
hikari-proptech-starter/
âââ src/
â   âââ pages/          # React pages
â   âââ components/     # UI components
â   âââ lib/            # Utils & hooks
â   âââ api/            # Base44 client
â   âââ index.css       # Design tokens
âââ base44/
â   âââ entities/       # Database schemas
â   âââ functions/      # Backend functions
âââ .github/
```

## ð ï¸ Technologies

- React 18
- Vite
- Tailwind CSS
- Base44
- Stripe
- TypeScript

## ð Documentation

| Document | Description |
|---|---|
| [Architecture](./docs/Architecture.md) | System architecture and design decisions |
| [Backend](./docs/Backend.md) | Backend services and API |
| [Frontend](./docs/Frontend.md) | Frontend architecture |
| [Database](./docs/Database.md) | Database schema and operations |
| [API](./docs/API.md) | API conventions |
| [Authentication](./docs/Authentication.md) | Auth flows |
| [Security](./docs/Security.md) | Security practices |
| [Deployment](./docs/Deployment.md) | Deployment guide |
| [Coding Standards](./docs/Coding-Standards.md) | Code conventions |
| [Testing](./docs/Testing.md) | Testing guide |
| [CI-CD](./docs/CI-CD.md) | CI/CD pipeline |
| [Git Workflow](./docs/Git-Workflow.md) | Branching & PR process |
| [Onboarding](./docs/Developer-Onboarding.md) | Developer onboarding |
| [Environment](./docs/Environment.md) | Environment setup |

## ðºï¸ Roadmap

See [ROADMAP.md](./ROADMAP.md) for our full vision.

## ð¤ Contributing

We welcome contributions! Please read [CONTRIBUTING.md](./CONTRIBUTING.md) first.

- ð [Report a bug](https://github.com/HIKARI-GROUP/hikari-proptech-starter/issues/new?labels=bug)
- ð¡ [Request a feature](https://github.com/HIKARI-GROUP/hikari-proptech-starter/issues/new?labels=enhancement)
- ð [Improve docs](https://github.com/HIKARI-GROUP/hikari-proptech-starter/issues/new?labels=documentation)
- ð [Good first issues](https://github.com/HIKARI-GROUP/hikari-proptech-starter/labels/good%20first%20issue)

## ð License

MIT Â© HIKARI GROUP

## ð¼ Careers

We're hiring! See [CAREERS.md](./CAREERS.md) for open positions.

## ð Links

- ð¢ [HIKARI GROUP](https://github.com/HIKARI-GROUP)
- ð [Website](https://hikari-group.tech)
- ð¼ [LinkedIn](https://www.linkedin.com/company/hikari-group)
- ð§ [Contact](mailto:contact@hikari-group.tech)

---

<div align="center">
  <sub>Built with â¤ï¸ by <a href="https://github.com/HIKARI-GROUP">HIKARI GROUP</a></sub>
</div>
