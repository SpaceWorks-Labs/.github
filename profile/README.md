<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SpaceWorks-Labs/.github/main/profile/assets/banner-dark.png">
  <img alt="Space Works — Less searching. More making. Open-source software for makerspaces and communities." src="https://raw.githubusercontent.com/SpaceWorks-Labs/.github/main/profile/assets/banner-light.png">
</picture>

<p align="center">
  <a href="https://spaceworks-labs.github.io/SpaceWorks-Website/"><b>Website</b></a> ·
  <a href="https://spaceworks-labs.github.io/SpaceWorks-Docs/"><b>Documentation</b></a> ·
  <a href="https://spaceworks-labs.github.io/SpaceWorks-Design/"><b>Design system</b></a> ·
  <a href="https://github.com/SpaceWorks-Labs/SpaceWorks#quick-start"><b>Get started</b></a>
</p>

# Built in a makerspace. Shared with everyone.

**Space Works builds free, open-source, self-hosted software for makerspaces, fab labs, tool libraries and the communities around them.** Track shared tools, run machines, host events, book rooms, manage memberships and give your team a place to work.

Start with the complete makerspace platform, or choose a standalone app for the job you need. Host it on your own infrastructure, keep control of your data, and adapt it to the way your community works.

## SpaceWorks — the makerspace hub

