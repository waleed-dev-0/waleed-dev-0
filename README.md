<h1 align="center"><strong>DoctorX</strong></h1>
<h3 align="center">Full-Stack Developer • Reverse Engineer • Security Researcher</h3>

<div align="center">
  <img src="https://raw.githubusercontent.com/gilbarbara/logos/master/logos/windows.svg" height="32" />
  <img src="https://raw.githubusercontent.com/gilbarbara/logos/master/logos/linux-tux.svg" height="32" />
  <img src="https://raw.githubusercontent.com/gilbarbara/logos/master/logos/apple.svg" height="32" />
</div>

---

## 🔥 Summary

I'm **DoctorX**, a full-stack engineer and reverse-engineering specialist.  
I build **desktop applications, backend APIs, dev-tools, automation systems, and security-focused utilities**.  
My work spans:

- Low-level analysis (IDA, Ghidra, x64dbg, Radare)
- Deobfuscation, unpacking, malware behavior research
- Game hacking & memory instrumentation
- API design with Node.js, Go, and .NET
- Desktop software in C#, Avalonia, WinForms, WPF
- Linux tooling, GNOME extensions, and Bash automation
- Web apps with React + TypeScript
- Tooling ecosystems & internal developer infrastructure

> My focus: **clean architecture, performance, security, and reverse engineering.**

---

## 🧩 Skills Overview

### 💻 Languages
<p>
  <img src="https://skillicons.dev/icons?i=cs,go,ts,js,cpp,bash,python&perline=10" />
</p>

### 🏗 Backend & APIs
<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express,go,dotnet,mongodb,postgres,redis&perline=10" />
</p>

### 🎨 Frontend
<p>
  <img src="https://skillicons.dev/icons?i=react,tailwind,html,css&perline=10" />
</p>

### 🖥 Desktop & Tools
<p>
  <img src="https://skillicons.dev/icons?i=dotnet,visualstudio,vscode&perline=10" />
</p>

### 🛡 Reverse Engineering & Security
<div>
  <img src="https://img.shields.io/badge/IDA%20Pro-202020?style=for-the-badge&logo=hackaday&logoColor=white" />
  <img src="https://img.shields.io/badge/Ghidra-FF0000?style=for-the-badge&logo=ghidra&logoColor=white" />
  <img src="https://img.shields.io/badge/x64dbg-1f1f1f?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Reverse%20Engineering-000000?style=for-the-badge&logo=linux&logoColor=white" />
  <img src="https://img.shields.io/badge/Deobfuscation-444444?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Game%20Hacking-141414?style=for-the-badge" />
</div>

---

## 🧪 Featured Projects

### 📨 **ArrowSender – Advanced Messaging Automation**
A powerful desktop automation suite for:
- Messenger / WhatsApp operations  
- Campaigns, safe-mode sending, message queueing  
- WebView2 integration  
- Custom UX + licensing + secure storage  

**Tech:** C#, WinForms / Avalonia, Node.js backend, MongoDB  
**Status:** Private

---

### 🛠 **GRZ Tool – Reverse Engineering Utilities**
A toolkit for:
- Static + dynamic analysis  
- Scriptable unpacking  
- Low-level binary inspection  
- Memory scanning + patching  

**Tech:** C#, Native modules, x64dbg scripting  
**Status:** Private

---

## 🧑‍💻 Linux & Bash Work

I build:
- Gnome extensions  
- Shell utilities  
- System automation scripts  
- Developer workflow enhancements  

```bash
# sample: auto-restart service watcher
while true; do
  if ! systemctl is-active --quiet backend.service; then
      echo "[!] Restarting backend..."
      systemctl restart backend.service
  fi
  sleep 3
done
