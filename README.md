# 🧪 Debian 12 EPICS Training Environment

This repository contains a personal development and training environment for working with [EPICS](https://epics-controls.org/) (Experimental Physics and Industrial Control System) on Debian 12. It includes tools, IOC repositories, and configuration files used to build, test, and maintain soft IOCs, device support, and related control system utilities. Much of the structure and content is based on the tutorials available at [Han's EPICS Training Site](https://jeonghanlee.github.io/epics-trainings/introduction.html).

---

## 📁 Repository Structure

```
.  
├── epics/            # EPICS base and modules  
├── mouse/            # IOC and driver source for 'mouse'  
├── rain-mouse/       # Customized version of 'mouse' IOC  
├── tools/            # Utility scripts and EPICS tools  
├── training/         # Training and reference materials  
├── orig.mouse/       # Original untouched 'mouse' repo  
├── orig.tools/       # Original untouched 'tools' repo  
├── .gitignore  
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

- Debian 12 system (bare metal or VM)  
- Basic knowledge of EPICS and shell commands  
- GCC, `make`, and build tools installed

### Clone the Repository

```bash
git clone git@github.com:your-username/deb12-epics-training.git  
cd deb12-epics-training
```

### EPICS Setup

```bash
cd epics  
# Build base and modules here (if applicable)  
make
```

---

## 🧰 Included IOCs & Tools

- **mouse/**: Basic test IOC for mouse input/output simulation  
- **rain-mouse/**: Customized fork with additional features or logging  
- **tools/**: Utility scripts, dev tools, and diagnostics  
- **training/**: Scripts and exercises for learning EPICS structure, macros, and build

---

## 📦 Git Best Practices

### .gitignore

This repo ignores sensitive and system-specific directories:

```
.local/  
.ssh/
```

If you add environment-specific credentials or logs, extend the `.gitignore` accordingly.

---

## 🛡️ Security

Please ensure that no SSH keys, credentials, or private configuration files are ever committed. This repo is set up to ignore `.ssh` and `.local`, but always double-check `git status` before committing.

---

## 🤝 Acknowledgments

- [EPICS Base](https://epics-controls.org/resources-and-support/base/)  
- [Debian](https://www.debian.org/)  
- Custom tools and forks adapted from internal training sessions

---

## 📜 License

This repository is for educational and internal use. Please contact the author for reuse.

---

## 🧑‍💻 Author

**Rob Rainer**  
Senior Technology Engineer – Accelerator & Data Sciences  
📧 rainer1370@gmail.com  
🔗 [Rainer1370.com](https://rainer1370.com)
