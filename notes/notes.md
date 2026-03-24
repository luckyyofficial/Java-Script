# ⚙️ JavaScript Variables

<p align="center">
  <img src="../img/js.svg" width="80" alt="JS Logo">
</p>

Variables are the fundamental "containers" used to store data values. In modern JavaScript (ES6+), the way you declare a variable determines its **scope** and whether its value can be **reassigned**.

---

## 📖 Overview Table
This table summarizes the key differences between the three declaration keywords:

| Keyword | Scope | Reassignable | Redeclarable | Recommendation |
| :--- | :--- | :--- | :--- | :--- |
| `var` | Function | ✅ Yes | ✅ Yes | ❌ Avoid |
| `let` | Block | ✅ Yes | ❌ No | ✅ Use for changing values |
| `const` | Block | ❌ No | ❌ No | ✅ Use by default |

---

## 1️⃣ `const` (Constant)
The `const` keyword is used for variables that **should not be reassigned**. It is the safest choice for most variables because it prevents accidental changes.
> **Note:** You must assign a value at the time of declaration.

```javascript
const API_URL = "[https://api.example.com](https://api.example.com)";
const birthYear = 2004;

// birthYear = 2005; ❌ Error: Assignment to constant variable.
