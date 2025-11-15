<div align="center">

# 👨‍💻 DoctorX

### Full-Stack Developer • Reverse Engineer • Security Researcher

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=2E9EF7&center=true&vCenter=true&width=435&lines=Building+Secure+Systems;Reverse+Engineering+Expert;Full-Stack+Architect" alt="Typing SVG" />

<p>
  <img src="https://raw.githubusercontent.com/gilbarbara/logos/master/logos/windows.svg" height="40" alt="Windows" />
  <img src="https://raw.githubusercontent.com/gilbarbara/logos/master/logos/linux-tux.svg" height="40" alt="Linux" />
  <img src="https://raw.githubusercontent.com/gilbarbara/logos/master/logos/apple.svg" height="40" alt="macOS" />
</p>

[![Profile Views](https://komarev.com/ghpvc/?username=DoctorX&color=2e9ef7&style=flat-square)](https://github.com/DoctorX)

</div>

---

## 🎯 About Me

I'm a **full-stack engineer** and **reverse-engineering specialist** passionate about building secure, high-performance systems. My expertise spans from low-level binary analysis to modern web applications, with a focus on **clean architecture**, **security**, and **performance optimization**.

### What I Do

- 🔬 **Low-Level Analysis** — Expert in IDA Pro, Ghidra, x64dbg, and Radare2
- 🛡️ **Security Research** — Deobfuscation, unpacking, and malware behavior analysis
- 🎮 **Game Hacking** — Memory instrumentation and reverse engineering
- ⚙️ **Backend Engineering** — Scalable APIs with Node.js, Go, and .NET
- 🖥️ **Desktop Development** — Cross-platform applications in C#, Avalonia, WPF
- 🐧 **Linux Tooling** — GNOME extensions, Bash automation, system utilities
- 🌐 **Web Development** — Modern interfaces with React and TypeScript
- 🔧 **DevOps & Tooling** — Internal developer infrastructure and automation

---

## 🛠️ Tech Stack

<details open>
<summary><b>💻 Languages</b></summary>
<br>
<p>
  <img src="https://skillicons.dev/icons?i=cs,go,ts,js,cpp,bash,python&theme=dark&perline=7" />
</p>
</details>

<details open>
<summary><b>🏗️ Backend & Databases</b></summary>
<br>
<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express,go,dotnet,mongodb,postgres,redis&theme=dark&perline=7" />
</p>
</details>

<details open>
<summary><b>🎨 Frontend</b></summary>
<br>
<p>
  <img src="https://skillicons.dev/icons?i=react,tailwind,html,css,vite&theme=dark&perline=7" />
</p>
</details>

<details open>
<summary><b>🖥️ Desktop & Tools</b></summary>
<br>
<p>
  <img src="https://skillicons.dev/icons?i=dotnet,visualstudio,vscode,vim,git&theme=dark&perline=7" />
</p>
</details>

<details open>
<summary><b>🛡️ Reverse Engineering & Security</b></summary>
<br>
<p>
  <img src="https://img.shields.io/badge/IDA_Pro-202020?style=for-the-badge&logo=hackaday&logoColor=00D9FF" />
  <img src="https://img.shields.io/badge/Ghidra-EF1F1F?style=for-the-badge&logo=ghidra&logoColor=white" />
  <img src="https://img.shields.io/badge/x64dbg-44CC11?style=for-the-badge&logo=CodersRank&logoColor=white" />
  <img src="https://img.shields.io/badge/Radare2-6A1B9A?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Deobfuscation-FF6B6B?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Memory_Analysis-4ECDC4?style=for-the-badge" />
</p>
</details>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%">

### 📨 ArrowSender
**Advanced Messaging Automation Suite**

A comprehensive desktop automation platform for enterprise messaging operations.

**Features:**
- Multi-platform support (Messenger, WhatsApp)
- Campaign management with safe-mode sending
- Message queueing and scheduling
- WebView2 integration
- Secure storage and licensing system

**Stack:** `C#` `WinForms` `Avalonia` `Node.js` `MongoDB`

🔒 *Private Repository*

</td>
<td width="50%">

### 🛠️ GRZ Tool
**Reverse Engineering Utilities**

A powerful toolkit for binary analysis and reverse engineering workflows.

**Features:**
- Static and dynamic analysis
- Scriptable unpacking engine
- Low-level binary inspection
- Memory scanning and patching
- x64dbg integration

**Stack:** `C#` `Native Modules` `x64dbg API`

🔒 *Private Repository*

</td>
</tr>
</table>

---

## 🐧 Linux & System Tools

I specialize in creating developer-friendly tooling for Linux environments:

- **GNOME Extensions** — Custom desktop enhancements
- **Shell Utilities** — Productivity automation scripts
- **System Monitors** — Service watchers and health checks
- **Workflow Tools** — Developer experience improvements

### Example: Service Auto-Restart Watcher

```bash
#!/bin/bash
# Service health monitor with auto-recovery

SERVICE_NAME="backend.service"
CHECK_INTERVAL=3

while true; do
  if ! systemctl is-active --quiet "$SERVICE_NAME"; then
      echo "[$(date '+%Y-%m-%d %H:%M:%S')] Service down, restarting..."
      systemctl restart "$SERVICE_NAME"
      
      if systemctl is-active --quiet "$SERVICE_NAME"; then
          echo "[$(date '+%Y-%m-%d %H:%M:%S')] Service restored successfully"
      else
          echo "[$(date '+%Y-%m-%d %H:%M:%S')] CRITICAL: Restart failed!"
      fi
  fi
  sleep $CHECK_INTERVAL
done
```

---

## 📊 GitHub Analytics

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=DoctorX&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DoctorX&layout=compact&langs_count=8&theme=tokyonight"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=DoctorX&theme=tokyonight" alt="GitHub Streak" />
</div>

---

## 🤝 Connect With Me

<div align="center">

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your.email@example.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourprofile)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/yourhandle)
[![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/users/yourid)

</div>

---

<div align="center">

### 💡 *"Security through obscurity is no security at all. Understanding systems deeply is the first step to securing them."*

![Snake animation](https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg)

**⭐ Star my repositories if you find them useful!**

</div>
