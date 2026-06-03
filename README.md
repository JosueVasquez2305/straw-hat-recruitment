# 🏴‍☠️ Straw Hat-Recruitment Form

An interactive, responsive, and modern web form designed for pirate recruitment into the Straw Hat Crew. This project was built as part of the **freeCodeCamp Responsive Web Design** certification, utilizing advanced CSS pseudo-classes and structured HTML5 layout components.

---

## 🚀 Live Demo
You can view the live deployment of this project via GitHub Pages here:
👉 **[INSERT YOUR GITHUB PAGES LINK HERE]**

---

## 🎨 Design & Theme Concepts

The interface features a custom **Modern Dark Mode** layout inspired by the vibrant aesthetic of *One Piece* and its captain, Monkey D. Luffy. 

* **The Straw Hat Gold (`#fbc02d`):** Used for primary headers, legends, and active states to represent the iconic straw hat.
* **Luffy's Vest Red (`#e53935` / `#b71c1c`):** Applied to the main call-to-action buttons with smooth hover transitions.
* **Gear 5 Aura (`#ffffff`):** Input focus states trigger a clean, bright white glow shadow, mirroring Luffy's Gear 5 energy.

---

## 🛠️ Technical Features & CSS Architecture

This project strictly adheres to semantic HTML5 standards and implements rigorous automated testing criteria. Key styling methods include:

* **Strict Pseudo-class Order:** Organized chaining of `:focus`, `:invalid`, and `:valid` state hooks across form controls to ensure bulletproof browser evaluation.
* **Form State Validation:** Built-in constraint validation utilizing HTML5 `required` flags paired directly with native CSS attribute testing (`red` / `green` boundary responses).
* **Attribute Selectors:** Target-specific formatting applied via `input[type="radio"]` combined with adjacent sibling combinators (`+ label`) to create an interactive layout without bloated class structures.
* **Structural Selectors:** Implementation of `input:first-of-type` to dynamically isolate and style user entry fields differently.

---

## 📂 Project Structure

```text
├── index.html   # Main application markup with semantic structure
└── styles.css   # Custom stylesheet containing theme tokens and pseudo-classes.


📝 User Stories Met
 [x] Implements a centralized structural ⁠.container⁠ and standard ⁠<form>⁠ node.
 [x] Includes explicit data fields for text (⁠#name⁠) and email (⁠#email⁠).
 [x] Features a custom selection matrix (⁠#position⁠) with a built-in default disabled fallback handler.
 [x] Groups radio-button controls within a dedicated ⁠.radio-group⁠ class structure sharing a unified namespace.
 [x] Integrates text-area blocks (⁠#message⁠) alongside semantic form labels linked via unique identifiers.
 [x] Leverages interactive user feedback actions including ⁠:hover⁠, ⁠:focus⁠, and dynamic border states.
