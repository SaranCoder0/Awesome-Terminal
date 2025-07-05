# 🔥 Awesome-Terminal — Powered by Athena OS ✨

A powerful terminal enhancement toolkit, built upon the solid foundation of [Athena OS](https://github.com/Athena-OS), tailored for cybersecurity professionals, DFIR analysts, and ethical hackers.

## 📎 Description

This repo contains a modified version of the `.bashrc` and `.bash_aliases` files **originally pulled from the Athena OS project**, customized for terminal productivity, faster navigation, and simplified command execution.

> 🧠 **Credit**: Base configuration and structure sourced from [Athena OS GitHub Repo](https://github.com/Athena-OS). Extended and modified by [Spower](https://github.com/SaranCoder0) for enhanced cybersecurity workflows.

---

## 🚀 Features

- 🧩 Athena-style terminal with Git-aware prompt and emoji indicators
- ⚙️ Useful aliases for `apt`, `pacman`, `git`, system cleanup, unlock, and more
- 🔐 Security & hacking tools ready to integrate (e.g., `nmap`, `netstat`, `whois`)
- 🖼️ Custom system info with `fastfetch`/`neofetch`
- 📜 Friendly pager fix (`core.pager=less`) for better Git UX

---

## 🛠️ Installation

```bash
git clone https://github.com/SaranCoder0/Awesome-Terminal.git
cd Awesome-Terminal
# Review and copy the files you want:
cp .bashrc ~/.bashrc
cp .bash_aliases ~/.bash_aliases
source ~/.bashrc
