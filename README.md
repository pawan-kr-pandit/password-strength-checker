# Password Strength Checker

A modern and responsive web application that evaluates password strength in real time using essential security rules.

This project is designed to demonstrate practical frontend development skills with a cybersecurity-focused use case. It provides instant feedback, improvement suggestions, and visual indicators to help users create stronger passwords.

---

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [How It Works](#how-it-works)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Security Rules Used](#security-rules-used)
- [Future Improvements](#future-improvements)
- [Author](#author)

---

## Overview

The Password Strength Checker analyzes user input as they type and assigns a strength level:

- **Weak**
- **Medium**
- **Strong**

It also shows:

- A visual progress bar
- Score in percentage
- Rule-by-rule validation status
- Actionable suggestions to improve password quality

---

## Key Features

- Real-time password strength analysis
- Percentage-based scoring model
- Dynamic strength meter with color feedback
- Checklist validation for required password rules
- Smart suggestions for missing security criteria
- Show/Hide password toggle
- One-click password copy using Clipboard API
- Dark/Light mode toggle
- Mobile-friendly responsive layout
- Animated background for modern UI experience

---

## Tech Stack

- **HTML5** - Semantic structure
- **CSS3** - Styling, responsive layout, animations, theme variables
- **Vanilla JavaScript (ES6+)** - Password evaluation logic and UI interactions

---

## How It Works

The application validates the password against 5 core conditions:

1. Minimum 8 characters
2. At least 1 uppercase letter
3. At least 1 lowercase letter
4. At least 1 number
5. At least 1 special character

Each valid condition increases the overall score. Based on score percentage, the app updates:

- Strength label (`Weak`, `Medium`, `Strong`)
- Progress bar width and color
- Rule checklist status
- Suggestions list

---

## Project Structure

```text
password-strength-checker-v2/
├── index.html      # Main UI markup
├── style.css       # Styling, themes, responsive design, background animation
├── script.js       # Validation logic, score calculation, interactions
└── README.md       # Project documentation
```

---

## Getting Started

### 1) Clone the repository

```bash
git clone https://github.com/pawan-kr-pandit/password-strength-checker-v2.git
```

### 2) Open the project directory

```bash
cd password-strength-checker-v2
```

### 3) Run the project

Open `index.html` directly in your browser.

No external dependencies or build tools are required.

---

## Usage

1. Enter a password in the input field.
2. Observe live score and strength indicator.
3. Check unmet rules in the suggestions section.
4. Improve password until all conditions pass.
5. Use:
   - **Show/Hide** to toggle visibility
   - **Copy** to copy password
   - **Light/Dark Mode** button to switch theme

---

## Security Rules Used

The checker follows common password hardening principles inspired by real-world security best practices:

- Length requirement
- Character diversity
- Numeric inclusion
- Special symbol inclusion

> Note: This is a frontend educational tool and does not replace full backend security enforcement policies.

---

## Future Improvements

- Add password generator for strong random passwords
- Add entropy-based strength estimation
- Detect common weak patterns (e.g., `123456`, `password`)
- Add copy-to-clipboard success toast animation
- Add multilingual support

---

## Author

**Pawan Kr. Pandit**

- GitHub: [pawan-kr-pandit](https://github.com/pawan-kr-pandit)
- LinkedIn: [pawan-kumar-pandit-651954302](https://www.linkedin.com/in/pawan-kumar-pandit-651954302)

---

If you found this project useful, consider giving it a star on GitHub.
