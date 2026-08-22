# NORDBLICK – Kiel Weather, Traffic & News

**NORDBLICK** is a compact information dashboard for **Kiel, Schleswig-Holstein, Germany**.

The website brings important local and general information together in one place — including current weather, forecasts, public transport information, local news, national news, and Euro exchange rates.

## 🌐 Live Website

**https://www.nordblick-weatherboard.de**

## 📌 About

NORDBLICK was created as a simple and easy-to-use information screen for Kiel and northern Germany.

Instead of checking multiple websites, users can get a quick overview of important information from different sources on a single page.

## ✨ Features

### 🌦️ Current Weather

- Current weather conditions for Kiel
- Feels-like temperature
- Humidity
- Wind speed
- Sunrise and sunset times
- Chance of rain
- Daily high temperature
- Weather information and updates

### 📅 7-Day Forecast

The dashboard provides a **7-day weather forecast** for Kiel, including daily weather information.

Users can switch between:

- °C / km/h
- °F / mph

### 🚌 KVG Live

NORDBLICK includes live public transport information for Kiel.

The dashboard currently provides a live display for:

**Stockholmstraße**

The live transport display is provided through **Flott-Live**.

### 📰 Kiel News

The website displays current news from **Kiel News**, allowing users to quickly see local headlines without leaving the dashboard.

### 🇩🇪 Tagesschau

NORDBLICK also includes national news from **Tagesschau.de** for a broader overview of current events in Germany.

### 💱 Euro Exchange Rates

The dashboard provides current exchange-rate information based on the Euro (EUR).

This makes it possible to quickly check currency rates without opening a separate exchange-rate website.

## 🔌 Data Sources

NORDBLICK combines information from several external services:

| Information | Source |
|---|---|
| Weather | Open-Meteo |
| Exchange Rates | Frankfurter API |
| Kiel News | Kiel News RSS |
| German News | Tagesschau API |
| Public Transport | Flott-Live |

The website clearly identifies these sources on the dashboard. citeturn0view0

## 🛠️ Technology

NORDBLICK is designed as a lightweight web dashboard and uses web technologies to retrieve and display information from external services.

### Main technologies

- HTML5
- CSS3
- JavaScript
- REST APIs
- RSS feeds
- Responsive web design

## 📂 Project Structure

```text
.
├── index.html
├── CNAME
└── README.md
```

### `index.html`

The main webpage containing the NORDBLICK dashboard.

### `CNAME`

Contains the custom domain configuration for:

`www.nordblick-weatherboard.de`

### `README.md`

Project documentation and information about NORDBLICK.

## 🚀 Running Locally

To run the project locally, clone the repository:

```bash
git clone YOUR-REPOSITORY-URL
```

Then open the project directory:

```bash
cd Nordblick-Kiel-Wetter-Nachrichten
```

Open `index.html` in a modern web browser.

Alternatively, you can use a local development server such as VS Code's **Live Server** extension.

## 🌍 Deployment

The project is hosted using **GitHub Pages** with a custom domain.

Live website:

**https://www.nordblick-weatherboard.de**

## 🔄 External Data

Because NORDBLICK relies on external APIs, RSS feeds, and live services, some information may occasionally be unavailable or delayed.

The availability and accuracy of external data depend on the respective service providers.

## 🎯 Project Goal

The goal of NORDBLICK is to create a **simple, fast, and useful information dashboard for Kiel**.

The project brings together:

- Weather
- Forecasts
- Public transport
- Local news
- National news
- Currency information

into one compact interface.

## 📍 Location

**Kiel, Schleswig-Holstein, Germany**

NORDBLICK focuses primarily on Kiel while also providing selected information relevant to northern Germany and Germany as a whole.

## 📄 License

This project is provided for personal and educational purposes.

Third-party services, APIs, news feeds, and data remain subject to their respective terms and licenses.

## 🙏 Data Providers

Special thanks to the services providing the data used by NORDBLICK:

- [Open-Meteo](https://open-meteo.com/) – Weather data
- [Frankfurter](https://www.frankfurter.app/) – Exchange-rate data
- [Kiel News](https://www.kn-online.de/) – Local news
- [Tagesschau](https://www.tagesschau.de/) – German news
- [Flott-Live](https://kiel.flott-live.de/) – Live transport information

---

**NORDBLICK**  
*Kiel · Weather · Traffic · News*
