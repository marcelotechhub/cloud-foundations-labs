# WSL, VS Code, Git, and GitHub Explained

## Goal

Understand the role of WSL, VS Code, Git, and GitHub in a Cloud, DevOps, and AI study environment.

---

## 1. What is WSL?

WSL means Windows Subsystem for Linux.

It allows Linux to run inside Windows without dual boot and without replacing Windows.

In this environment, Windows remains the main operating system, but Ubuntu runs as a Linux environment inside it.

Example:

```text
Windows 11
└── WSL
    └── Ubuntu
```

The Ubuntu environment is used to practice Linux commands, Git, Docker, Terraform, Python, and Cloud tools.

---

## 2. Why use WSL?

WSL is useful because many Cloud and DevOps environments use Linux.

By using Ubuntu inside WSL, I can practice commands similar to those used on real cloud servers.

Examples:

```bash
pwd
ls
cd
mkdir
git status
docker ps
terraform version
python3 --version
```

This helps build practical experience for Cloud Engineering, DevOps, and AI projects.

---

## 3. What is VS Code?

VS Code is a code editor.

It helps edit files, organize folders, open terminals, use Git, and work with extensions.

In this setup, VS Code runs on Windows but connects to Ubuntu through WSL.

Correct environment:

```text
WSL: Ubuntu
```

This means the files are inside Linux, but they are edited through the VS Code interface.

---

## 4. Why use VS Code?

VS Code makes it easier to work with projects.

It allows me to:

* see files and folders visually
* edit Markdown, scripts, and code
* use the integrated terminal
* use Git tools
* install extensions for Docker, Python, Terraform, and Cloud
* work directly inside WSL Ubuntu

Without VS Code, everything would need to be done manually through the terminal.

---

## 5. What is Git?

Git is a version control system.

It tracks changes in files and saves important points in the history of a project.

Important Git commands:

```bash
git status
```

Shows what changed.

```bash
git add .
```

Prepares changes to be saved.

```bash
git commit -m "message"
```

Saves a version of the project.

```bash
git log --oneline
```

Shows the commit history.

---

## 6. What is GitHub?

GitHub is an online platform that stores Git repositories.

Git works locally on the computer.

GitHub stores the project online.

Simple idea:

```text
Git = local version control
GitHub = online repository and portfolio
```

GitHub is useful for building a professional portfolio because it shows real projects, documentation, commits, and technical progress.

---

## 7. How everything works together

The workflow is:

```text
Edit files in VS Code
        ↓
Files are stored inside WSL Ubuntu
        ↓
Git tracks the changes
        ↓
Commit saves the changes locally
        ↓
Push sends the changes to GitHub
```

Example:

```bash
git status
git add .
git commit -m "Add notes about WSL VS Code Git and GitHub"
git push
```

---

## 8. My environment

Project path inside WSL:

```bash
/home/marceloadvincula/projects/cloud-foundations-labs
```

Repository:

```text
cloud-foundations-labs
```

Main purpose:

```text
Build practical foundations in Linux, Git, GitHub, Cloud, DevOps, and AI.
```

---

## 9. Simple summary

```text
WSL = Linux inside Windows
VS Code = editor to work with files
Git = saves project history
GitHub = online place to store and show projects
```

Final idea:

```text
I study and create files in WSL Ubuntu.
I edit them with VS Code.
I save versions with Git.
I publish them on GitHub.
```

