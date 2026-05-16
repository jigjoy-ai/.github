<p align="center">
  <a href="https://github.com/jigjoy-ai/mozaik">
    <img src="https://raw.githubusercontent.com/jigjoy-ai/.github/main/assets/mozaik-pin.svg" alt="mozaik" />
  </a>
  <a href="https://github.com/Lotus015/baro">
    <img src="https://raw.githubusercontent.com/jigjoy-ai/.github/main/assets/baro-pin.svg" alt="baro" />
  </a>
  <a href="https://github.com/jigjoy-ai/spektrum-sdk">
    <img src="https://raw.githubusercontent.com/jigjoy-ai/.github/main/assets/spektrum-pin.svg" alt="spektrum-sdk" />
  </a>
</p>

```bash
jigjoy@github:~$ whoami
JigJoy — Infrastructure and services for Gen AI teams.

jigjoy@github:~$ cat ~/.mission
We build agents that don't wait on each other.

jigjoy@github:~$ █
```

---

### What we ship

```bash
jigjoy@github:~$ ls -la ~/products/

drwxr-xr-x  mozaik          TS runtime · reactive agents on a shared event bus
drwxr-xr-x  baro            CLI · parallel Claude Code agents · ships a PR
drwxr-xr-x  spektrum-sdk    Vibe coding · prompt → deployed app, returns a URL
```

#### → mozaik &nbsp;·&nbsp; [github.com/jigjoy-ai/mozaik](https://github.com/jigjoy-ai/mozaik)

```bash
$ npm install @mozaik-ai/core
```

The core runtime. An open-source TypeScript framework for reactive, event-driven agents on a shared bus. Type-safe handlers, agent swarms, structured context. Everything else we ship is built on top of it.

#### → baro &nbsp;·&nbsp; [baro.rs](https://baro.rs)

```bash
$ npm install -g baro-ai
$ baro "Add JWT auth with role-based access control"
```

A CLI that spawns parallel Claude Code subprocesses, organizes them as a DAG, and opens a pull request when they're done. Built on **mozaik**.

#### → spektrum-sdk &nbsp;·&nbsp; [github.com/jigjoy-ai/spektrum-sdk](https://github.com/jigjoy-ai/spektrum-sdk)

A vibe-coding SDK: send a prompt, get back a URL to a deployed app. We do the planning, generation, and hosting; you stay in your editor. Also built on **mozaik**.

---

### What we're obsessed with

How do N parallel AI agents agree on architecture *before* they start writing code?

We think the answer is **specialization** — agents with explicit roles (Architect, Builder, Reviewer, Finalizer) that talk over a typed event bus, not soup-of-prompts. That's the bet behind mozaik, and the runtime that baro and spektrum-sdk are built on.

---

### Where we post

```bash
jigjoy@github:~$ cat ~/.signals

essays    → jigjoy.ai/blog
threads   → x.com/jigjoy_ai
community → discord (link on jigjoy.ai)
home      → jigjoy.ai
```

<!-- BLOG:START -->
**Latest essay** → [Build Your Own CLI Agent: A Step-by-Step Guide](https://jigjoy.ai/blog/build-your-own-cli-agent/)
<!-- BLOG:END -->

---

<a href="https://jigjoy.ai">
  <img src="https://raw.githubusercontent.com/jigjoy-ai/.github/main/assets/footer.svg" alt="JigJoy — Infrastructure and services for Gen AI teams" />
</a>
