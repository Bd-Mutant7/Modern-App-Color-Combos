# 🎨 Travel App - Primary Palette

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-Travel-4A90E2?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Primary-00A86B?style=flat-square)]()
  [![Adventure](https://img.shields.io/badge/Adventure-Ready-FFD700?style=flat-square)]()
  
  ---
  
  | [🏠 Travel Home](../README.md) | [🌙 Dark Mode](./dark-mode.md) | [💎 Luxury Style](./luxury-style.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 🎨 Color Palette

| Color Name | Hex | HSL | Usage | Preview |
|------------|-----|-----|-------|---------|
| Ocean Blue | `#4A90E2` | `hsl(214, 82%, 62%)` | Primary brand, trust | ████ |
| Sunset Orange | `#FF6B4A` | `hsl(14, 100%, 64%)` | Deals, CTAs | ████ |
| Tropical Green | `#00A86B` | `hsl(156, 100%, 33%)` | Eco-travel, nature | ████ |
| Sand Beige | `#F5E6D3` | `hsl(30, 55%, 89%)` | Backgrounds, warmth | ████ |
| Deep Navy | `#0A2342` | `hsl(214, 74%, 15%)` | Text, night sky | ████ |
| Coral Reef | `#FF7F6B` | `hsl(8, 100%, 71%)` | Highlights, alerts | ████ |

## 🧠 Color Psychology

| Color | Emotion | Best Used For |
|-------|---------|---------------|
| **Ocean Blue** | Trust, Calm | Navigation, booking |
| **Sunset Orange** | Energy, Deals | Discounts, promotions |
| **Tropical Green** | Nature, Eco | Sustainable travel |
| **Sand Beige** | Warmth, Comfort | Cards, backgrounds |
| **Deep Navy** | Night, Mystery | Dark mode, text |

## 💻 Implementation

```css
:root {
  --travel-primary: #4A90E2;
  --travel-primary-dark: #3A70B0;
  --travel-accent: #FF6B4A;
  --travel-eco: #00A86B;
  --travel-background: #F5E6D3;
  --travel-surface: #FFFFFF;
  --travel-text: #0A2342;
  --travel-highlight: #FF7F6B;
}

.destination-card {
  background: white;
  border-radius: 16px;
  overflow: hidden;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  position: relative;
}

.price-tag {
  background: var(--travel-accent);
  color: white;
  padding: 4px 12px;
  border-radius: 20px;
  font-weight: bold;
  position: absolute;
  top: 12px;
  right: 12px;
}

.eco-badge {
  background: var(--travel-eco);
  color: white;
  padding: 2px 8px;
  border-radius: 12px;
  font-size: 12px;
}
