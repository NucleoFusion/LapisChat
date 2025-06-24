# LapisChat

**LapisChat** is a minimal, ephemeral chat application built with **Rust** and **Tauri**. It enables two users to connect in a temporary session, exchange messages in real-time, and leave without a trace. Once the session ends, all data is discarded — no history, no storage, no surveillance.

> Temporary by design. Private by default.

---

## 💡 What is LapisChat?

LapisChat is designed for short, secure, and no-strings-attached conversations. Instead of creating user accounts or storing chat history, it focuses on **instant, one-time communication sessions** that are destroyed as soon as users disconnect.

---

## 🔐 Features

- ⚡ Real-time messaging between two users
- 🧼 Data lives only for the duration of the session
- 🔐 No login, no user tracking, no database
- 🖥️ Desktop-ready via [Tauri](https://tauri.app)
- 🦀 Backend built with Rust for speed and safety

---

## 🛠️ Tech Stack

- **Rust** – core logic and ephemeral backend
- **Tauri** – secure, lightweight desktop shell
- **WebSocket / P2P** – for real-time communication
- **(Optional)**: frontend with Svelte, React, or Vanilla JS

---

## 🚀 Getting Started

### Prerequisites

- [Rust](https://www.rust-lang.org/tools/install)
- [Node.js](https://nodejs.org/)
- [Tauri CLI](https://tauri.app/v1/guides/getting-started/prerequisites/)

### Installation

```bash
git clone https://github.com/NucleoFusion/LapisChat
cd LapisChat

# Install frontend deps
npm install

# Build and run
npm run tauri dev
```

---

## 📦 How It Works

1. User A creates a session (gets a session ID or link).
2. User B joins the session using that code.
3. Messages are exchanged live while both are connected.
4. When either user disconnects, the session and messages vanish completely.

---

## ⚠️ Disclaimer

LapisChat is **not encrypted** end-to-end by default. It is ephemeral and private in terms of **no persistence**, but not meant for transmitting sensitive or regulated data without additional security layers.

---

## ✨ Roadmap

- [ ] Add session PIN/code sharing
- [ ] Optional end-to-end encryption
- [ ] UI polish and theming
- [ ] Support for group sessions (3+ users)
- [ ] Mobile app via Tauri or Capacitor

---

## 🤝 Contributing

Contributions welcome!

```bash
# Fork the repo
# Create your branch: git checkout -b feature/your-feature
# Commit your changes
# Push and open a PR
```

---

## 📄 License

This project is licensed under the MIT License. See [`LICENSE`](./LICENSE) for details.

---

## 💬 Author

Built by [@NucleoFusion](https://github.com/NucleoFusion) with a love for privacy-first software.
