# Currency Converter

A simple, responsive web app to convert between global currencies using live exchange rates.

## Features

- Convert between 150+ world currencies
- Live exchange rates via [ExchangeRate-API](https://www.exchangerate-api.com/)
- Auto-updating country flags for selected currencies
- Default conversion loads automatically on page open

## Tech Stack

- HTML, CSS, JavaScript (Vanilla)
- [ExchangeRate-API](https://www.exchangerate-api.com/) for live rates
- [FlagsAPI](https://flagsapi.com/) for country flag images
- [Font Awesome](https://fontawesome.com/) for icons

## How to Use

1. Clone or download the repository
2. Open `index.html` in your browser
3. Enter an amount, select the source and target currencies, and click **Get Exchange Rate**

> No build tools or installations needed — runs directly in the browser.

## File Structure
├── index.html     # App layout and structure
├── style.css      # Styling
├── script.js      # Logic, API calls, flag updates
└── codes.js       # Currency-to-country code mapping

## API

Uses the free tier of ExchangeRate-API:
GET https://api.exchangerate-api.com/v4/latest/{currency}
