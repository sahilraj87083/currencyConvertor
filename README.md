# 🪙 Currency Converter (React + Custom Hook)

A simple and elegant Currency Converter built with React, Tailwind CSS, and a custom hook (useCurrencyInfo) that fetches real-time exchange rates from an external API.

# 🚀 Features

- 🌍 Convert any currency to another in real-time
- 🔄 Swap currencies instantly
- 📡 Live exchange rates using a public CDN API
- 🧩 Reusable InputBox component
- 🎣 Custom React hook for API calls
- 🎨 Beautiful UI with Tailwind CSS
- ⚡ Fully responsive design


# 📂 Project Structure
```
src/
│── components/
│   └── InputBox.jsx
│   └── index.js           # Barrel export
│
│── hooks/
│   └── useCurrencyInfo.js
│
│── App.jsx
│── main.jsx

```
# 🛠️ Tech Stack

- React (Vite)
- Tailwind CSS
- Custom Hooks
- JavaScript
- Fetch API
- JSDelivr Currency API

 # 🔌 API Used

This project fetches currency exchange rates from:
```
https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies/
```

Example:
```
/usd.json
/inr.json
```

Returns all rates relative to the base currency.

# 🧩 Components

InputBox

- Reusable input component for:
- entering an amount
- selecting a currency
- disabling fields
- dynamic rendering of currency options

# 🎣 Custom Hook: useCurrencyInfo(currency)

Fetches exchange rates for the selected base currency.

Returns:
```
{
   inr: 83.12,
   eur: 0.91,
   ...
}

```
Used inside App.jsx to get conversion values dynamically.


# ▶️ How to Run Locally

## 1️⃣ Clone the repository
```
git clone <your-repo-url>
cd currency-converter
```
## 2️⃣ Install dependencies
```
npm install
```

## 3️⃣ Start dev server
```
npm run dev
```

Your app will be live on:
```
👉 http://localhost:5173/ (default Vite port)
```


# 📸 Preview
<img width="1512" height="828" alt="Screenshot 2025-11-27 at 4 21 23 PM" src="https://github.com/user-attachments/assets/6a2631e9-cd25-43fc-989e-fcd4f9e8cfff" />



