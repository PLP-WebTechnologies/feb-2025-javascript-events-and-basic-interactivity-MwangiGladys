# feb-2025-avasjcript-events-and-basic-interactivity

# Gladys Mwangi Interactive Contact Page

This project is a simple interactive web page that includes a contact form with form validation, a live character counter, and a dark mode toggle. The code is built with **HTML**, **CSS**, and **JavaScript**.

---

## 🔧 Features

1. **Contact Form**  
   - Users can input their **name**, **email**, and a **message**.
   - All fields are required.
   - Real-time form validation and error messages.
   - Message is limited to 200 characters.

2. **Character Counter**  
   - Displays the remaining character count as the user types into the message field.

3. **Dark Mode Toggle**  
   - A toggle switch allows users to switch between light and dark themes.

---

## 📁 File Structure

```
Gladys-Contact-Page/
│
├── index.html       # HTML structure of the page
├── style.css        # CSS for styling and themes
└── script.js        # JavaScript for form validation, character count, and theme toggle
```

---

## 📄 Code Explanation

### 1. `index.html`

- **Purpose**: Structure of the contact form and toggle button.
- **Important Tags**:
  - `<form>`: Contains inputs for name, email, and message.
  - `<div class="error">`: Displays validation messages.
  - `<div id="themeToggle">`: Clickable text to switch themes.
  - `<script src="script.js">`: Links external JavaScript file.

---

### 2. `style.css`

- **Purpose**: Styles the form and defines dark/light themes.
- **Key Sections**:
  - `.dark-mode`: Defines dark background and light text.
  - `form`: Styles form box with shadows and padding.
  - `input`, `textarea`: Full-width form controls.
  - `.error`: Red text to display validation messages.

---

### 3. `script.js`

- **Purpose**: Adds interactivity to the page.
- **Key Functions**:
  - **Form Validation**:
    - Checks if all fields are filled correctly.
    - Uses regex to validate email format.
    - Displays custom error messages.
  - **Character Counter**:
    - Updates remaining character count dynamically as user types.
  - **Theme Toggle**:
    - Adds/removes `.dark-mode` class on the `<body>` when clicked.

---

## ✅ Usage Instructions

1. Open `index.html` in a web browser.
2. Fill out the contact form and press **Submit**.
3. Try leaving a field blank to see validation in action.
4. Click **"Toggle Dark Mode"** to switch the theme.

---

## 🧠 Skills Practiced

- HTML5 form handling
- CSS3 styling and theming
- JavaScript DOM manipulation and event handling
- Basic front-end validation
>>>>>>> 4fc5cdb (completed wk 6 assignment)
