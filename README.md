# FrontendMentor-Project

A collection of solutions for challenges from [Frontend Mentor](https://www.frontendmentor.io/) built using different frontend technologies and architectures.

This repository acts as a central hub containing multiple projects as Git submodules, where each submodule represents an individual Frontend Mentor challenge implementation.

The goal of this repository is to:

- Practice frontend development across multiple stacks
- Explore different styling approaches
- Compare implementations between frameworks
- Build reusable UI and architecture patterns
- Track learning progress over time

---

## 🚀 Tech Stacks Used

Projects inside this repository may use combinations of:

### Frameworks & Libraries
- Vanilla JavaScript
- React
- Next.js

### Styling Approaches
- CSS3
- SCSS / SASS
- Tailwind CSS

### Tooling
- Vite
- Webpack
- npm / pnpm / yarn

---

## 📁 Repository Structure

```bash
FrontendMentor-Project/
│
├── project-1/
├── project-2/
├── project-3/
└── ...
```

Each folder is a Git submodule pointing to its own standalone repository.

---

## 🔗 Clone Repository With Submodules

To clone the repository along with all submodules:

```bash
git clone --recurse-submodules <repo-url>
```

If you already cloned the repository without submodules:

```bash
git submodule update --init --recursive
```

---

## 🛠️ Running a Project

Navigate into any submodule:

```bash
cd project-folder
```

Install dependencies:

```bash
npm install
```

Start development server:

```bash
npm run dev
```

---

# 📚 Projects / Submodules

> Update this table whenever a new Frontend Mentor project is added.

| Project | Stack | Frontend Mentor Challenge | Repository |
|---|---|---|---|
| Example Project | React + Tailwind | [Challenge Link](https://www.frontendmentor.io/challenges) | [Submodule Link](./example-project) |
| Example Project 2 | Vanilla JS + CSS | [Challenge Link](https://www.frontendmentor.io/challenges) | [Submodule Link](./example-project-2) |

---

## ✅ Suggested Naming Convention

Recommended submodule naming format:

```bash
<challenge-name>-<stack>
```

Examples:

```bash
qr-code-react-tailwind
product-preview-vanilla-css
blog-preview-next-tailwind
```

---

## 🎯 Objectives

- Improve frontend development skills
- Practice responsive design
- Learn modern frontend tooling
- Experiment with multiple frameworks
- Build production-style UI implementations

---

## 📌 Notes

- Every submodule is independently runnable.
- Some projects may have multiple implementations using different stacks.
- Challenges belong to Frontend Mentor.

---

## 📜 License

This repository is for educational and portfolio purposes.  
Challenge designs are provided by Frontend Mentor.
