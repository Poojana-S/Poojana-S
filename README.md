<!--
╔══════════════════════════════════════════════════════════════════════════════╗
║   POOJANA S — GitHub Profile README                                        ║
║   © 2025 Poojana S. All rights reserved.                                   ║
╚══════════════════════════════════════════════════════════════════════════════╝
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=6366f1&height=280&section=header&text=Poojana%20S&fontSize=72&fontColor=ffffff&fontAlignY=42&desc=Full%20Stack%20Developer%20%7C%20DevOps%20Enthusiast%20%7C%20CSE%202027&descSize=16&descAlignY=60&descColor=c7d2fe&animation=fadeIn&stroke=0&strokeWidth=0" width="100%" alt="Poojana S" />

</div>

<br/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=6366F1&center=true&vCenter=true&width=700&lines=Full+Stack+Dev+%7C+MERN+Stack+Builder.;DevOps+%26+Cloud+with+AWS+%2B+Jenkins+%2B+Docker.;Department+Topper+%7C+Project+Expo+Winner.;Automating+Infra+with+Ansible+%26+Terraform.;LeetCode+Rating+1438+%7C+Problem+Solver.)](https://git.io/typing-svg)

</div>

<br/>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%40poojanas-6366f1?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=312e81)](https://www.linkedin.com/in/poojanas)&nbsp;
[![LeetCode](https://img.shields.io/badge/LeetCode-Rating%201438-6366f1?style=for-the-badge&logo=leetcode&logoColor=white&labelColor=312e81)](https://leetcode.com/)&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-%40poojanas-6366f1?style=for-the-badge&logo=github&logoColor=white&labelColor=312e81)](https://github.com/)&nbsp;
[![Email](https://img.shields.io/badge/Gmail-poojanas222-6366f1?style=for-the-badge&logo=gmail&logoColor=white&labelColor=312e81)](mailto:poojanas222@gmail.com)

</div>

---

<br/>

## ◈ &nbsp;Who I Am

<img align="right" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs?username=poojanas&layout=compact&theme=transparent&title_color=6366f1&text_color=cbd5e1&bg_color=0f172a&border_color=312e81&border_radius=10&langs_count=7&hide=html" height="140" alt="Top Languages" />

I'm a third-year Computer Science student at Sri Eshwar College of Engineering with a 8.94 GPA, building at the intersection of full-stack development and DevOps engineering.

The problems I find most interesting sit at the infrastructure layer — how a CI/CD pipeline reduces deployment risk, why Ansible playbooks beat manual SSH sessions for repeatability, where containerization boundaries belong when you're scaling a Node.js service. I don't just learn these things from documentation; I build them, break them, and wire them into working systems.

Department Topper. Project Expo winner. These aren't just resume lines — they reflect a habit of finishing things properly.

<br clear="right"/>

---

<br/>

## ◈ &nbsp;Tech Stack

```
Languages    →   C++ · C · Java (Basics) · HTML · CSS · JavaScript
Frontend     →   React.js · HTML5 · CSS3
Backend      →   Node.js · Express.js · REST APIs
Databases    →   MongoDB · SQL
Cloud        →   AWS EC2 · AWS S3 · AWS IAM · AWS SNS
DevOps       →   Jenkins · Docker · Kubernetes · Ansible · Terraform · SonarQube
Tools        →   Git · GitHub · Postman · PM2
Core CS      →   OS · CN · DBMS · OOP · DSA
```

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-6366f1?style=flat-square&logo=javascript&logoColor=white)
![React](https://img.shields.io/badge/React-6366f1?style=flat-square&logo=react&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-6366f1?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-6366f1?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-6366f1?style=flat-square&logo=mongodb&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-6366f1?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-6366f1?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-6366f1?style=flat-square&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-6366f1?style=flat-square&logo=jenkins&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-6366f1?style=flat-square&logo=ansible&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-6366f1?style=flat-square&logo=terraform&logoColor=white)
![Git](https://img.shields.io/badge/Git-6366f1?style=flat-square&logo=git&logoColor=white)

</div>

---

<br/>

## ◈ &nbsp;Featured Work

<br/>

> [!NOTE]
>
> ### 🔁 &nbsp;CI/CD Pipeline — Jenkins + AWS EC2
>
> _Automated delivery from commit to production. No manual steps, no surprises._

The goal was a repeatable, observable delivery pipeline for a React application — one where every push runs through quality gates before anything touches production. Jenkins orchestrates the workflow. SonarQube blocks bad code. Terraform provisions the infrastructure. EC2 hosts the result.

<br/>

**Pipeline at a glance:**

```
GitHub Push  →  Jenkins Trigger  →  SonarQube Quality Gate
           →  Terraform: Provision AWS EC2
           →  Deploy Production Build  →  Application Live
```

> Code that doesn't pass quality checks doesn't ship. The pipeline enforces this without anyone needing to remember to check.

<br/>

**Tech Stack:** `Jenkins` &nbsp;·&nbsp; `Terraform` &nbsp;·&nbsp; `AWS EC2` &nbsp;·&nbsp; `SonarQube` &nbsp;·&nbsp; `React`

<div align="center">

[![→ View Repository](https://img.shields.io/badge/%E2%86%92%20CI%2FCD%20Pipeline%20Repository-6366f1?style=for-the-badge&logo=github&logoColor=white)](https://github.com/)

</div>

<br/>

---

### 🤖 &nbsp;Node.js Deployment Automation — Ansible

> [!IMPORTANT]
> **Infrastructure automation** — zero-touch deployment to AWS EC2

Manual deployments are error-prone and hard to reproduce. This project replaces them with an Ansible playbook that handles everything: pulling code from GitHub, installing dependencies, configuring the environment, and keeping the process alive with PM2. AWS security groups are configured as part of the same run.

> [!TIP]
> **Why PM2?** — Node.js processes die. PM2 restarts them, keeps logs, and survives reboots. Combining it with Ansible means the deployment is not just automated — it's also durable. One command from any control node, and the app is running and supervised on EC2.

<br/>

**Tech Stack:** `Ansible` &nbsp;·&nbsp; `Node.js` &nbsp;·&nbsp; `AWS EC2` &nbsp;·&nbsp; `PM2` &nbsp;·&nbsp; `GitHub`

<div align="center">

[![→ View Repository](https://img.shields.io/badge/%E2%86%92%20Ansible%20Deployment%20Repository-6366f1?style=for-the-badge&logo=github&logoColor=white)](https://github.com/)

</div>

<br/>

---

### 📝 &nbsp;BlogVerse — Full Stack Blog Application

> [!IMPORTANT]
> **MERN stack blog platform** — authentication, roles, and a real content workflow

BlogVerse is a complete blog application: users can sign up, create posts, and manage content — all behind a secure authentication layer with role-based access control. The backend handles post management and auth. The frontend is responsive and built with React. MongoDB stores everything.

> [!TIP]
> **Role-based access control** — not every user can do everything. Authors manage their own posts. Admins can manage everything. The permission model is enforced on the backend, not just hidden in the UI — a distinction that actually matters.

<br/>

**Tech Stack:** `React.js` &nbsp;·&nbsp; `Node.js` &nbsp;·&nbsp; `Express.js` &nbsp;·&nbsp; `MongoDB`

<div align="center">

[![→ View Repository](https://img.shields.io/badge/%E2%86%92%20BlogVerse%20Repository-6366f1?style=for-the-badge&logo=github&logoColor=white)](https://github.com/)

</div>

---

<br/>

## ◈ &nbsp;GitHub Activity

<br/>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=poojanas&bg_color=0f172a&color=cbd5e1&line=6366f1&point=818cf8&area=true&area_color=312e81&hide_border=false&border_color=312e81&radius=8" width="96%" alt="Contribution Graph" />

</div>

---

<br/>

## ◈ &nbsp;Internship Experience

> [!NOTE]
>
> ### 🏢 &nbsp;RAMPeX Academy &nbsp;·&nbsp; _DevOps & SRE Intern — 2024_

Designed CI/CD workflows, automated code quality validation through SonarQube, and applied containerization and orchestration using Docker and Kubernetes. This is where reading about DevOps became doing DevOps — the difference matters.

<br/>

> [!NOTE]
>
> ### 🏢 &nbsp;Consensus Academy &nbsp;·&nbsp; _MERN Stack Intern — 2024_

Gained hands-on experience building, testing, and deploying responsive full-stack web applications with the MERN stack. Extending an existing codebase responsibly — without breaking things, without making a mess — is a different skill from greenfield development. This is where I learned it.

---

<br/>

## ◈ &nbsp;Achievements

> [!TIP]
> **🏆 Department Topper — CSE 2026**
>
> Highest academic standing in the department.

<br/>

> [!TIP]
> **🥇 1st Place — Project Expo, Sri Eshwar College of Engineering 2025**
>
> Best project among all entries at the college-level expo.

<br/>

> [!TIP]
> **🥈 2nd Place — Fresh-a-thon, Sri Eshwar College of Engineering 2024**

<br/>

> [!TIP]
> **🥉 3rd Place — CodeFiesta C Buildathon, Sri Eshwar College of Engineering 2024**

---

<br/>

## ◈ &nbsp;Certifications

```
AWS Cloud Practitioner          │  Amazon Web Services  │  2026
AWS Academy Graduate            │  Amazon Web Services  │  2025
Networking Basics               │  Cisco                │  2025
SQL (Basics)                    │  HackerRank           │  2025
JavaScript Basics Bootcamp      │  ─                    │  ─
```

---

<br/>

## ◈ &nbsp;Coding Profiles

> [!NOTE]
> **LeetCode** — Max Rating: **1438** &nbsp;|&nbsp; Problems Solved: **77** &nbsp;|&nbsp; Global Rank: 868,265

Consistent problem solving, not just a solved count. The rating reflects depth across data structures and algorithm patterns.

<div align="center">

[![LeetCode Profile](https://img.shields.io/badge/LeetCode-Rating%201438-6366f1?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/)

</div>

---

<br/>

## ◈ &nbsp;Let's Connect

Cloud infrastructure, DevOps pipelines, full-stack engineering — these are the problems I'm spending my time on. If you're building something in this space or want to collaborate, I'd love to hear from you.

<div align="center">

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-6366f1?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/poojanas)&nbsp;
[![Email](https://img.shields.io/badge/Gmail-6366f1?style=for-the-badge&logo=gmail&logoColor=white)](mailto:poojanas222@gmail.com)&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-6366f1?style=for-the-badge&logo=github&logoColor=white)](https://github.com/)&nbsp;
[![LeetCode](https://img.shields.io/badge/LeetCode-6366f1?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=6366f1&height=130&section=footer&animation=fadeIn" width="100%" alt="footer" />

<sub>Written and designed by Poojana S &nbsp;·&nbsp; © 2025 All rights reserved</sub>

</div>
