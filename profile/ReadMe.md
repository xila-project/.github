<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/xila-project/.github/main/profile/assets/xila-horizontal-white.svg">
    <img src="https://raw.githubusercontent.com/xila-project/.github/main/profile/assets/xila-horizontal-ink.svg" alt="Xila" width="300">
  </picture>
</p>

<p align="center">
  <strong>A modern, memory-safe operating system for embedded systems.</strong><br>
  Rewritten in <b>Rust</b>. Powered by <b>WebAssembly</b>.
</p>

<p align="center">
  <a href="https://xila.dev">🌍 Website</a> •
  <a href="https://documentation.xila.dev/demonstrations/wasm/en/">🎬 Demonstrations</a> •
  <a href="https://www.xila.dev/guide/">📖 Guide</a> •
  <a href="https://www.xila.dev/reference/">📚 Reference</a> •
  <a href="mailto:contact@xila.dev">✉️ Contact</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Language-Rust-orange?style=flat-square&logo=rust" alt="Rust">
  <img src="https://img.shields.io/badge/Runtime-WASM-624de3?style=flat-square&logo=webassembly" alt="WASM">
  <a href="https://matrix.to/#/#xila:anneraud.fr" rel="noopener" target="_blank"><img src="https://matrix.to/img/matrix-badge.svg" alt="Chat on Matrix"></a>
</p>

---

## ⚡ The Evolution

Xila has been completely reimagined. We have moved away from the legacy C++/Berry architecture to a modern stack built on **Rust** for maximum memory safety and **WebAssembly (WASM)** for a high-performance, sandboxed application ecosystem.

### Why the rewrite?

- **Memory Safety:** Leveraging Rust to eliminate common embedded bugs at compile-time.
- **WASM Portability:** Applications are language-agnostic. Develop in any language that targets WebAssembly.
- **Security:** Sandboxed execution of software components.
- **Performance:** Near-native execution speeds on microcontrollers.

## 🏗️ Architecture

Xila acts as a lightweight kernel and abstraction layer for microcontrollers (primarily ESP32-S3), providing:

- **Core:** The Rust-based heartbeat managing hardware abstraction and task scheduling.
- **WASM Runtime:** A portable execution engine for sandboxed binaries.
- **Unified API:** Simplified interfaces for graphics, connectivity, and storage.

## 📂 Repositories

| Repository                                             | Description                                                     |
| :----------------------------------------------------- | :-------------------------------------------------------------- |
| [**Core**](https://github.com/Xila-Project/Core)       | The Rust-based core operating system and WASM execution engine. |
| [**Website**](https://github.com/Xila-Project/Website) | The source for [xila.dev](https://xila.dev).                    |

## 💬 Community & Support

Join us to discuss development, suggest features, or get help:

- **Matrix:** [#xila:anneraud.fr](https://matrix.to/#/#xila:anneraud.fr)
- **Email:** [contact@xila.dev](mailto:contact@xila.dev)

> [!IMPORTANT]  
> Xila is currently in a **heavy alpha/rewrite phase**. The legacy C++ repositories have been archived to focus entirely on the new Rust/WASM architecture.

---

<p align="center">
  Built with 🦀 by <strong>Alix ANNERAUD</strong> and contributors. <br>
  Xila is licensed under the <a href="https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html">GNU General Public License v2.0</a>.
</p>
