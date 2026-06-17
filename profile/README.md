<p align="center">
  <img src="https://raw.githubusercontent.com/rudderjs/rudder/main/logo.png" alt="Rudder" width="220" />
</p>

<p align="center">
  <strong>The fullstack Node.js framework with structure, speed, and AI built in.</strong>
</p>

<p align="center">
  <a href="https://github.com/rudderjs/rudder">Framework</a> ·
  <a href="https://www.npmjs.com/package/create-rudder-app">Scaffolder</a> ·
  <a href="https://github.com/rudderjs/rudder/discussions">Discussions</a> ·
  <a href="https://github.com/rudderjs/rudder/blob/main/docs/guide/mental-model.md">Docs</a>
</p>

---

## What we build

**Rudder** is a batteries-included, modular TypeScript framework for Node.js. Controller-returned SSR views through [Vike](https://vike.dev) + [Vite](https://vitejs.dev), AI-native agents, real-time collab, service-oriented architecture — all in one monorepo, all opt-in.

45 first-party packages. Start with 3, bolt on what you need.

---

## Quick start

```bash
pnpm create rudder-app my-app
cd my-app
pnpm exec prisma generate && pnpm exec prisma db push
pnpm dev
# → http://localhost:3000 — welcome page + register/login working end-to-end
```

---

## Projects

| Project | Description |
|---|---|
| **[rudder](https://github.com/rudderjs/rudder)** | The framework monorepo — 45 `@rudderjs/*` packages across routing, ORM, auth, queue, AI, real-time, and more. |
| **[create-rudder](https://www.npmjs.com/package/create-rudder)** | Interactive scaffolder. Pick your database, frontend, and packages — ship in 60 seconds. |

---

## Community

- **Discussions** — [github.com/rudderjs/rudder/discussions](https://github.com/rudderjs/rudder/discussions) — ask questions, share what you built
- **Issues** — [github.com/rudderjs/rudder/issues](https://github.com/rudderjs/rudder/issues) — bug reports, feature requests
- **Security** — see the [security policy](https://github.com/rudderjs/rudder/blob/main/SECURITY.md) for responsible disclosure

---

## Contributing

We welcome contributions of every shape — bug fixes, new packages, docs, benchmarks, examples. Start with [CONTRIBUTING.md](https://github.com/rudderjs/rudder/blob/main/CONTRIBUTING.md) and the [code of conduct](https://github.com/rudderjs/rudder/blob/main/CODE_OF_CONDUCT.md).

RudderJS is MIT-licensed and built in the open.

---

<p align="center">
  <sub>Built with ❤ by the RudderJS team.</sub>
</p>
