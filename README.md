<div align="center">

# Mohamed Elsherbini

**`N4P1`** · Security research · Embedded systems · CTF

[![IEEE ITC-Egypt 2026](https://img.shields.io/badge/IEEE%20ITC--Egypt%202026-Published-00629B?style=flat-square)](https://ieeexplore.ieee.org/document/11765755)
[![CTFtime rank](https://img.shields.io/badge/dynamic/json?color=FF2D55&label=N!ghtM4re%20world%20rank&query=%24.rating.2026.rating_place&url=https%3A%2F%2Fctftime.org%2Fapi%2Fv1%2Fteams%2F418706%2F&style=flat-square)](https://ctftime.org/team/418706)

</div>

---

Security researcher from Egypt. My work looks at what happens to cryptography when the hardware underneath it misbehaves — software-induced faults on ESP32, and cheap ways to recover when they land. I compete with [N!ghtM4re](https://ctftime.org/team/418706), 4th in Egypt and top 100 worldwide, and build security tooling in the open.

---

## Research

### Cyber-FIE: A Software-Induced Memory Fault Injection Framework for Evaluating AES-256 Resilience on ESP32

A. E. Takieldeen, Z. A. Mashaly, **M. H. El Sherbini**, H. M. Attia, S. H. Hagag, E. A. Takieldeen  
*2026 International Telecommunications Conference (ITC-Egypt)*, pp. 56–61, New Capital, Egypt, July 2026.

[IEEE Xplore](https://ieeexplore.ieee.org/document/11765755) · [doi:10.1109/ITC-EGYPT70422.2026.11765755](https://doi.org/10.1109/ITC-EGYPT70422.2026.11765755) · [PDF](https://github.com/N4P1x/Research-Papers/raw/master/Cyber-FIE.pdf)

Most fault injection assumes a lab: voltage glitches, lasers, a bench setup. Cyber-FIE asks how far you can get with pointer arithmetic alone — direct reads and writes into the stack, heap, and active AES context of an ESP32-D0WDQ6, using C++ and a small injection engine. No ECC RAM, no hardware attacker.

What the experiments showed:

- **3,560** hardware trials over four months
- **100%** functional failure against legacy DES/3DES (1,240/1,240)
- **12.3%** critical failure rate against AES-256 (95% CI 11.2–13.4%), at **14.7 µs** fault latency
- **28.0%** system crashes at higher injection frequencies — the watchdog timer firing on corrupted state; most of the experimental work was timing calibration
- **Shield**, a self-healing protocol with a lightweight runtime integrity check, recovered **94.2%** of keys; the remaining 5.8% was mostly hash collisions and race conditions

I worked on the injection engine, the ESP32 test harness, and the timing calibration.

<details>
<summary>Cite this paper</summary>

```bibtex
@inproceedings{takieldeen2026cyberfie,
  title     = {Cyber-FIE: A Software-Induced Memory Fault Injection Framework
               for Evaluating AES-256 Resilience on ESP32},
  author    = {Takieldeen, Ali E. and Mashaly, Ziad A. and
               El Sherbini, Mohamed H. and Attia, Haitham M. and
               Hagag, Sayed H. and Takieldeen, Eslam A.},
  booktitle = {2026 International Telecommunications Conference (ITC-Egypt)},
  pages     = {56--61},
  year      = {2026},
  doi       = {10.1109/ITC-EGYPT70422.2026.11765755}
}
```

</details>

---

## Selected work

| | | |
|:---|:---|---:|
| [Night-Watch](https://github.com/N4P1x/Night-Watch) | Tor-aware dark web and ransomware monitoring. FastAPI, React, Redis, Docker. | [![stars](https://img.shields.io/github/stars/N4P1x/Night-Watch?style=flat-square&label=)](https://github.com/N4P1x/Night-Watch) |
| [Malware-Hunter](https://github.com/N4P1x/Malware-Hunter) | PE malware classification with scikit-learn, enriched with VirusTotal data. | [![stars](https://img.shields.io/github/stars/N4P1x/Malware-Hunter?style=flat-square&label=)](https://github.com/N4P1x/Malware-Hunter) |
| [YoRHa-Deauther](https://github.com/N4P1x/YoRHa-Deauther) | ESP32 Wi-Fi deauthentication tooling with a browser UI, built on ESP-IDF. | [![stars](https://img.shields.io/github/stars/N4P1x/YoRHa-Deauther?style=flat-square&label=)](https://github.com/N4P1x/YoRHa-Deauther) |
| [mini-ter](https://github.com/N4P1x/mini-ter) | Arch Linux + Hyprland setup, Material You colors. | [![stars](https://img.shields.io/github/stars/N4P1x/mini-ter?style=flat-square&label=)](https://github.com/N4P1x/mini-ter) |
| [Writeups](https://github.com/N4P1x/Writeups) | 19 challenge writeups across 3 CTFs. | [![stars](https://img.shields.io/github/stars/N4P1x/Writeups?style=flat-square&label=)](https://github.com/N4P1x/Writeups) |

---

## Toolbox

`Python` `C++` `ESP32 / ESP-IDF` `FastAPI` `React` `Docker` `Linux` `Hyprland` `Nmap` `Metasploit`

Reverse engineering, malware analysis, DFIR, wireless security, OSINT, threat intelligence, OT/ICS security.

---

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/mohamed-elsherbini-41671b2b1) · [n4p1.me](https://n4p1.me) · [sh3rb1n1@gmail.com](mailto:Sh3rb1n1@gmail.com) · [CTFtime](https://ctftime.org/team/418706) · [Research papers](https://github.com/N4P1x/Research-Papers)

---

## Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=N4P1x&theme=tokyo-night&hide_border=true" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=N4P1x&theme=github-light&hide_border=true" />
  <img alt="Contribution activity" src="https://github-readme-activity-graph.vercel.app/graph?username=N4P1x&theme=tokyo-night&hide_border=true" width="100%" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/N4P1x/N4P1x/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/N4P1x/N4P1x/output/github-contribution-grid-snake.svg" />
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/N4P1x/N4P1x/output/github-contribution-grid-snake.svg" width="100%" />
</picture>

---

<div align="center">

_Exploiting systems. Securing knowledge._

</div>
