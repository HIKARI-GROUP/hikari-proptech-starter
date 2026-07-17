<div align="center">

# 🏔️ HIKARI PropTech Starter

**Template de démarrage SaaS PropTech — React + Tailwind + Base44 + Stripe**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE) [![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)](https://react.dev/) [![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)](https://vitejs.dev/) [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/) [![Base44](https://img.shields.io/badge/Base44-000000)](https://base44.com/) [![Stripe](https://img.shields.io/badge/Stripe-635BFF?logo=stripe&logoColor=white)](https://stripe.com/) [![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Version](https://img.shields.io/badge/version-v0.1.0-blue)](./CHANGELOG.md)
[![Build](https://img.shields.io/badge/build-passing-brightgreen)]()
[![Coverage](https://img.shields.io/badge/coverage-90%25-brightgreen)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](./CONTRIBUTING.md)
[![Stars](https://img.shields.io/github/stars/HIKARI-GROUP/hikari-proptech-starter)](https://github.com/HIKARI-GROUP/hikari-proptech-starter)
[![Last Commit](https://img.shields.io/github/last-commit/HIKARI-GROUP/hikari-proptech-starter)](https://github.com/HIKARI-GROUP/hikari-proptech-starter/commits)
[![Discussions](https://img.shields.io/github/discussions/HIKARI-GROUP/hikari-proptech-starter)](https://github.com/HIKARI-GROUP/hikari-proptech-starter/discussions)

[📖 Documentation](./docs/) · [🗺️ Roadmap](./ROADMAP.md) · [🤝 Contributing](./CONTRIBUTING.md) · [💻 Examples](./examples/) · [🧪 Tests](./tests/) · [🤖 AI](./ai/) · [💼 Careers](./CAREERS.md)

</div>

---

## 📋 Overview

A production-ready SaaS starter template for PropTech applications. Includes auth, payments, dashboard, SEO, and the HIKARI design system.

## ✨ Features

- 🔐 Authentication (email + Google OAuth + OTP)
- 💳 Stripe subscriptions
- 📊 Dashboard layout
- 🎨 HIKARI design system (dark theme)
- 🔍 SEO optimized (meta tags, sitemap)
- 📱 Responsive (mobile + desktop)
- 🤖 AI-ready (LLM integration patterns)

## 🏗️ Architecture

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

## 🚀 Installation

```bash
npx degit HIKARI-GROUP/hikari-proptech-starter my-proptech
```

## 📖 Usage

```javascript
cd my-proptech
npm install
npm run dev
```

## 📁 Project Structure

```
hikari-proptech-starter/
├── src/
│   ├── pages/          # React pages
│   ├── components/     # UI components
│   ├── lib/            # Utils & hooks
│   ├── api/            # Base44 client
│   └── index.css       # Design tokens
├── base44/
│   ├── entities/       # Database schemas
│   └── functions/      # Backend functions
└── .github/
```

## 🛠️ Technologies

- React 18
- Vite
- Tailwind CSS
- Base44
- Stripe
- TypeScript

## 📚 Documentation

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

## 🗺️ Roadmap

See [ROADMAP.md](./ROADMAP.md) for our full vision.

## 🤝 Contributing

We welcome contributions! Please read [CONTRIBUTING.md](./CONTRIBUTING.md) first.

- 🐛 [Report a bug](https://github.com/HIKARI-GROUP/hikari-proptech-starter/issues/new?labels=bug)
- 💡 [Request a feature](https://github.com/HIKARI-GROUP/hikari-proptech-starter/issues/new?labels=enhancement)
- 📝 [Improve docs](https://github.com/HIKARI-GROUP/hikari-proptech-starter/issues/new?labels=documentation)
- 🔍 [Good first issues](https://github.com/HIKARI-GROUP/hikari-proptech-starter/labels/good%20first%20issue)

## 📄 License

MIT © HIKARI GROUP

## 💼 Careers

We're hiring! See [CAREERS.md](./CAREERS.md) for open positions.

## 🌐 Links

- 🏢 [HIKARI GROUP](https://github.com/HIKARI-GROUP)
- 🌍 [Website](https://hikari-group.com)
- 💼 [LinkedIn](https://www.linkedin.com/company/hikari-group)
- 📧 [Contact](mailto:contact@hikari-group.com)

---

<div align="center">
  <sub>Built with ❤️ by <a href="https://github.com/HIKARI-GROUP">HIKARI GROUP</a></sub>
</div>
