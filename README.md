# 🔐 VantOS – The Privacy-First, AI-Powered Browser

**VantOS** is a user-first, privacy-respecting browser that puts control back into your hands.

- 🔒 Built-in local encryption (zero cloud sync)
- 🧠 AI Assistant powered by Ollama + LangChain
- 🌐 Built-in VPN support (WireGuard / OpenVPN)
- 🔧 Offline, fast, customizable, and open-source
- 📦 Installable as a native `.exe` on Windows

---

## ✨ Features

| Feature                  | Description |
|--------------------------|-------------|
| 🔐 **Encrypted History**  | Browsing history is encrypted locally with user-only access |
| 🧠 **Offline AI Assistant** | Built-in LLM (Mistral or Phi) powered by Ollama + LangChain |
| 🌐 **VPN Integration**   | Route all traffic through built-in VPN (OpenVPN/WireGuard compatible) |
| 📂 **No Cloud Sync**     | All data stays on your device — zero telemetry, zero tracking |
| 🛠 **Customizable**      | Built on Rust + Tauri for maximum performance |
| 📦 **Windows Installer** | Easy-to-use `.exe` installer bundles all components |

---

## 🧠 Local AI Assistant

VantOS includes an evolving, private AI assistant that can:
- Answer your questions (like ChatGPT, but offline)
- Control browser settings via commands
- Learn from your history, bookmarks, and preferences (encrypted)

Powered by:
- 🧠 [`Ollama`](https://ollama.com) (for local LLMs)
- 🧠 [`LangChain`](https://www.langchain.com/)
- 🧠 `Chroma` for vector memory

---

## 🛠 Installation (Development)

### Prerequisites

- [Rust](https://rust-lang.org)
- [Node.js](https://nodejs.org)
- [Python 3.10+](https://www.python.org/)
- [Ollama](https://ollama.com) (`ollama pull mistral`)
- Tauri CLI:  
  ```bash
  cargo install create-tauri-app
