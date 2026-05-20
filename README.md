# 🧮 Simple Web Calculator

A clean, minimalist web-based calculator built using vanilla HTML, CSS, and JavaScript. The application features a dark-button theme, robust error handling, and structured grid layout.

## 🚀 Features

* **Basic Operations**: Supports addition, subtraction, multiplication, and division.
* **Expression Grouping**: Includes functional parentheses `(` and `)` for complex mathematical expressions.
* **Instant Evaluation**: Computes formulas dynamically using JavaScript engine optimization.
* **Error Prevention**: Guardrails against broken expressions (e.g., `5++` or `9*`) using runtime exception safety.
* **Smart Display Alerts**: User guidance notifications if an empty calculation is attempted.
* **Responsive Layout**: Clean grid spacing utilizing a standard HTML table framework with unified button sizing.

## 📂 Project Structure

```text
├── index.html   # Markup structure and calculator button grid
├── style.css    # Layout properties, color themes, and alignment
└── script.js    # Click handlers, logic routing, and string evaluations
```

## 🛠️ Tech Stack

* **HTML5**: Structural semantic elements and table layout wrappers.
* **CSS3**: Screen center alignments via CSS Grid, border configurations, and custom color mappings.
* **JavaScript (ES6+)**: Node selection, event listeners, dynamic UI string rewriting, and safe `try...catch` math evaluations.

## 🏁 How to Run the Project

1. Clone or download this repository to your local machine.
2. Navigate to the project folder.
3. Double-click the `index.html` file to launch the calculator instantly in your default web browser.

## 🔧 Code Quality & Safety Enhancements
* Added a fixed width to the display component to prevent global wrapper layout shifts during long entries.
* Converted legacy `.substr()` string slicing to modern `.substring()` mechanics inside the backspace router.
* Fixed a text-injection bug by clearing alert notifications safely if a user attempts to type during an active alert sequence.
