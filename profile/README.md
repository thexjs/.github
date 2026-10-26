<div align="center">
  <img src="https://raw.githubusercontent.com/thexjs/x/main/examples/landing/public/icon-512.png" width="140" alt="Thexjs logo" />
  <h1>Thexjs</h1>
  <p><strong>A full-stack React framework built natively on Bun.</strong></p>
  <p>File-based routing, islands, SSR/SSG, API routes, and server functions — in one process, with no separate bundler stack.</p>
</div>

<p align="center">
  <a href="https://thexjs.abdelkabir.me/docs"><img src="https://img.shields.io/badge/Docs-thexjs.abdelkabir.me-black?style=flat-square" alt="Docs"></a>
  <a href="https://github.com/thexjs/x/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" alt="MIT License"></a>
  <a href="https://bun.sh"><img src="https://img.shields.io/badge/Bun-1.0+-black?style=flat-square&logo=bun" alt="Bun"></a>
  <a href="https://react.dev"><img src="https://img.shields.io/badge/React-19-blue?style=flat-square&logo=react" alt="React 19"></a>
  <a href="https://github.com/thexjs/x/discussions"><img src="https://img.shields.io/badge/Discussions-open-blue?style=flat-square" alt="Discussions"></a>
</p>

## Quick start

```bash
bun create thexjs-app@latest my-app
cd my-app
bun run dev
```

The scaffolder is feature-based — pick `tailwind`, `auth`, `content`, `hooks`, or `shadcn`, or start with a blank page. Pass flags non-interactively with `--tailwind --auth`, and use `--no-install` / `--no-git` to skip setup steps.

## Packages

| Package | What it does |
| --- | --- |
| [`@thexjs/core`](https://github.com/thexjs/x/tree/main/packages/core) | Router, SSR/SSG, islands, server functions, data layer |
| [`@thexjs/cli`](https://github.com/thexjs/x/tree/main/packages/cli) | `x dev`, `x build`, `x start` |
| [`@thexjs/auth`](https://github.com/thexjs/x/tree/main/packages/auth) | Credentials + OAuth2 auth, sessions, CSRF |
| [`@thexjs/env`](https://github.com/thexjs/x/tree/main/packages/env) | Type-safe environment variable validation |
| [`@thexjs/hooks`](https://github.com/thexjs/x/tree/main/packages/hooks) | Client-side React hooks |
| [`@thexjs/adapter-vercel`](https://github.com/thexjs/x/tree/main/packages/adapter-vercel) | Vercel Build Output API adapter |
| [`@thexjs/mcp`](https://github.com/thexjs/x/tree/main/packages/mcp) | MCP server exposing x docs to coding agents |
| [`create-thexjs-app`](https://github.com/thexjs/x/tree/main/packages/create-thexjs-app) | Project scaffolder |

## Repositories

| Repository | Description |
| --- | --- |
| [`thexjs/x`](https://github.com/thexjs/x) | Framework monorepo — packages, examples, and docs |
| [`thexjs/.github`](https://github.com/thexjs/.github) | Organization profile and community health files |

## Community

- [Documentation](https://thexjs.abdelkabir.me/docs)
- [Discussions](https://github.com/thexjs/x/discussions)
- [Issues](https://github.com/thexjs/x/issues)
- [Contributing](https://github.com/thexjs/x/blob/main/CONTRIBUTING.md)
- [Support](https://github.com/thexjs/x/blob/main/SUPPORT.md)
- [Code of Conduct](https://github.com/thexjs/x/blob/main/CODE_OF_CONDUCT.md)
- [Security policy](https://github.com/thexjs/x/blob/main/SECURITY.md)
- [Roadmap](https://github.com/thexjs/x/blob/main/ROADMAP.md)

Thexjs is maintained by the [@thexjs/maintainers](https://github.com/orgs/thexjs/teams/maintainers) team on a best-effort basis. It is a learning-oriented project — treat it as curiosity software rather than a production dependency.
