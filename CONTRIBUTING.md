<p align="center">
  <strong>Contributing to Smart Dashboard</strong>
  <br />
  <em>Guide for developers who want to help improve the project</em>
</p>

---

## Overview

Thanks for your interest in contributing to **Smart Dashboard**!  
This guide will help you set up your environment, understand the codebase, and follow best practices for contributing.

Smart Dashboard is built with **React**, **TypeScript**, **TailwindCSS**, **Shadcn-ui**, and **Zustand**. We aim to keep the project modular, scalable, and easy to extend.

---

## Getting Started

### Fork & Clone

1. **Fork the repository**  
   Click the **Fork** button on GitHub to create your own copy.

2. **Clone your fork**
```bash
git clone https://github.com/YOUR_USERNAME/smart-dashboard.git

3. **Navigate into the project**
```bash
cd smart-dashboard

4. **Install dependencies**
```bash
npm install

5. **Run the development server**
```bash
npm run dev
The app will be available at http://localhost:3000
----------------------------------------------------------
Contribution Flow
1.Always create a new branch before working on changes:
```bash
git checkout -b feature/my-new-feature
2.Commit with clear messages using conventional commits:
```bash
git commit -m "feat: add new analytics widget"
3.Push your branch:
```bash
git push origin feature/my-new-feature
4.Open a Pull Request (PR) on GitHub:
. Describe your changes clearly
. Include screenshots for UI changes
. Reference any related issues
----------------------------------------------------------
Areas to Contribute
| Area                | Folder / Path                    | Notes                                          |
| ------------------- | -------------------------------- | ---------------------------------------------- |
| Dashboard Pages     | `src/pages/dashboard/`           | Add new widgets, cards, or analytics screens   |
| Reusable Components | `src/components/`                | Create or improve UI components                |
| Hooks & Store       | `src/hooks/` / `src/store/`      | Add custom logic, Zustand stores, or utilities |
| Styles & Themes     | `src/styles/`                    | Add new Tailwind presets or update themes      |
| Documentation       | `/README.md`, `/CONTRIBUTING.md` | Improve clarity, examples, or add guides       |
---------------------------------------------------------------
Guidelines
. Write TypeScript types whenever possible
. Keep components modular and reusable
. Follow ESLint + Prettier rules
. Use Tailwind v4 and Shadcn-ui conventions
. Ensure accessibility (ARIA, keyboard navigation)
. Avoid unnecessary dependencies
. Test your changes thoroughly
-------------------------------------------------------------------
Reporting Bugs
. Include clear steps to reproduce the issue
. Describe expected vs actual behavior
. Add screenshots or videos if possible
----------------------------------------------------------------------
Suggesting Features
. Open an issue before implementing new features
. Explain the purpose, use case, and benefits of your feature
----------------------------------------------------------------------
<p align="center"> Your contributions make Smart Dashboard better for everyone! 🚀 <strong>Happy Coding!</strong> </p> ```



