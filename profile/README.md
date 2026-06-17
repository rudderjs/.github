<p align="center">
  <img src="https://raw.githubusercontent.com/rudderjs/rudder/main/logo.png" alt="Rudder" width="220" />
</p>

<p align="center">
  <strong>The fullstack Node.js framework with structure, speed, and AI built in.</strong>
</p>

<p align="center">
  <a href="https://github.com/rudderjs/rudder">Framework</a> ·
  <a href="https://rudderjs.com/guide">Docs</a> ·
  <a href="https://www.npmjs.com/package/create-rudder">Scaffolder</a> ·
  <a href="https://github.com/rudderjs/rudder/discussions">Discussions</a>
</p>

---

## What we build

**Rudder** is a batteries-included, modular TypeScript framework for Node.js. Controller-returned SSR views through [Vike](https://vike.dev) + [Vite](https://vitejs.dev), AI-native agents, real-time collaboration, and service-oriented architecture: all in one monorepo, all opt-in.

51 first-party `@rudderjs/*` packages. Start with a few, bolt on what you need.

---

## Quick start

```bash
pnpm create rudder my-app
cd my-app
pnpm rudder migrate     # set up the database (native engine, the default)
pnpm dev
# → http://localhost:3000 with a welcome page + register/login working end-to-end
```

> Picked Prisma or Drizzle in the scaffolder instead? Run that ORM's setup
> (`pnpm rudder db:generate && pnpm rudder db:push`) before `pnpm dev`.

---

## Projects

| Project | Description |
|---|---|
| **[rudder](https://github.com/rudderjs/rudder)** | The framework monorepo: 51 `@rudderjs/*` packages across routing, ORM, auth, queue, AI, real-time, and more. |
| **[create-rudder](https://www.npmjs.com/package/create-rudder)** | Interactive scaffolder. Pick your database, frontend, and packages, then ship in 60 seconds. |
| **[rudderjs.com](https://rudderjs.com)** | Documentation, guides, and the package reference. |

---

## Community

- **Discussions** ([github.com/rudderjs/rudder/discussions](https://github.com/rudderjs/rudder/discussions)): ask questions, share what you built
- **Issues** ([github.com/rudderjs/rudder/issues](https://github.com/rudderjs/rudder/issues)): bug reports, feature requests
- **Security**: see the [security policy](https://github.com/rudderjs/rudder/blob/main/SECURITY.md) for responsible disclosure

---

## Contributing

We welcome contributions of every shape: bug fixes, new packages, docs, benchmarks, examples. Start with [CONTRIBUTING.md](https://github.com/rudderjs/rudder/blob/main/CONTRIBUTING.md) and the [code of conduct](https://github.com/rudderjs/rudder/blob/main/CODE_OF_CONDUCT.md).

Rudder is MIT-licensed and built in the open.

---

<p align="center">
  <sub>Built with care by the Rudder team.</sub>
</p>
