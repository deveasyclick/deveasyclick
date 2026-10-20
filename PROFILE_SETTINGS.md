# GitHub presentation settings

The profile and project documentation changes are in review branches. These account and
repository settings are separate from Git files. The available GitHub integration rejected
account/profile and repository-setting updates with HTTP 403 (`Resource not accessible by
integration`), so none of the proposed metadata below has been applied.

## Profile

At [profile settings](https://github.com/settings/profile), use:

- **Bio:** Senior Full-Stack Engineer | Go, TypeScript & Node.js | Payments, reliable APIs & developer tools | Building products end to end
- **Website:** https://www.yusufadeniyi.dev/

## Pins

On [the profile](https://github.com/deveasyclick), choose **Customize your pins** and select
these six repositories: **gitx, iwifunni, billpay-sdk, feature-flags, zendo, openb2b**.
This replaces the URL shortener and full-stack BillPay application in the current six pins.
BillPay remains featured in the profile README. The public API does not offer repository-pin
mutations, so this uses GitHub's profile control.

## Repository About settings

Open each repository's **About** settings and apply the description and topics below.
Existing topics are retained in these suggestions.

| Repository | Description | Topics |
| --- | --- | --- |
| [gitx](https://github.com/deveasyclick/gitx) | AI-powered Go CLI for commit messages, pull request descriptions, and changelogs. | golang, cli, developer-tools, git, ai |
| [iwifunni](https://github.com/deveasyclick/iwifunni) | Multi-tenant notification infrastructure for email, SMS, and push with Go and Redis-backed queues. | golang, notifications, multitenant-applications, redis, nextjs |
| [billpay-sdk](https://github.com/deveasyclick/billpay-sdk) | Stateless Node.js/TypeScript SDK for Interswitch and VTPass, with explicit provider routing and failover. | typescript, nodejs, sdk, payments, interswitch, vtpass |
| [feature-flags](https://github.com/deveasyclick/feature-flags) | Iwifunni feature management: environment configuration, targeting, gradual rollouts, and audit history. | feature-flags, progressive-delivery, typescript, nextjs, hono, postgresql |
| [zendo](https://github.com/deveasyclick/zendo) | Customer support platform with a Next.js dashboard, embeddable chat widget, and Go backend. | customer-support, golang, nextjs, chat, postgresql |
| [openb2b](https://github.com/deveasyclick/openb2b) | Multi-tenant ordering and invoicing platform for small wholesalers, built with Go, PostgreSQL, and React. | business, modular-architecture, multitenant-applications, golang, react, postgresql, invoicing, b2b |
| [billpay](https://github.com/deveasyclick/billpay) | Full-stack bill payment application with NestJS, Next.js, PostgreSQL, and queue-backed reconciliation. | typescript, nestjs, nextjs, payments, bullmq, redis |
| [portfolio](https://github.com/deveasyclick/portfolio) | Yusuf Adeniyi’s product engineering portfolio: shared content, product and editorial designs, and dark mode. | portfolio, nextjs, typescript, accessibility, dark-mode |
| [deveasyclick](https://github.com/deveasyclick/deveasyclick) | Yusuf Adeniyi — senior full-stack engineer working on payments, reliable APIs, and developer tools. | github-profile, portfolio, golang, typescript |

Use these homepage corrections:

- **BillPay:** https://billspay.vercel.app — returned HTTP 200 during review. The previous
  `billpay-frontend.vercel.app` URL returned HTTP 404.
- **BillPay SDK:** https://www.npmjs.com/package/billpay — package identity/version checked
  against the npm registry; the source repository is `deveasyclick/billpay-sdk`.
- **Iwifunni:** https://iwifunni.cc — returned HTTP 200 during review.
- **OpenB2B:** https://openb2b-web.vercel.app — returned HTTP 200 during review.
- **Portfolio and profile repository:** https://www.yusufadeniyi.dev/

The complete proposed values are in [profile-settings.json](profile-settings.json). No token
or credential value belongs in either file.

## License changes

MIT license files are included for Iwifunni and OpenB2B following the owner's explicit
selection. Root MIT license files are also added to Feature Flags, BillPay, and Zendo,
whose existing READMEs already declare MIT. GitHub's license detection reflects the default
branch after those changes are merged.
