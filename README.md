<div align="center">

# 🎓 Bitnami LMS Moodle

### 🚀 Ready-to-Deploy Moodle Learning Management System

A preconfigured **Bitnami + Moodle virtual machine** designed to make deploying a complete LMS simple, fast, and accessible.

<br>

[![Moodle](https://img.shields.io/badge/Moodle-LMS-orange?style=for-the-badge&logo=moodle)](https://moodle.org/)
[![Bitnami](https://img.shields.io/badge/Bitnami-VM-blue?style=for-the-badge)](https://bitnami.com/)
[![VirtualBox](https://img.shields.io/badge/VirtualBox-Compatible-183A61?style=for-the-badge&logo=virtualbox)](https://www.virtualbox.org/)
[![Linux](https://img.shields.io/badge/Linux-Supported-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://www.linux.org/)

<br>

<a href="https://github.com/youssef-bahida/Bitnami-LMS-Moodle">
  <img src="https://img.shields.io/badge/⭐%20Star%20Repository-yellow?style=for-the-badge" alt="Star Repository">
</a>

<a href="https://github.com/youssef-bahida/Bitnami-LMS-Moodle/issues">
  <img src="https://img.shields.io/badge/🐛%20Report%20Issue-red?style=for-the-badge" alt="Report Issue">
</a>

<a href="https://github.com/youssef-bahida/Bitnami-LMS-Moodle/fork">
  <img src="https://img.shields.io/badge/🍴%20Fork%20Project-blue?style=for-the-badge" alt="Fork Project">
</a>

</div>

---

## 📖 About

**Bitnami LMS Moodle** is a ready-to-deploy Moodle Learning Management System packaged as a virtual machine.

The project aims to simplify the deployment of a complete Moodle environment by providing a preconfigured server that can be imported into virtualization software such as **VirtualBox** or **VMware**.

Instead of manually installing and configuring:

```text
Linux
   ↓
Web Server
   ↓
Database
   ↓
PHP
   ↓
Moodle
   ↓
Configuration



                    ┌──────────────────────────┐
                    │      Host Computer       │
                    │                          │
                    │  Windows / Linux / etc.  │
                    └────────────┬─────────────┘
                                 │
                                 ▼
                    ┌──────────────────────────┐
                    │     VirtualBox / VMware  │
                    └────────────┬─────────────┘
                                 │
                                 ▼
             ┌────────────────────────────────────┐
             │          Moodle Virtual Machine    │
             │                                    │
             │  ┌──────────────────────────────┐  │
             │  │          Bitnami             │  │
             │  ├──────────────────────────────┤  │
             │  │           Moodle             │  │
             │  ├──────────────────────────────┤  │
             │  │       Web Server / PHP        │  │
             │  ├──────────────────────────────┤  │
             │  │          Database             │  │
             │  └──────────────────────────────┘  │
             └────────────────┬───────────────────┘
                              │
                              ▼
                    ┌─────────────────────┐
                    │   Moodle Web UI     │
                    │                     │
                    │ Teachers / Students │
                    └─────────────────────┘




Bitnami-LMS-Moodle/
│
├── 📄 README.md
│
├── ⚙️ install.sh
├── ⬇️ download-vm.sh
├── 🔎 verify-vm.sh
├── ✂️ split-vm.sh
├── 🔗 join-vm.sh
│
├── 📂 scripts/
│   ├── start-vm.sh
│   ├── stop-vm.sh
│   └── backup.sh
│
└── 📂 docs/
    └── INSTALLATION.md
