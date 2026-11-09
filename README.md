# OmniConvert — Live Currency & Universal Unit Converter

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v3-38BDF8?logo=tailwindcss)
![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

## Overview

OmniConvert is a lightweight converter application available as both a web app and a Python CLI tool. It provides real-time currency conversion using a public exchange rate API alongside a comprehensive collection of universal unit converters, all within a fast, responsive, and modern interface.

The project is designed with a backend-free architecture, offline fallback support, and smart local caching to deliver a smooth and reliable user experience.

---

## Features

### Live Currency Converter

- Real-time exchange rates
- Public API integration (no API key required)
- Smart local caching
- Offline fallback support
- Automatic currency search
- Currency swap
- Two-way conversion
- Fast calculations

### Universal Unit Converter

#### Length
- Kilometer (km)
- Meter (m)
- Centimeter (cm)
- Millimeter (mm)
- Mile (mi)
- Foot (ft)

#### Mass
- Kilogram (kg)
- Gram (g)
- Milligram (mg)
- Pound (lb)
- Ounce (oz)

#### Temperature
- Celsius (°C)
- Fahrenheit (°F)
- Kelvin (K)

#### Volume
- Liter (L)
- Milliliter (mL)
- Gallon (gal)
- Cup

### User Experience

- Modern dark theme
- Responsive design
- Copy-to-clipboard
- Fast interface
- Mobile-friendly
- Keyboard-friendly
- Smooth interactions

---

## Tech Stack

### Frontend

- HTML5
- Tailwind CSS v3
- Vanilla JavaScript (ES6+)
- Fetch API
- Local Storage
- Lucide Icons
- Google Fonts

### CLI Version

- Python 3.x
- Requests

---

## Project Structure

```text
Currency-Unit-Converter/
│
├── index.html
├── main.py
├── README.md
└── LICENSE
```

---

## Installation

### Web Version

```bash
git clone https://github.com/yourusername/Currency-Unit-Converter.git

cd Currency-Unit-Converter
```

Open `index.html` in your browser or use Live Server.

---

### Python CLI

Install the required dependency:

```bash
pip install requests
```

Run the application:

```bash
python main.py
```

---

## API

The currency converter uses the public exchange rate service:

- Open Exchange Rates API (`open.er-api.com`)

No API key is required.

---

## Performance

- Smart Local Storage caching
- Reduced network requests
- Instant loading
- Offline fallback
- Lightweight architecture

---

## Error Handling

- Input validation
- Network timeout handling
- API error handling
- Offline fallback
- Invalid number protection
- Safe temperature calculations
- Divide-by-zero prevention

---

## Responsive Design

Optimized for:

- Mobile
- Tablet
- Laptop
- Desktop

---

## Main Highlights

- Real-time currency conversion
- Universal unit converter
- Offline fallback support
- Smart caching
- Responsive UI
- Dark mode design
- Copy-to-clipboard
- Lightweight architecture
- Web + Python CLI
- No backend required

---

## License

This project is licensed under the MIT License.
