
# 🔳 QR Code Generator – Web Application

## 📌 Project Overview

The **QR Code Generator** is a simple and interactive web application that allows users to generate a QR code instantly by entering any text or URL.

This project is built using **HTML, CSS, and JavaScript**, and it uses a free online QR Code API to generate QR images dynamically.

The application features a modern **Glassmorphism UI design**, smooth animations, and responsive layout support for mobile devices.

---

## 🎯 Objective of the Project

The main objective of this project is to:

* Practice **DOM manipulation** using JavaScript
* Understand how to integrate a **third-party API**
* Build a responsive and modern UI using **CSS3**
* Improve frontend development skills

---

## 🛠️ Technologies Used

* **HTML5** – Structure of the web page
* **CSS3** – Styling and animations
* **JavaScript (Vanilla JS)** – Functionality and logic
* **QR Code API** –
  `https://api.qrserver.com/v1/create-qr-code/`

---

## 📂 Project Structure

```
QR-Code-Generator/
│
├── index.html      → Main HTML structure
├── style.css       → Styling (Glass effect, animations, responsive design)
└── script.js       → QR generation logic
```

---

## 🧠 How the Application Works

### Step 1: User Input

The user enters any text or URL into the input field.

### Step 2: Button Click

When the user clicks **"Generate QR Code"**, the JavaScript function `generateQR()` is executed.

### Step 3: QR Code Generation

If the input field is not empty:

* The app dynamically creates a QR code using the API.
* The QR image source is updated.
* The QR container becomes visible with animation.

Example API format:

```
https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=YOUR_TEXT
```

### Step 4: Error Handling

If the input field is empty:

* A shake animation appears.
* This gives visual feedback to the user.

---

## ✨ Features

* 🔹 Instant QR code generation
* 🔹 Clean Glassmorphism design
* 🔹 Smooth hover and click animations
* 🔹 Input validation with shake effect
* 🔹 Fully responsive layout
* 🔹 Lightweight and fast

---

## 📱 Responsive Design

The application adjusts automatically for smaller screen sizes using CSS media queries.
It works smoothly on:

* Desktop
* Tablet
* Mobile devices

---

## 💻 How to Run This Project

### Option 1: Open Directly

1. Download the project files.
2. Open `index.html` in your browser.

### Option 2: Using VS Code

1. Open the project folder in VS Code.
2. Install **Live Server Extension**.
3. Right-click `index.html` → Click **Open with Live Server**.

---

## 🔮 Future Enhancements

* Add QR Code download button
* Allow user to select QR size
* Add custom color options
* Add dark/light theme toggle
* Store QR history

---
