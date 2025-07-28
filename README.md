# 💱 Currency Converter Web App

A modern and responsive **Currency Converter** that uses live exchange rates from the [Frankfurter API](https://www.frankfurter.app/). Built with vanilla **HTML**, **CSS**, and **JavaScript** — no frameworks required.

---


## 🚀 Features

- 🌍 Real-time exchange rates
- 🔄 Convert between 30+ global currencies
- 🔒 Input validation (prevents converting the same currency)
- 🎨 Clean, responsive, and accessible UI
- 📱 Mobile-friendly layout with CSS Grid

---

## 🧰 Tech Stack

| Technology | Usage            |
|------------|------------------|
| HTML5      | Markup structure |
| CSS3       | Styling and layout |
| JavaScript | API integration and logic |
| Frankfurter API | Currency data source |

---

## 📂 File Structure
- main
  - html files
    - index.html
  - css file
    - style.css
  - readme.md



---

## 🧠 How It Works

1. On page load, the app fetches a list of all currencies from `https://api.frankfurter.app/currencies`.
2. Two `<select>` elements are populated with the list.
3. When the **Convert** button is clicked:
   - The app fetches conversion results using:
     ```
     https://api.frankfurter.app/latest?amount=X&from=USD&to=EUR
     ```
   - The result is displayed in the output field.

---

## 🧪 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Harsh-Raj4618/currency-converter.git
   cd currency-converter
