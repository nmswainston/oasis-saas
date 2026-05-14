# Oasis SaaS

A SaaS platform built on the Oasis brand — extending the Oasis help desk into a full subscription product.

## Overview

Oasis SaaS is the product layer on top of the Oasis help desk system. It wraps the knowledgebase and support features in a multi-tenant SaaS structure with Netlify deployment and a Tailwind-based UI.

## Tech Stack

- TypeScript
- Vite
- Tailwind CSS
- Netlify (deployment)

## Getting Started

### Prerequisites

- Node.js 18+
- npm

### Installation

```bash
npm install
```

### Development

```bash
npm run dev
```

### Build

```bash
npm run build
```

## Project Structure

```
src/         # Application source code
public/      # Static assets
CSP.md       # Content Security Policy documentation
```

## Deployment

Deploys to Netlify automatically — see `netlify.toml` for configuration.

## Related

- [`oasis-help-desk`](https://github.com/nmswainston/oasis-help-desk) — the core knowledgebase product

---

*Built by [nmswainston](https://github.com/nmswainston)*
