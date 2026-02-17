# TU-Sofia E-Student Mockup 🎓

This repository contains a lightweight, frontend-only mockup of the "Е-Студент" (E-Student) portal for the Technical University of Sofia (ТУ - София). It uses static HTML, inline CSS, and Vanilla JavaScript to simulate a login process and display a populated student profile.

## 🚀 Features

* **State Management via Local Storage:** The login page captures the user's First, Middle, and Last names in Cyrillic and temporarily saves them using the browser's `localStorage` to pass data between pages.
* **Dynamic Profile Generation:** The profile page retrieves the stored names to personalize the dashboard greeting.
* **Cyrillic Transliteration Engine:** Includes a custom JavaScript function that automatically maps Bulgarian Cyrillic characters to Latin equivalents. This is used to dynamically generate a formatted university email address based on the user's input.
* **Mock Student Data:** Displays a fully formatted student information table, including faculty details, group numbers, and semester status, styled to mimic the official university system.

## 🛠️ Tech Stack

* **HTML5:** For page structure and tabular layouts.
* **CSS:** Internal and inline styles for a basic, responsive UI that mirrors the original portal.
* **Vanilla JavaScript:** Handles form validation, DOM manipulation, and text transliteration. 

## 📦 How to Run

Because this project relies entirely on client-side code with no backend or database required, getting it running is incredibly simple:

1. Clone this repository to your local machine.
2. Open the login HTML file directly in any modern web browser (e.g., Chrome, Firefox, Safari).
3. Enter a First, Middle, and Last name and click **Вход** (Login).
4. You will be redirected to the profile page, where you can view the hardcoded academic data alongside your dynamically generated `.tu-sofia.bg` email address.

OR you can access it via the link in the description hosted on github pages.

## ⚠️ Disclaimer

This project is an unofficial mockup created for educational, demonstrative, or testing purposes. It is not affiliated with, maintained by, or endorsed by the Technical University of Sofia.
