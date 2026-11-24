<div align="center">

[![Status](https://img.shields.io/badge/Status-Research%20%26%20Building-2EA043?style=for-the-badge)](#)
[![Based in](https://img.shields.io/badge/Based%20in-Egypt-0066FF?style=for-the-badge)](#)
[![Team](https://img.shields.io/badge/Team-N!ghtM4re-FF2D55?style=for-the-badge)](https://ctftime.org/team/418706)
[![IEEE Published](https://img.shields.io/badge/IEEE-ITC--Egypt%20'26-00629B?style=for-the-badge)](https://ieeexplore.ieee.org/document/11765755)

# Mohamed Elsherbini

### `N4P1` · Security Researcher · CTF Player · Embedded Security

**I break embedded crypto in the lab — then build the defenses that survive it.**

[🔬 Research](#-featured-research) · [🛠 Projects](#-selected-projects) · [📈 Activity](#-activity) · [🧰 Toolkit](#-toolkit) · [📫 Connect](#-connect)

<br>

<img src="https://komarev.com/ghpvc/?username=N4P1x&label=Profile%20Views&color=0066ff&style=for-the-badge" alt="Profile Views"/>

</div>

---

## 👋 About

Cybersecurity researcher and CTF competitor from Egypt, currently hacking with **N!ghtM4re** — ranked **4th nationally** and **top 100 worldwide** on [CTFtime](https://ctftime.org/team/418706).

My work sits at the intersection of **embedded systems, applied cryptography, and offensive security**: fault injection on real hardware, memory-safety exploitation, malware analysis, and DFIR. I co-authored **Cyber-FIE**, now published in the IEEE *2026 International Telecommunications Conference (ITC-Egypt)*.

| 🔬 IEEE Publication | 🧪 Hardware Trials | 🏆 CTF | 🛠 Open Source |
|:---:|:---:|:---:|:---:|
| **ITC-Egypt '26** | **3,560** | **Top 100 worldwide** | **5 featured repos** |

---

## 🔬 Featured Research

> ### Cyber-FIE
> **A Software-Induced Memory Fault Injection Framework for Evaluating AES-256 Resilience on ESP32**

[![IEEE Xplore](https://img.shields.io/badge/IEEE%20Xplore-Paper-00629B?style=for-the-badge)](https://ieeexplore.ieee.org/document/11765755)
[![DOI](https://img.shields.io/badge/DOI-10.1109%2FITCEGYPT70422.2026.11765755-4B9E79?style=for-the-badge)](https://doi.org/10.1109/ITC-EGYPT70422.2026.11765755)
[![PDF](https://img.shields.io/badge/PDF-Download-E95420?style=for-the-badge)](https://github.com/N4P1x/Research-Papers/raw/master/Cyber-FIE.pdf)

*Ali E. Takieldeen, Ziad A. Mashaly, **Mohamed H. El Sherbini**, Haitham M. Attia, Sayed H. Hagag, Eslam A. Takieldeen*

*2026 International Telecommunications Conference (ITC-Egypt) · pp. 56–61 · New Capital, Egypt · July 2026*

Most fault-injection research assumes expensive lab gear. **Cyber-FIE** asks what happens when the attack is pure software: direct memory access through C++ pointer arithmetic — no voltage glitching, no lasers. We validated the framework on an **ESP32-D0WDQ6** and measured how AES-256 holds up against corruption of its active cryptographic context.

| Metric | Result |
|:---|:---|
| Hardware trials | **3,560** over 4 months |
| Legacy DES/3DES | **100%** functional failure (1,240 / 1,240) |
| AES-256 | **12.3%** critical failure rate (95% CI: 11.2–13.4%) |
| Fault latency | **14.7 µs** |
| **Shield** (self-healing protocol) | **94.2%** key recovery with a lightweight runtime integrity check |

I contributed to the fault-injection engine and the experimental evaluation, including the timing calibration needed to keep watchdog interference from skewing the results.

> *"The disconnect between cryptographic algorithmic robustness and physical execution security is particularly evident in embedded systems that do not employ Error Correction Code (ECC) RAM."*

---

## 🛠 Selected Projects

| Project | Stars | Description | Stack |
|:---|:---:|:---|:---|
| [**Night-Watch**](https://github.com/N4P1x/Night-Watch) | [![stars](https://img.shields.io/github/stars/N4P1x/Night-Watch?style=flat-square&label=)](https://github.com/N4P1x/Night-Watch) | Dark web & ransomware threat intelligence platform | `FastAPI` · `React` · `Docker` · `Tor` · `Redis` |
| [**Malware-Hunter**](https://github.com/N4P1x/Malware-Hunter) | [![stars](https://img.shields.io/github/stars/N4P1x/Malware-Hunter?style=flat-square&label=)](https://github.com/N4P1x/Malware-Hunter) | ML-based PE malware detection system | `Python` · `Flask` · `Scikit-learn` · `VirusTotal` |
| [**YoRHa-Deauther**](https://github.com/N4P1x/YoRHa-Deauther) | [![stars](https://img.shields.io/github/stars/N4P1x/YoRHa-Deauther?style=flat-square&label=)](https://github.com/N4P1x/YoRHa-Deauther) | ESP32 Wi-Fi deauthentication tool with a web interface | `C++` · `ESP-IDF` · `Web UI` |
| [**mini-ter**](https://github.com/N4P1x/mini-ter) | [![stars](https://img.shields.io/github/stars/N4P1x/mini-ter?style=flat-square&label=)](https://github.com/N4P1x/mini-ter) | Custom Arch Linux + Hyprland setup | `Wayland` · `Material You` |
| [**Writeups**](https://github.com/N4P1x/Writeups) | [![stars](https://img.shields.io/github/stars/N4P1x/Writeups?style=flat-square&label=)](https://github.com/N4P1x/Writeups) | CTF writeups — 19 challenges across 3 CTFs | `Markdown` · `Python` |

---

## 📈 Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=N4P1x&theme=tokyo-night&hide_border=true" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=N4P1x&theme=github-light&hide_border=true" />
  <img alt="Contribution Activity Graph" src="https://github-readme-activity-graph.vercel.app/graph?username=N4P1x&theme=tokyo-night&hide_border=true" width="100%" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/N4P1x/N4P1x/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/N4P1x/N4P1x/output/github-contribution-grid-snake.svg" />
  <img alt="Contribution Snake" src="https://raw.githubusercontent.com/N4P1x/N4P1x/output/github-contribution-grid-snake.svg" width="100%" />
</picture>

---

## 🧰 Toolkit

<div align="center">

**Security**

[![Ethical Hacking](https://img.shields.io/badge/Ethical%20Hacking-FF2D55?style=for-the-badge)](#)
[![Reverse Engineering](https://img.shields.io/badge/Reverse%20Engineering-8A2BE2?style=for-the-badge)](#)
[![Malware Analysis](https://img.shields.io/badge/Malware%20Analysis-D14836?style=for-the-badge)](#)
[![DFIR](https://img.shields.io/badge/DFIR-1F6FEB?style=for-the-badge)](#)
[![Wireless Security](https://img.shields.io/badge/Wireless%20Security-00A8A8?style=for-the-badge)](#)
[![OSINT](https://img.shields.io/badge/OSINT-6E7681?style=for-the-badge)](#)
[![Threat Intelligence](https://img.shields.io/badge/Threat%20Intelligence-D97706?style=for-the-badge)](#)
[![OT / ICS Security](https://img.shields.io/badge/OT%20%2F%20ICS%20Security-BE4D00?style=for-the-badge)](#)

**Engineering**

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](#)
[![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)](#)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](#)
[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)](#)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](#)
[![ESP32](https://img.shields.io/badge/ESP32-ESP--IDF-E7352C?style=for-the-badge)](#)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](#)
[![Nmap](https://img.shields.io/badge/Nmap-5A7DCE?style=for-the-badge&logo=nmap&logoColor=white)](#)
[![Metasploit](https://img.shields.io/badge/Metasploit-4B0082?style=for-the-badge)](#)
[![Hyprland](https://img.shields.io/badge/Hyprland-2E3440?style=for-the-badge)](#)

</div>

---

## 📫 Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohamed-elsherbini-41671b2b1)
[![Website](https://img.shields.io/badge/Website-1E90FF?style=for-the-badge&logo=firefox&logoColor=white)](https://n4p1.me)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Sh3rb1n1@gmail.com)
[![CTFtime](https://img.shields.io/badge/CTFtime-N!ghtM4re-FF2D55?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSI2NCIgaGVpZ2h0PSI2NCIgdmlld0JveD0iMCAwIDY0IDY0Ij48cGF0aCBmaWxsPSJ3aGl0ZSIgZD0iTTMyIDJMMTAgMTJ2MThjMCAxNi4yIDEwLjYgMzEuNCAyMiAzNiAxMS40LTQuNiAyMi0xOS44IDIyLTM2VjEyTDMyIDJ6bTAgNThjLTguMi0zLjQtMTYtMTUuMi0xNi0yOFYxNWwxNi02IDE2IDZ2MTdjMCAxMi44LTcuOCAyNC42LTE2IDI4eiIvPjxwYXRoIGZpbGw9IndoaXRlIiBkPSJNMjMgMjhsLTMgM2w3IDdsMTQtMTRsLTMtM2wtMTEgMTF6Ii8+PC9zdmc+)](https://ctftime.org/team/418706)
[![World Rank](https://img.shields.io/badge/dynamic/json?color=FF2D55&label=World%20Rank&query=%24.rating.2026.rating_place&url=https%3A%2F%2Fctftime.org%2Fapi%2Fv1%2Fteams%2F418706%2F&style=for-the-badge&suffix=%20worldwide)](https://ctftime.org/team/418706)

</div>

<br>

<div align="center">

**_Exploiting systems. Securing knowledge._**

</div>
