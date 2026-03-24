# 🟨 JavaScript Master Notes

<p align="center">
  <img src="../img/js.svg" width="100" alt="JS Logo">
</p>

Welcome to the comprehensive guide to **JavaScript**, the programming language that powers the interactive web. This document is designed to be a one-stop reference for everything from basic syntax to advanced logic.

---

## 📑 Table of Contents
* [🌟 Introduction to JavaScript](#-introduction-to-javascript)
* [⚙️ Topic 1: Variables](#-topic-1-variables)
* [💡 Naming Conventions & Rules](#-naming-conventions--rules)
* [🛠️ Practical Example](#-practical-example)

---

## 🌟 Introduction to JavaScript
**JavaScript (JS)** is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions. While it is most well-known as the scripting language for Web pages, many non-browser environments also use it, such as **Node.js**.

### 🚀 Key Features:
* **High-Level:** Abstracts away complex machine details.
* **Multi-paradigm:** Supports object-oriented, imperative, and functional programming styles.
* **Interactivity:** Used to create dynamic content, control multimedia, and animate images.
* **Massive Ecosystem:** Works seamlessly with frameworks like **React**, **Node.js**, and **Express**.

---

## ⚙️ Topic 1: Variables

Variables are the fundamental "containers" used to store data values. In modern JavaScript (ES6+), the way you declare a variable determines its **scope** and whether its value can be **reassigned**.

### 📖 Comparison Table

| Keyword | Scope | Reassignable | Redeclarable | Recommendation |
| :--- | :--- | :--- | :--- | :--- |
| `var` | Function | ✅ Yes | ✅ Yes | ❌ Avoid (Legacy) |
| `let` | Block | ✅ Yes | ❌ No | ✅ Use for changing values |
| `const` | Block | ❌ No | ❌ No | ✅ Use by default |

---

### 1️⃣ `const` (Constant)
The `const` keyword is used for variables that **should not change**. It makes your code safer by preventing accidental overwrites.
> **Note:** You must assign a value immediately when declaring a `const`.

```javascript
const API_URL = "[https://api.lucky.com](https://api.lucky.com)";
const birthYear = 2004;

// birthYear = 2005; ❌ Error: Assignment to constant variable.
