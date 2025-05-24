# 🛡️ try‑hack‑me

> Personal knowledge base & hands‑on write‑ups for the [TryHackMe](https://tryhackme.com) platform.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  [![Last Updated](https://img.shields.io/github/last-commit/giterror/try-hack-me?label=last%20updated)](#)

---

## 📚 What’s inside?

- **Room notes** – condensed takeaways and command snippets.  
- **Walk‑throughs** – step‑by‑step solutions with context and screenshots.  
- **Scripts & payloads** – helper code I wrote or modified for specific tasks.  
- **Cheat‑sheets** – quick reference for commonly used tools and techniques.

> **Disclaimer:** All content is for _educational purposes only_. Attack only the boxes you own or have explicit permission to test.

---

## 🏗️ Repo structure

```text
.
├── rooms/
│   ├── offensive-security-intro/
│   │   ├── writeup.md
│   │   └── assets/
│   ├── defensive-security-intro/
│   └── …
├── scripts/
│   └── nmap/
├── cheatsheets/
└── README.md
```

---

## 🚀 Getting started

```bash
# Clone the repo
git clone https://github.com/giterror/try-hack-me.git
cd try-hack-me
```

### Prerequisites

- Active TryHackMe account  
- Kali / Parrot / Docker‑based lab (recommended)  
- Basic Linux & networking experience  

---

## 📝 How to use the notes

1. Open the folder under **`rooms/`** that matches the room name.  
2. Follow the numbered steps in `writeup.md` to reproduce the exploit.  
3. Rinse & repeat in a safe, isolated lab environment.  

---

## 🤝 Contributing

Spotted a typo, missing step, or have a better exploit? PRs are welcome!

Commit message convention:

```text
feat(room): add Buffer Overflow Prep note
fix(script): handle IPv6 targets
docs(readme): update badges
```

---

## 📜 License

Distributed under the MIT License. See [`LICENSE`](LICENSE) for details.

---

## 🙏 Acknowledgements

- [TryHackMe](https://tryhackme.com) for the awesome learning platform.  
- The broader offensive‑security community for tools, tips, and inspiration.  

---

Happy hacking 🎉
