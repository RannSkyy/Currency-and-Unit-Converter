# OmniConvert – Universal Converter & Live Currency Exchange

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-CDN-38BDF8?logo=tailwindcss)
![Responsive](https://img.shields.io/badge/Responsive-Mobile--First-success)
![License](https://img.shields.io/badge/License-MIT-green)

## Overview

OmniConvert is a modern client-side web application that combines real-time currency exchange and universal unit conversion in one fast, intuitive, and responsive interface. It supports live exchange rates, offline caching, and accurate conversions across multiple measurement categories without requiring a backend server.

---

## Features

### Live Currency Converter

- Real-time exchange rates from ExchangeRate API
- Supports 160+ world currencies
- Instant currency conversion
- Smart currency search
- Animated currency swap
- Popular exchange rate dashboard
- Automatic exchange rate updates
- Offline fallback rates
- 12-hour local cache
- No API key required

### Universal Unit Converter

Convert between multiple categories:

#### Length
- Meter
- Kilometer
- Centimeter
- Millimeter
- Mile
- Yard
- Foot
- Inch

#### Mass
- Kilogram
- Gram
- Milligram
- Metric Ton
- Pound
- Ounce

#### Temperature
- Celsius
- Fahrenheit
- Kelvin

#### Volume
- Liter
- Milliliter
- Cubic Meter
- US Gallon
- US Fluid Ounce

### Multi-Unit Breakdown

- Displays conversions for all units in the selected category
- Automatic updates while typing
- Clean information grid

### User Experience

- Modern dark interface
- Mobile-first responsive layout
- Smooth tab switching
- Fast calculations
- One-click copy result
- Toast notifications
- API status indicator

---

## Tech Stack

- HTML5
- Vanilla JavaScript (ES6+)
- Tailwind CSS (CDN)
- Lucide Icons
- Inter Font
- JetBrains Mono
- ExchangeRate API
- Browser Local Storage

---

## API

Exchange rates are retrieved from:

```
https://open.er-api.com/v6/latest/USD
```

Features:

- Live exchange rates
- Free endpoint
- No API key required
- Automatic cache fallback

---

## Offline Support

OmniConvert continues working even when an internet connection is unavailable.

Features include:

- 12-hour exchange rate cache
- Automatic fallback to cached data
- Built-in static exchange rates
- Seamless offline experience

---

## Data Persistence

The application stores user data locally using Local Storage, including:

- Cached exchange rates
- Last update timestamp
- User preferences

---

## Error Handling

- Input sanitization
- Invalid value prevention
- Floating-point precision handling
- API failure fallback
- Network error recovery
- User-friendly notifications

---

## Responsive Design

Optimized for:

- Mobile
- Tablet
- Laptop
- Desktop

---

## Project Structure

```text
project/
├── index.html
├── css/
├── js/
│   ├── api.js
│   ├── currency.js
│   ├── converter.js
│   ├── storage.js
│   ├── ui.js
│   └── app.js
├── assets/
└── icons/
```

---

## Installation

```bash
git clone https://github.com/yourusername/omniconvert.git

cd omniconvert
```

Open `index.html` in your browser, or use a local development server.

---

## Highlights

- Real-time currency exchange
- 160+ supported currencies
- Universal unit converter
- Length, Mass, Temperature, and Volume conversions
- Smart search and currency swap
- Multi-unit breakdown grid
- Offline support
- Local cache system
- One-click copy results
- Responsive dark UI
- No backend required
- No API key required

---

## License

This project is licensed under the MIT License.
