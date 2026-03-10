# 📊 BMI Calculator Project

A clean, responsive, and functional **Body Mass Index (BMI) Calculator** built with Vanilla JavaScript, HTML5, and CSS3. This project demonstrates DOM manipulation, event handling, and real-time UI updates.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-complete-success.svg)

## 🔗 Live Demo
Check out the live application here:  
**[BMI Calculator Live Demo](https://mooraxx1.github.io/BMI-Calculator-1/)**

---

## 🚀 Features
* **Instant Calculation:** Calculates BMI immediately upon clicking the button.
* **Input Validation:** Ensures users enter valid positive numbers for height and weight.
* **Weight Classification:** Categorizes the result into Underweight, Normal, Overweight, or Obesity.
* **Modern UI:** Features a glassmorphism-inspired container with a smooth linear gradient background.
* **Responsive Design:** Optimized for both desktop and mobile viewing.

## 🛠️ Tech Stack
* **HTML5:** Semantic structure.
* **CSS3:** Flexbox layout, custom buttons, and transitions.
* **JavaScript (ES6):** Logic, mathematical formulas, and DOM interaction.

## 📐 How It Works
The app uses the standard metric formula for BMI:
$$BMI = \frac{weight (kg)}{height (m)^2}$$

The JavaScript logic then maps the resulting value to the World Health Organization (WHO) categories.

## 📁 Project Structure
```text
├── index.html   # Main structure and UI
├── style.css    # Custom styling and layout
└── index.js     # BMI calculation logic and validation
