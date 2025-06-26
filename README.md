# Gitlet 🛠️ — A Mini Java Version Control

**Gitlet** is a lightweight, educational re-implementation of Git’s core features in pure Java. It’s perfect for anyone who wants to see how a VCS works “under the hood,” without relying on Git’s C code or libraries.

---

## ✨ Features

- **init** — Create a new Gitlet repository  
- **add** — Stage one or more files for the next commit  
- **commit** — Record a snapshot with a descriptive message  
- **log** — Display the project’s commit history  
- **branch** — Create and list branches  
- **checkout** — Restore files or switch branches  
- **merge** — Integrate changes from another branch  
- **SHA-1 Hashing** — Unique identifiers for commits  
- **Custom Storage** — Uses its own `.gitlet/` folder structure  

---

## 🚀 Quickstart

### Prerequisites

- Java 11 (or later)  
- Command-line access (Terminal, PowerShell, Git Bash, etc.)

### Clone & Compile

```bash
git clone https://github.com/YourUsername/gitlet.git
cd gitlet
javac gitlet/*.java
