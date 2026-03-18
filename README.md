<div align="center">

```
██████╗  ██████╗  ██████╗████████╗ ██████╗ ██████╗ ██╗  ██╗
██╔══██╗██╔═══██╗██╔════╝╚══██╔══╝██╔═══██╗██╔══██╗╚██╗██╔╝
██║  ██║██║   ██║██║        ██║   ██║   ██║██████╔╝ ╚███╔╝ 
██║  ██║██║   ██║██║        ██║   ██║   ██║██╔══██╗ ██╔██╗ 
██████╔╝╚██████╔╝╚██████╗   ██║   ╚██████╔╝██║  ██║██╔╝ ██╗
╚═════╝  ╚═════╝  ╚═════╝   ╚═╝    ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝
```

</div>

---

I build things that live between the OS and the model — autonomous agents, real-time vision pipelines, reverse engineering tooling, and backend infrastructure. The focus is always on correctness and things that run in the real world, not just in demos.

Most of what I work on starts with a problem that off-the-shelf tools can't solve cleanly, which means building the entire stack from scratch: from raw screen data to a deployable model, or from a memory dump to a working disassembly.

---

## 🤖 AI & Intelligent Systems

- Autonomous agents with closed-loop pipelines: screen capture → inference → action
- Real-time object detection and classification using YOLO and custom-trained models
- Dataset construction from scratch: synthetic generation, labeling pipelines, augmentation, evaluation
- Fine-tuning vision and language models for domain-specific tasks (PyTorch, Transformers, TRL)
- Hybrid decision systems: learned policy combined with deterministic rule engines
- Reinforcement learning in controlled simulated environments
- Integration with local models (Ollama, llama.cpp) and cloud APIs (OpenAI, Anthropic, OpenRouter)

#### Arabic NLP

- Fine-tuning LLMs for Arabic conversational tasks — Qwen, AraGPT, and custom architectures
- Specialization in dialectal Arabic: Palestinian and Levantine speech patterns, tone, and cultural context
- Full SFT pipeline: dataset cleaning, multi-turn dialogue formatting, tokenization, and training under GPU constraints
- Building Arabic agents with strong personality consistency and dialect accuracy — not just translation

---

## ⚙️ Systems & Backend

- Go, C#/.NET, Node.js
- REST APIs, microservice decomposition, background job queues
- MongoDB, PostgreSQL, Redis — schema design, query optimization, caching strategies
- Auth systems: JWT, OAuth2, session management
- Performance-focused design: profiling, reducing allocations, minimizing serialization overhead
- Async pipelines and event-driven processing

---

## 🖥️ Desktop & Automation

- Native Windows applications: WinForms, WPF, Avalonia UI (XAML)
- Settings management systems with encryption and secure local storage
- WebView2 embedding and host-object bridging
- System-level automation: input simulation, window management, screen capture
- Click-through overlay rendering with Win32 layered window APIs
- Multi-language UI handling: Arabic/English bidirectional layouts

---

## 🔬 Low-Level & Kernel

- Windows internals: memory layout, process/thread model, executive subsystems
- Kernel-mode development and Windows Driver (WDM/KMDF) fundamentals
- Defensive security: anti-rootkit concepts, driver signing, and detection techniques
- C++ systems programming — memory management, object layout, compiler behavior
- Computer architecture: instruction pipelines, cache behavior, calling conventions

---

## 🔍 Reverse Engineering & Security

- Static analysis: IDA Pro, Ghidra, Radare2
- Dynamic analysis: x64dbg, memory inspection, runtime patching
- Obfuscated and protected code analysis — unpacking, import reconstruction, string decryption
- Cryptography and compression in real-world binaries
- Game instrumentation and memory mapping
- PE format internals

---

## 🐧 Linux & DevOps

- Bash scripting and system automation
- GNOME Shell extension development
- CI/CD pipeline configuration (GitHub Actions, Docker)
- Log aggregation and monitoring setups
- Service hardening and resource management

---

## Stack

<div align="center">

<table>
<tr>
<td align="right"><b>Languages</b></td>
<td>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/>
<img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white"/>
<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white"/>
<img src="https://img.shields.io/badge/x86_ASM-6E4C13?style=flat-square"/>
</td>
</tr>
<tr>
<td align="right"><b>AI / ML</b></td>
<td>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>
<img src="https://img.shields.io/badge/Ultralytics_YOLO-111F68?style=flat-square"/>
<img src="https://img.shields.io/badge/HuggingFace-FFD21F?style=flat-square&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/TRL-FF6F00?style=flat-square"/>
<img src="https://img.shields.io/badge/llama.cpp-8B0000?style=flat-square"/>
</td>
</tr>
<tr>
<td align="right"><b>Backend</b></td>
<td>
<img src="https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white"/>
</td>
</tr>
<tr>
<td align="right"><b>Desktop</b></td>
<td>
<img src="https://img.shields.io/badge/WinForms-0078D4?style=flat-square&logo=windows&logoColor=white"/>
<img src="https://img.shields.io/badge/WPF-0078D4?style=flat-square&logo=windows&logoColor=white"/>
<img src="https://img.shields.io/badge/Avalonia-8B44AC?style=flat-square"/>
<img src="https://img.shields.io/badge/Win32_API-0078D4?style=flat-square&logo=windows&logoColor=white"/>
</td>
</tr>
<tr>
<td align="right"><b>RE Tools</b></td>
<td>
<img src="https://img.shields.io/badge/IDA_Pro-990000?style=flat-square"/>
<img src="https://img.shields.io/badge/Ghidra-FF0000?style=flat-square"/>
<img src="https://img.shields.io/badge/x64dbg-555555?style=flat-square"/>
<img src="https://img.shields.io/badge/Radare2-333333?style=flat-square"/>
<img src="https://img.shields.io/badge/Frida-E67E22?style=flat-square"/>
</td>
</tr>
<tr>
<td align="right"><b>DevOps</b></td>
<td>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
</td>
</tr>
</table>

</div>

---

## What I Build

- Agents that read live application state and act autonomously — driven by vision, not APIs
- End-to-end training pipelines from raw screen data to a deployable classification model
- Arabic conversational agents with genuine dialect accuracy and consistent personality
- Automation systems that handle repetitive OS-level interaction reliably
- Internal tools that reduce friction in day-to-day engineering work
- Backend services designed to stay lean and stable under real usage

---

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=DoctorX&show_icons=true&theme=default&hide_border=true&hide=stars&count_private=true)

</div>

---

<div align="center">
<sub>The repositories are more up to date than this page.</sub>
</div>
