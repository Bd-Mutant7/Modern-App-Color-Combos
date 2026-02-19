# 🎨 Farming App - Primary Palette

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-Farming-00A86B?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Primary-00A86B?style=flat-square)]()
  [![Growth](https://img.shields.io/badge/Growth-Natural-FFD700?style=flat-square)]()
  
  ---
  
  | [🏠 Farming Home](../README.md) | [🌙 Dark Mode](./dark-mode.md) | [💎 Luxury Style](./luxury-style.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 🎨 Color Palette

| Color Name | Hex | HSL | Usage | Preview |
|------------|-----|-----|-------|---------|
| Jade Green | `#00A86B` | `hsl(156, 100%, 33%)` | Primary brand, growth | ████ |
| Warm Earth | `#8B5A2B` | `hsl(30, 53%, 36%)` | Soil, fields, ground | ████ |
| Sky Blue | `#87CEEB` | `hsl(197, 71%, 73%)` | Weather data, sky | ████ |
| Cream | `#FFF8E7` | `hsl(40, 100%, 95%)` | Backgrounds, cards | ████ |
| Terracotta | `#E2725B` | `hsl(10, 70%, 62%)` | Alerts, drought warnings | ████ |
| Forest Green | `#228B22` | `hsl(120, 61%, 34%)` | Crops, vegetation | ████ |

## 🧠 Color Psychology

| Color | Emotion | Best Used For |
|-------|---------|---------------|
| **Jade Green** | Growth, Health | Brand, success indicators |
| **Warm Earth** | Grounding, Stability | Soil data, fields |
| **Sky Blue** | Clarity, Weather | Forecast, atmospheric data |
| **Cream** | Warmth, Approachable | Backgrounds, cards |
| **Terracotta** | Warning, Alert | Drought, critical issues |

## 💻 Implementation

```css
:root {
  --farming-primary: #00A86B;
  --farming-primary-dark: #008C56;
  --farming-soil: #8B5A2B;
  --farming-sky: #87CEEB;
  --farming-background: #FFF8E7;
  --farming-surface: #FFFFFF;
  --farming-alert: #E2725B;
  --farming-crops: #228B22;
}

.field-card {
  background: var(--farming-surface);
  border-radius: 12px;
  padding: 16px;
  border-left: 4px solid var(--farming-primary);
  box-shadow: 0 2px 8px rgba(0,0,0,0.05);
}

.soil-moisture {
  color: var(--farming-soil);
  font-weight: bold;
}

.weather-display {
  background: var(--farming-sky);
  color: #2C3E50;
  padding: 12px;
  border-radius: 8px;
}

.drought-alert {
  background: var(--farming-alert);
  color: white;
  padding: 8px 16px;
  border-radius: 20px;
  font-weight: bold;
  animation: pulse 2s infinite;
}
