<h1 align="center">toawe.me</h1>

<p align="center">
  <b>Small, composable, offline-first Go tooling.</b><br>
  Most repos carry zero third-party dependencies, and nothing phones home.
</p>

<p align="center">
  <a href="https://toawe.me">toawe.me</a> ·
  <a href="https://code.toawe.me">code.toawe.me</a>
</p>

---

### Apps

| | Repo | What it does |
|---|---|---|
| ⚡ | **[blink](https://github.com/toaweme/blink)** | Boots your entire dev stack (shell, Go, Node, Docker) with multiplexed logs, live reload, and port reclaiming, behind a TUI. Zero-config for the common case, fully offline. |
| 🩺 | **[care](https://github.com/toaweme/care)** | Runs every quality, security, dependency, and test check for a repo in one command and grades it. Built for working across many repos and languages at once. |

### Engine

| | Repo | What it does |
|---|---|---|
| 🧩 | **[sintax](https://github.com/toaweme/sintax)** | Zero-dependency templating engine with pipe syntax, for workflows, document generation, and data transforms. `{{ orders \| filter:'status','paid' \| pluck:'total' \| sum }}` |

### The toolkit underneath

The small modules that blink and care are built on. Each stands alone.

| Repo | What it does |
|---|---|
| **[cli](https://github.com/toaweme/cli)** | Build Go CLIs where a command is just a struct. Flags, args, env, defaults, and validation declared once as tags. |
| **[structs](https://github.com/toaweme/structs)** | Runtime tools to fill and read Go structs. Set any nested field from a simple `map[string]any`. |
| **[http](https://github.com/toaweme/http)** | Struct-based HTTP client (pure stdlib, zero deps) plus a tiny chi server wrapper with middleware, auth, and SSE. |
| **[log](https://github.com/toaweme/log)** | A thin, zero-dependency layer over `log/slog`. Filters, fan-out to multiple outputs, and custom levels. |

---

<p align="center">
  Apache-2.0. Built to run offline, self-hostable, no lock-in.<br>
  Made with ❤️ in Lithuania 🇱🇹.
</p>
