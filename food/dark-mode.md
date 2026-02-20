# 🌙 Food & Drink App - Dark Mode

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-Food%20%26%20Drink-FF6B4A?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Dark%20Mode-1A1E2B?style=flat-square)]()
  [![Late Night](https://img.shields.io/badge/Late%20Night-Cravings-00A86B?style=flat-square)]()
  
  ---
  
  | [🏠 Food Home](../README.md) | [🎨 Primary](./primary-palette.md) | [💎 Luxury](./luxury-style.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 🌙 Dark Mode Palette

| Color | Hex | Original | Usage | Preview |
|-------|-----|----------|-------|---------|
| Dark Kitchen | `#1A1A1A` | #FFF9F0 | Background | ████ |
| Surface Dark | `#2A2A2A` | #FFFFFF | Cards | ████ |
| Warm Orange | `#FF8C42` | #FF6B4A | Primary | ████ |
| Muted Green | `#4A8A5A` | #00A86B | Healthy | ████ |
| Soft Brown | `#8B6B4A` | #8B5A2B | Dessert | ████ |
| Light Cream | `#F5E6D3` | #4A5568 | Text | ████ |

## 🧠 Benefits for Food Apps

- **Late-night ordering** without bright light
- **Cozy atmosphere** for browsing menus
- **Food photos pop** against dark backgrounds
- **Reduced eye strain** during midnight cravings
- **Cinematic feel** for restaurant galleries

## 💻 Implementation

```css
@media (prefers-color-scheme: dark) {
  :root {
    --background: #1A1A1A;
    --surface: #2A2A2A;
    --primary: #FF8C42;
    --healthy: #4A8A5A;
    --dessert: #8B6B4A;
    --text: #F5E6D3;
  }
}

.food-image {
  filter: brightness(0.9) contrast(1.1);
}
