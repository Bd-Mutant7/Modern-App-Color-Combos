# 🎨 Navigation App - Primary Palette

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-Navigation-4A90E2?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Primary-00A86B?style=flat-square)]()
  [![Safety](https://img.shields.io/badge/Safety-High-FFD700?style=flat-square)]()
  
  ---
  
  | [🏠 Navigation Home](../README.md) | [🌙 Dark Mode](./dark-mode.md) | [💎 Luxury Style](./luxury-style.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 🎨 Color Palette

| Color Name | Hex | HSL | Usage | Preview |
|------------|-----|-----|-------|---------|
| Cool Blue | `#4A90E2` | `hsl(214, 82%, 62%)` | Primary route, interactive | ████ |
| Slate Gray | `#4A5568` | `hsl(218, 18%, 35%)` | Secondary roads, labels | ████ |
| Forest Green | `#2E7D32` | `hsl(123, 46%, 34%)` | Parks, nature areas | ████ |
| Sunset Orange | `#FF6B4A` | `hsl(14, 100%, 64%)` | Traffic alerts, warnings | ████ |
| Clean White | `#FFFFFF` | `hsl(0, 0%, 100%)` | Backgrounds, text | ████ |
| Deep Water | `#0A2342` | `hsl(214, 74%, 15%)` | Water bodies | ████ |

## 🧠 Color Psychology

| Color | Emotion | Best Used For |
|-------|---------|---------------|
| **Cool Blue** | Trust, Clarity | Primary routes, navigation |
| **Slate Gray** | Neutral, Informative | Secondary roads |
| **Forest Green** | Nature, Parks | Green spaces |
| **Sunset Orange** | Urgency, Alert | Traffic, hazards |
| **Deep Water** | Depth, Water | Lakes, oceans |

## 💻 Implementation

```css
:root {
  --nav-primary: #4A90E2;
  --nav-primary-dark: #3A70B0;
  --nav-secondary: #4A5568;
  --nav-park: #2E7D32;
  --nav-alert: #FF6B4A;
  --nav-alert-dark: #E04F4A;
  --nav-background: #FFFFFF;
  --nav-water: #0A2342;
}

.route-line {
  stroke: var(--nav-primary);
  stroke-width: 4px;
}

.traffic-warning {
  color: var(--nav-alert);
  font-weight: bold;
  animation: pulse 1s infinite;
}

.park-area {
  fill: var(--nav-park);
  opacity: 0.3;
}
