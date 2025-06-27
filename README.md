# 🧩 micro-frontend-demo

A modular microfrontend playground with 3 independently deployed apps:

- `app1` – Vanilla JS component
- `app2` – Another Vanilla JS component
- `app3` – A React component wrapped in Shadow DOM
- `app-shell` – The main UI that brings it all together, styled and responsive

Each app runs on its own port and is dropped into the shell via `<script>` and custom elements, simulating real-world frontend autonomy.

---

## ⚡ Prerequisite

This demo uses [`http-server`](https://www.npmjs.com/package/http-server) to serve static assets locally:

```bash
npm install -g http-server
