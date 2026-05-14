# Oasis SaaS

A SaaS platform that scales the Oasis help desk into a multi-client subscription product.

## Problem

The Oasis help desk was built for a single client, but the core product had value for any smart home integrator with clients who needed self-service support.

## Solution

Wrapped the knowledgebase in a SaaS structure, adding multi-tenancy support and a deployable product layer so the tool could serve multiple integrators and their clients.

## Screenshots

> *Add 2–4 screenshots here*

## Tech Stack

- TypeScript
- Vite
- Tailwind CSS
- Netlify

## Features

- Multi-tenant architecture for serving multiple integrators
- Knowledgebase and support article management
- Mobile-first UI inherited from the core Oasis product
- Netlify deployment with CSP configuration

## Installation

```bash
npm install
npm run dev
```

## Lessons Learned

- Transitioning a single-client tool to multi-tenant requires rethinking data boundaries early
- SaaS pricing and access control are design decisions, not just engineering ones
- Reusing a proven UI base (`oasis-help-desk`) accelerated development significantly

## Future Improvements

- Stripe billing and subscription management
- Admin dashboard for managing tenants and articles
- Analytics on article views and search queries

## Related

- [`oasis-help-desk`](https://github.com/nmswainston/oasis-help-desk) — the core product this is built on

---

*Built by [nmswainston](https://github.com/nmswainston)*
