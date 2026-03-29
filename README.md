# Full-Stack Developer & Linux/DevOps Engineer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/muhammad-rizwan-dot-net-developer)
[![Portfolio](https://img.shields.io/badge/Portfolio-View_Projects-orange?logo=github)](https://github.com/rizvawn)
[![Email](https://img.shields.io/badge/Email-Contact-red?logo=gmail)](mailto:rizvawn@gmail.com)

---

## 🚀 About Me

I'm building skills across backend development, Linux systems, and DevOps practices through hands-on projects. This portfolio documents working code and real implementations.

---

## 📂 Projects

### Heart Disease Predictor ✅

**Repository:** [`heart-disease-predictor`](https://github.com/rizvawn/heart-disease-predictor)

A machine-learning project that predicts heart disease from patient health metrics using a clean, object-oriented Python architecture. It includes a full workflow—data loading/inspection, exploratory analysis in Jupyter, model training/evaluation, and a terminal-based app for running predictions with a saved model.

**Key highlights:**

- End-to-end ML pipeline: data processing → EDA (notebooks) → model training → CLI predictions
- Object-oriented, modular structure: `DataProcessor`, `ModelTrainer`, `TerminalApp`
- Dataset: Kaggle Heart Disease dataset (1,025 records, 13 features + binary target)
- Model artifact: saves a trained model for reuse at `models/best_model.pkl`

**Technologies:** Python · Jupyter Notebook · scikit-learn · pandas · matplotlib/seaborn

---

### MongoDB Bash Workshop ✅

**Repository:** [`mongodb-bash-workshop`](https://github.com/rizvawn/mongodb-bash-workshop)

A hands-on educational project demonstrating core MongoDB concepts through executable Bash scripts. The workshop walks through CRUD operations (Create, Read, Update, Delete), document modeling strategies, cross-collection lookups, and schema validation, all driven directly from the command line using `mongosh` inside a Docker-hosted MongoDB instance.

**Key highlights:**

- 10 sequential Bash scripts covering the full MongoDB fundamentals workflow
- Executing CRUD operations directly via MongoDB Shell (`mongosh`) without abstraction layers
- Embedded vs. referenced document modeling with practical trade-off analysis
- JSON Schema validation enforced at the database level (`collMod`)
- Fully repeatable via a single `run_all.sh` orchestration script

**Technologies:** MongoDB · Bash · Docker · mongosh · JSON Schema

---

### Python Pandas Cleaner ✅

**Repository**: [`python-pandas-cleaner`](https://github.com/rizvawn/python-pandas-cleaner)

A data processing pipeline using Pandas to clean messy CSV files and transform them into structured JSON. Demonstrates:

- Robust data validation and cleaning
- Date parsing with fallback strategies
- Handling nullable types (Int64)
- JSON serialization with type fidelity considerations

**Tech**: Python, Pandas

---

### RHEL Navigator ✅

**Repository:** [`rhel-navigator`](https://github.com/rizvawn/rhel-navigator)

A production-grade Red Hat Enterprise Linux (RHEL) system reconnaissance and auditing tool built around a “configure-then-verify” workflow. It demonstrates practical Linux administration and security best practices by pairing hands-on system configuration tasks with automated validation checks, using Bash for orchestration and Python for JSON parsing and higher-level logic.

**Key highlights:**

- RHEL-focused auditing and validation: OS fingerprinting, user/account checks, file permission verification
- Admin & observability tooling: `systemctl` service checks, `journalctl` log analysis, disk/LVM usage checks
- Security + infrastructure checks: network listener auditing via `ss`, SSH key permission audits (Ed25519), timestamped backup generation
- Container inspection support: analyzes Podman container state by parsing JSON output with Python
- FHS-aligned layout with a single main executable (`bin/navigator`) plus supporting `etc/`, `lib/`, and `var/` directories

**Technologies:** Bash · Python · systemd (`systemctl`) · `journalctl` · Podman · Linux utilities (`ss`, `awk`, `grep`)

---

### Package Management Dashboard ✅

**Repository:** [`package-management-dashboard`](https://github.com/rizvawn/package-management-dashboard)

Shell-based toolkit for package management analysis on RHEL/Fedora systems, exposed through a unified `pkg` CLI:

- Query installed packages with totals and disk usage
- Search repositories (DNF5-compatible) with install status
- Inspect package metadata, files, changelog, and direct dependencies
- Validate repo health (enabled/disabled, package counts, accessibility)

**Tech:** Bash · DNF5/DNF4 · YUM · RPM · awk/sed/grep

---

### Bash Globbing Mastery ✅

**Repository**: [`bash-globbing`](https://github.com/rizvawn/bash-globbing)

Linux kernel source analysis using Bash glob patterns, from basic wildcards to advanced pattern matching:

- Basic wildcards (`*`, `?`, `*/`)
- Character classes and brace expansion
- Extended globbing (`extglob`, `globstar`)
- Recursive pattern matching with `**/*.c`

**Tech**: Bash, Linux

---

### Linux System Explorer ✅

**Repository**: [`linux-system-explorer`](https://github.com/rizvawn/linux-system-explorer)

Interactive Filesystem Hierarchy Standard (FHS) navigation tool:

- Interactive FHS navigation script with dual interface (menu/CLI)
- Scenario-based quiz system with state management
- Integrated FHS cheatsheet covering 15 directories
- Comprehensive unit testing with BATS framework

**Tech**: Bash, Linux, BATS

---

## 🛠️ Tech Stack

### Languages & Core Skills

![C#](https://img.shields.io/badge/C%23-239120?logo=c-sharp&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnu-bash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)

### Frameworks & Tools

![.NET](https://img.shields.io/badge/.NET_8-512BD4?logo=dotnet&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)

---

## 🤝 Connect

Reach out to discuss projects, collaboration, or learning:

- 📧 Email: [rizvawn@gmail.com](mailto:rizvawn@gmail.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/muhammad-rizwan-dot-net-developer)

---

**Last Updated**: December 22, 2025