[**SpaceWorks**](https://github.com/SpaceWorks-Labs/SpaceWorks) brings day-to-day makerspace operations into one modular, multi-tenant platform. One deployment can serve several spaces, each with its own members, inventory, roles and settings. Enable the modules your space needs.

- **Inventory and lending:** public catalogues, borrow requests, QR checkout, photo-evidence handovers, returns and an audit trail.
- **Machines and making:** machine records, 3D-printing requests, service queues, consumables and maintenance.
- **Community:** events, registration, QR check-in, bookable spaces, memberships and maker profiles.
- **Operations:** optional payments, reports, notifications, backups and updates.

**Stack:** Python · Django 6 · Django REST Framework · React 19 · TypeScript · Vite · TanStack Query · Tailwind CSS · PostgreSQL · Redis · Celery · S3-compatible storage · Docker Compose.

[Explore the platform](https://github.com/SpaceWorks-Labs/SpaceWorks#readme) · [Browse its modules](https://github.com/SpaceWorks-Labs/SpaceWorks/blob/main/docs/MODULES.md) · [Install and self-host](https://github.com/SpaceWorks-Labs/SpaceWorks#quick-start)

## Standalone apps — choose what your space needs

These are independent applications with their own backends, databases and installation guides. They cover focused parts of the Space Works ecosystem and can be deployed without the main platform. Where supported, APIs and webhooks connect them to other tools; running several apps does not automatically combine their accounts or data.

| Project | What it does |
| --- | --- |
| [**SpaceWorks-Inventory**](https://github.com/SpaceWorks-Labs/SpaceWorks-Inventory) | A stock room and lending desk: catalogues, serialized assets, QR labels, photo-evidence loans, stock counts and transfers between spaces. |
| [**SpaceWorks-Machines**](https://github.com/SpaceWorks-Labs/SpaceWorks-Machines) | Machine catalogues, job requests and queues, pricing and payments, consumables, repairs, maintenance and printer connections. |
| [**SpaceWorks-Events**](https://github.com/SpaceWorks-Labs/SpaceWorks-Events) | Event pages, registration, free or paid tickets, live QR tickets, offline check-in, badges, feedback and certificates. |
| [**SpaceWorks-Bookings**](https://github.com/SpaceWorks-Labs/SpaceWorks-Bookings) | Rooms, studios, desks and halls: live availability, recurring bookings, approvals, check-in, payments and cancellation policies. |
| [**SpaceWorks-Organization**](https://github.com/SpaceWorks-Labs/SpaceWorks-Organization) | Memberships for clubs, associations and alumni bodies: join forms, plans, approvals, renewals, payments, GST receipts and verifiable member cards. In active development. |
| [**SpaceWorks-Workspace**](https://github.com/SpaceWorks-Labs/SpaceWorks-Workspace) | Internal team operations: projects and kanban, chat, docs, files, finance, people, governance and an AI assistant with MCP. |

**Shared app stack:** TypeScript · Next.js 16 · React 19 · Prisma · PostgreSQL · Tailwind CSS · Radix UI. Self-hosted deployments use Docker Compose, Redis, background workers and S3-compatible storage, including Silo. Each repository documents its own configuration and hosting options.

## Native mobile clients

Take the SpaceWorks makerspace platform to the workshop floor. The native clients cover member and staff journeys, including equipment, requests, loans, bookings, events and QR/evidence workflows.

| Project | Stack | Platform |
| --- | --- | --- |
| [**SpaceWorks-iOS**](https://github.com/SpaceWorks-Labs/SpaceWorks-iOS) | Swift · SwiftUI · generated OpenAPI client · Xcode | iPhone and iPad, iOS 17+ |
| [**SpaceWorks-Android**](https://github.com/SpaceWorks-Labs/SpaceWorks-Android) | Kotlin · Jetpack Compose · Material 3 · generated OpenAPI client · Gradle | Android phones and tablets, Android 8+ |

Both clients can be configured for your own SpaceWorks backend. Live authentication, payments and push notifications depend on deployment setup; see each repository for current validation and release readiness.

## Shared foundations

| Project | What it holds | Stack / formats |
| --- | --- | --- |
| [**SpaceWorks-Design**](https://github.com/SpaceWorks-Labs/SpaceWorks-Design) | Brand guidelines, logo masters, Patch the mascot, icons, design tokens and UX specifications; reusable as a Git submodule. | SVG · CSS / JSON tokens · Astro Starlight |
| [**SpaceWorks-Docs**](https://github.com/SpaceWorks-Labs/SpaceWorks-Docs) | Installation, self-hosting, configuration, staff guides, developer documentation and API reference for the main platform. | Astro Starlight · Markdown / MDX |
| [**SpaceWorks-Website**](https://github.com/SpaceWorks-Labs/SpaceWorks-Website) | The public landing page introducing Space Works. | HTML · CSS · JavaScript · Python build script |

## Open source, under the AGPL

**Every project listed here is open source and carries the GNU Affero General Public License v3.** Most specify **AGPL-3.0-or-later**; each repository's license and notices define the applicable terms.

Use, study, modify and share the software, including for commercial work, under those terms. If you modify an AGPL application and let people use it over a network, offer those users the corresponding source for your modified version. Third-party dependencies, fonts and reference materials retain their own licenses.

Your community can run the software on its own infrastructure and contribute improvements back to the ecosystem.

## Build with us

Space Works grew out of everyday making at **TinkerSpace Kochi**: finding tools, lending equipment and keeping a shared workshop running. The same practical questions guide the ecosystem today.

Try an app, report a reproducible bug, improve a guide, translate a screen, or share a tested hardware integration. Read the chosen repository's contributing guide for its setup, checks and target branch.

[Find an issue](https://github.com/search?q=org%3ASpaceWorks-Labs+is%3Aissue+is%3Aopen&type=issues) · [Contributing guide](https://github.com/SpaceWorks-Labs/.github/blob/main/CONTRIBUTING.md) · [Get help](https://github.com/SpaceWorks-Labs/.github/blob/main/SUPPORT.md) · [Report a security issue privately](https://github.com/SpaceWorks-Labs/.github/blob/main/SECURITY.md)

---

<p align="center">
  <img src="https://raw.githubusercontent.com/SpaceWorks-Labs/.github/main/profile/assets/symbol.svg" alt="" width="36"><br>
  <sub>Made with care by the Space Works community. Started by <a href="https://github.com/Shaan-Shoukath">Shaan-Shoukath</a> at TinkerSpace Kochi.</sub>
</p>
