# $ Currency Converter

A modern and responsive Currency Converter web application built using HTML, CSS, and JavaScript. The application fetches live exchange rates from ExchangeRate API and allows users to convert between 160+ international currencies with a clean and intuitive user interface.

## 🚀 Live Demo

🔗 https://ankit-currency-converter.vercel.app/

## 📌 Features

- Real-time currency conversion
- Support for 160+ global currencies
- Currency swap functionality
- Live exchange rate retrieval using API
- Fast conversion using cached exchange rates
- Responsive design for desktop and mobile
- Loading indicators for API requests
- Input validation and error handling
- Clean and modern user interface

## 🛠️ Tech Stack

- HTML5
- CSS3
- JavaScript
- ExchangeRate API
- GitHub
- Vercel

## ⚙️ How It Works

1. User enters an amount.
2. Selects source currency.
3. Selects destination currency.
4. Application fetches exchange rates from ExchangeRate API.
5. Conversion is calculated using:

```text
Converted Amount = (Amount / Source Currency Rate) × Target Currency Rate
```

6. Converted amount is displayed instantly.

## 🧠 Key Concepts Used

- DOM Manipulation
- Event Handling
- Async/Await
- Fetch API
- API Integration
- Error Handling
- Responsive Web Design

## 📸 Preview

<img width="623" height="708" alt="image" src="https://github.com/user-attachments/assets/41f738e8-9121-4396-b8eb-99bfad308d81" />

## 🔥 Performance Optimizations

- Exchange rates are fetched only once and stored in memory.
- Subsequent conversions use cached data.
- Reduced API requests improve response time.
- Faster user experience with local calculations.

## 🚀 Future Enhancements

- Dark Mode
- Currency Flags
- Conversion History
- Hourly Exchange Rate Refresh
- Backend Integration
- Secure API Key Management
- Progressive Web App (PWA)

## 📥 Installation

Clone the repository:

```bash
git clone https://github.com/sharmaankit29/Currency-Converter.git
```

Navigate to project directory:

```bash
cd Currency-Converter
```

Open:

```text
index.html
```

in your browser.

## 👨‍💻 Author

**Ankit Sharma**

- GitHub: https://github.com/sharmaankit29

---
