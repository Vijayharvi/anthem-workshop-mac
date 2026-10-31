# 🇮🇳 National Anthem — Git & GitHub Workshop

<p align="center">
  <strong>A Practical Demonstration of Version Control and Collaborative Software Development</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Git-Version%20Control-F05032?logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-Repository-181717?logo=github" />
  <img src="https://img.shields.io/badge/Python-3.14-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Flask-Web%20Framework-000000?logo=flask" />
  <img src="https://img.shields.io/badge/macOS-Development%20Environment-000000?logo=apple" />
  <img src="https://img.shields.io/badge/Status-Completed-success" />
</p>

---

## 📌 Project Overview

The **National Anthem — Git & GitHub Workshop** is a hands-on practical project developed to understand Git version control, GitHub repository management, and collaborative software development.

The project demonstrates how developers can work independently on different branches, exchange code changes, maintain commit history, merge contributions, resolve merge conflicts, and recover previously committed work.

The workshop was performed using macOS Terminal with Git, GitHub, Python, Flask, and HTML.

## 🎯 Project Objectives

- Understand Git and GitHub fundamentals.
- Create and manage local and remote repositories.
- Practise Git push and pull operations.
- Configure multiple developer identities.
- Create and manage feature branches.
- Track changes through meaningful commits.
- Merge independent development branches.
- Create and resolve merge conflicts.
- Develop and execute a Flask web application.
- Recover committed work using Git Reflog.

## 🛠️ Technologies & Tools

| Technology | Purpose |
|---|---|
| Git | Version control and source tracking |
| GitHub | Remote repository hosting |
| macOS Terminal | Command-line development |
| Python 3 | Backend programming |
| Flask | Web application framework |
| HTML5 | Web page structure |
| Nano | Terminal-based text editor |

## 📂 Project Structure

```text
anthem-workshop-mac/
│
├── README.md
├── anthem.txt
├── app.py
│
└── templates/
    └── index.html
```

## 🚀 Workshop Activities

### Part 0 — Developer Configuration

- Configured Git username and email.
- Set the default branch to `main`.
- Configured Git editor and credential management.
- Created three separate development clones representing Satish, Rajesh, and Ramesh.

*Note: The three developers were simulated using separate Git repositories and commit identities on macOS.*

### Part 1 — Repository Creation and Publishing

- Initialized a local Git repository.
- Created `anthem.txt`.
- Added and committed the initial anthem content.
- Created a GitHub repository.
- Connected the local repository to GitHub.
- Published the project using Git push.
- Cloned the repository into separate developer directories.

### Part 2 — Push and Pull Collaboration

- Created a Flask backend application.
- Developed the HTML template.
- Pushed application files to GitHub.
- Pulled changes into another developer's clone.
- Modified the HTML content.
- Verified developer contributions using Git history.
- Practised `git shortlog` and `git blame`.

### Part 3 — Branching, Merging and Deletion

- Created the `feature/second-stanza` branch.
- Added two separate commits.
- Pushed the feature branch to GitHub.
- Verified changes across branches.
- Merged the feature branch into `main`.
- Deleted the remote feature branch.

### Part 4 — Merge Conflict Resolution

- Created the `title-english` branch.
- Created the `title-bilingual` branch.
- Modified the same HTML heading in different ways.
- Generated an intentional merge conflict.
- Inspected Git conflict markers.
- Resolved the conflict manually.
- Created a merge commit.
- Pushed the final changes to GitHub.

### Part 5 — Undo and Recover

- Practised discarding uncommitted changes.
- Created a test commit.
- Removed the commit using `git reset --hard`.
- Located the previous commit using `git reflog`.
- Successfully recovered the committed work.

*The recovery exercise was performed locally and was not pushed to the remote repository.*

## 💻 Important Git Commands

```bash
# Initialize repository
git init -b main

# Check repository status
git status

# Add files
git add .

# Commit changes
git commit -m "Your commit message"

# Connect GitHub repository
git remote add origin REPOSITORY_URL

# Push changes
git push origin main

# Pull latest changes
git pull origin main

# Clone repository
git clone REPOSITORY_URL

# Create a feature branch
git switch -c feature/new-feature

# Switch branches
git switch main

# Merge branches
git merge feature/new-feature

# View branches
git branch -a

# View commit history
git log --oneline --graph

# View contributor history
git shortlog -sn

# View file authorship
git blame templates/index.html

# Recover previous commits
git reflog
```

## ⚙️ Installation & Execution

### 1. Clone the repository

```bash
git clone https://github.com/Vijayharvi/anthem-workshop-mac.git
```

### 2. Enter the project directory

```bash
cd anthem-workshop-mac
```

### 3. Create a Python virtual environment

```bash
python3 -m venv venv
```

### 4. Activate the environment

```bash
source venv/bin/activate
```

### 5. Install Flask

```bash
python -m pip install flask
```

### 6. Run the application

```bash
python app.py
```

### 7. Open in your browser

```text
http://127.0.0.1:5000
```

## 📚 Key Learning Outcomes

By completing this practical workshop, I gained hands-on experience in:

- Version control and source code management.
- GitHub repository creation and management.
- Collaborative development workflows.
- Branch creation and merging.
- Resolving real-world merge conflicts.
- Commit history management and recovery.
- Python Flask application development.
- macOS Terminal and command-line operations.

## 👨‍💻 Author

**VIJAYAKUMAR MAHESH HARAVI**

- GitHub: [@Vijayharvi](https://github.com/Vijayharvi)
- Repository: [anthem-workshop-mac](https://github.com/Vijayharvi/anthem-workshop-mac)

## 🔗 Project Repository

[View Source Code on GitHub](https://github.com/Vijayharvi/anthem-workshop-mac)

---

<p align="center">
  <strong>Built with ❤️ by Vijayakumar Mahesh Haravi</strong>
  <br/>
  <sub>Learn • Practise • Collaborate • Build • Grow</sub>
</p>
