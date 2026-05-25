# CodeAlpha Tasks

This repository contains the projects and tasks completed during my **CodeAlpha Web Development Internship**. 

---

## Task 1: Web-Based Age Calculator

A sleek, responsive, and precision-driven web application that calculates a user's exact age down to the day, along with the total cumulative days they have lived. 

### Key Features
* **Dynamic Calculations:** Computes chronological age in exact years, months, and days using the native JavaScript `Date` object.
* **Intelligent Edge-Case Validation:** * Automatically catches invalid dates per month (e.g., preventing entering February 31st).
  * Accounts for leap years dynamically.
  * Blocks future dates from being processed.
* **Clean & Modern UI:** Designed with a vibrant CSS linear gradient background, responsive CSS grid layouts, soft interactive form focus rings, and smooth entrance animations.
* **Non-Intrusive Error Handling:** Validation errors only appear dynamically via JavaScript as the user interacts with the application, ensuring a clean state on page load.

### Technologies Used
* **HTML5:** Semantic document structure for forms, inputs, and numeric constraints.
* **CSS3:** Custom linear gradients, responsive typography, interactive focus pseudoclasses, flexbox/grid layout systems, and `@keyframes` slide-in animations.
* **JavaScript (ES6+):** Form manipulation, input listeners, and algorithmic date manipulation.

---

## Project Structure
```text
├── index.html      # Semantic HTML structure and layout
├── styles.css      # Core styling, layouts, animations, and responsive breakpoints
└── script.js      # Form validation engines and core calculation logic

