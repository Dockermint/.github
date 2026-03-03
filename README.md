<p align="center">
  <a href="https://dockermint.io">
    <img src="logo.svg" alt="Dockermint" width="420" />
  </a>
</p>

<p align="center">
  <b>The first CD Pipeline built for Cosmos SDK node operators.</b><br/>
  Build and deploy deterministic Docker images automatically.
</p>

<p align="center">
  <a href="https://dockermint.io"><img src="https://img.shields.io/badge/Website-dockermint.io-0025FF?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNmZmYiIHN0cm9rZS13aWR0aD0iMiI+PGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iMTAiLz48cGF0aCBkPSJNMiAxMmgyME0xMiAyYTE1LjMgMTUuMyAwIDAgMSA0IDEwIDE1LjMgMTUuMyAwIDAgMS00IDEwIDE1LjMgMTUuMyAwIDAgMS00LTEwIDE1LjMgMTUuMyAwIDAgMSA0LTEweiIvPjwvc3ZnPg==" alt="Website"/></a>
  <a href="https://github.com/Dockermint"><img src="https://img.shields.io/badge/GitHub-Dockermint-181717?style=flat-square&logo=github" alt="GitHub"/></a>
  <a href="https://github.com/Dockermint/.github/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-Apache_2.0-blue?style=flat-square" alt="License"/></a>
</p>

---

### What is Dockermint?

Node operators across the Cosmos ecosystem face the same deployment challenges: missing pre-built binaries, inconsistent build standards, no official Docker images, and manual update processes that don't scale.

**Dockermint solves this.** It scans GitHub releases, builds deterministic Docker images, and pushes them to your registry, with zero manual intervention.

<br/>

### ⚡ Key Features

| | Feature | Description |
|---|---|---|
| 🔍 | **Auto-scan** | Watches GitHub releases and triggers builds automatically |
| 🔒 | **Deterministic builds** | 100% reproducible with locked dependencies |
| 🏗️ | **Multi-arch** | AMD64 & ARM64 built simultaneously |
| 🗄️ | **DB flexibility** | LevelDB and PebbleDB support out of the box |
| 📦 | **Registry push** | Works with any OCI-compliant Docker registry |
| 📲 | **Telegram alerts** | Real-time build notifications |
| 📋 | **Build traces** | Complete logs for full transparency |
| ⚙️ | **Customizable** | Static/dynamic linking, your rules |

<br/>

### 📂 Projects

<table>
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/Dockermint/dockermint">
        <img src="https://img.shields.io/badge/Rust-000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust"/><br/>
        <b>Dockermint</b>
      </a>
      <br/>
      <sub>The CD pipeline: automated Docker image builds for Cosmos SDK chains.</sub>
      <br/><br/>
      <img src="https://img.shields.io/badge/status-WIP-orange?style=flat-square" alt="WIP"/>
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/Dockermint/pebblify">
        <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go"/><br/>
        <b>Pebblify</b>
      </a>
      <br/>
      <sub>Migrate LevelDB to PebbleDB: 866K keys/sec, crash recovery built-in.</sub>
      <br/><br/>
      <img src="https://img.shields.io/badge/status-Production_Ready-brightgreen?style=flat-square" alt="Production Ready"/>
    </td>
  </tr>
</table>

<br/>

### 🌐 Trusted by operators of

**Cosmos Hub** · **Axelar** · **Fetch** · **Injective** · **Osmosis**, and more.

---

<p align="center">
  <sub>Open source under <a href="https://github.com/Dockermint/.github/blob/main/LICENSE">Apache 2.0</a> · Built with 💙 by the Dockermint team</sub>
</p>
