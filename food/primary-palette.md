# 🎨 Food & Drink App - Primary Palette

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-Food%20%26%20Drink-FF6B4A?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Primary-00A86B?style=flat-square)]()
  [![Appetite](https://img.shields.io/badge/Appetite-High-FFD700?style=flat-square)]()
  
  ---
  
  | [🏠 Food Home](../README.md) | [🌙 Dark Mode](./dark-mode.md) | [💎 Luxury Style](./luxury-style.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 🎨 Color Palette

| Color Name | Hex | HSL | Usage | Preview |
|------------|-----|-----|-------|---------|
| Appetite Orange | `#FF6B4A` | `hsl(14, 100%, 64%)` | Primary CTA, brand | ████ |
| Fresh Green | `#00A86B` | `hsl(156, 100%, 33%)` | Healthy options, veg | ████ |
| Creamy White | `#FFF9F0` | `hsl(40, 100%, 97%)` | Backgrounds, cards | ████ |
| Chocolate Brown | `#8B5A2B` | `hsl(30, 53%, 36%)` | Desserts, coffee | ████ |
| Tomato Red | `#FF6347` | `hsl(9, 100%, 64%)` | Hot, spicy alerts | ████ |
| Slate Gray | `#4A5568` | `hsl(218, 18%, 35%)` | Menu text | ████ |

## 🧠 Color Psychology

| Color | Emotion | Best Used For |
|-------|---------|---------------|
| **Appetite Orange** | Hunger, Urgency | Order buttons, deals |
| **Fresh Green** | Healthy, Natural | Veg options, salads |
| **Creamy White** | Clean, Appetizing | Backgrounds, cards |
| **Chocolate Brown** | Rich, Indulgent | Desserts, coffee |
| **Tomato Red** | Hot, Spicy | Spicy indicators |

## 💻 Implementation

```css
:root {
  --food-primary: #FF6B4A;
  --food-primary-dark: #E04F4A;
  --food-healthy: #00A86B;
  --food-background: #FFF9F0;
  --food-surface: #FFFFFF;
  --food-dessert: #8B5A2B;
  --food-spicy: #FF6347;
  --food-text: #4A5568;
}

.menu-item {
  background: white;
  border-radius: 12px;
  padding: 16px;
  margin: 8px 0;
  box-shadow: 0 2px 8px rgba(0,0,0,0.05);
  border-left: 4px solid var(--food-primary);
}

.spicy-badge {
  background: var(--food-spicy);
  color: white;
  padding: 2px 8px;
  border-radius: 12px;
  font-size: 12px;
  font-weight: bold;
}

.healthy-badge {
  background: var(--food-healthy);
  color: white;
  padding: 2px 8px;
  border-radius: 12px;
  font-size: 12px;
}

.price {
  color: var(--food-primary);
  font-weight: bold;
  font-size: 18px;
}
