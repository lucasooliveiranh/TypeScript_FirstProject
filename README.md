# 🚀 My First TypeScript Repository

Welcome to my first TypeScript project! This repository contains my code, exercises, and learnings as I transition from JavaScript to TypeScript.

---

## 📌 Reference & Resources

This project and my learnings are based on the full tutorial:
* 🎬 **Video Tutorial:** [TypeScript Full Course - From Beginner to Advanced](https://www.youtube.com/watch?v=iJkaAJUzeWQ) by Tech With Tim

---

## 💡 Key Learnings & Concepts

### 1. Dynamic vs. Static Typing

| Feature | Dynamic Typing (e.g., JavaScript) | Static Typing (e.g., TypeScript) |
| :--- | :--- | :--- |
| **Type Definition** | Types are determined dynamically at **runtime**. | Types are declared and checked at **compile-time**. |
| **Variable Flexibility** | Variables can hold values of any type and change over time. | Once defined, a variable's type **cannot change**. |
| **Error Catching** | Type-related errors appear during code execution (runtime errors). | Errors are caught **early** before the code runs (compile-time errors). |

---

### 2. JavaScript vs. TypeScript

* **JavaScript:** A dynamically typed, interpreted language widely used for web development.
* **TypeScript:** A **superset of JavaScript** that adds static typing and advanced type-checking features on top of standard JS syntax.

> 💡 *Note:* Browsers and Node.js do not execute TypeScript directly. TypeScript code is compiled/transpiled into standard JavaScript (`.js`) using the TypeScript compiler (`tsc`) before running.

---

## ⚙️ Getting Started

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/lucasooliveiranh/TypeScript_FirstProject.git](https://github.com/lucasooliveiranh/TypeScript_FirstProject.git)
   cd TypeScript_FirstProject
   ```

2. **Initialize Node.js and install TypeScript as a dev dependency:**
   ```bash
   npm init -y
   npm install typescript --save-dev
   ```

3. **Initialize the TypeScript Configuration file (`tsconfig.json`):**
   ```bash
   npx tsc --init
   ```

4. **Compile TypeScript to JavaScript:**
   ```bash
   npx tsc
   ```

---

## 🛠️ Tech Stack
* **Language:** TypeScript
* **Runtime:** Node.js
* **Compiler:** `tsc` (TypeScript Compiler)