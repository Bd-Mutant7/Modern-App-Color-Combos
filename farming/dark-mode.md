# 🌙 Farming App - Dark Mode

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-Farming-00A86B?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Dark%20Mode-1A1E2B?style=flat-square)]()
  [![Field](https://img.shields.io/badge/Field-Optimized-00A86B?style=flat-square)]()
  
  ---
  
  | [🏠 Farming Home](../README.md) | [🎨 Primary](./primary-palette.md) | [💎 Luxury](./luxury-style.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 🌙 Dark Mode Palette

| Color | Hex | Original | Usage | Preview |
|-------|-----|----------|-------|---------|
| Dark Soil | `#2A241F` | #FFF8E7 | Background | ████ |
| Surface Dark | `#1E3A2A` | #FFFFFF | Cards | ████ |
| Moss Green | `#4A704A` | #00A86B | Primary | ████ |
| Warm Sand | `#D2B48C` | #8B5A2B | Soil data | ████ |
| Harvest Gold | `#FFD700` | #E2725B | Alerts | ████ |
| Soft Blue | `#4A7A8A` | #87CEEB | Weather | ████ |

## 🧠 Benefits for Farming Apps

- **Outdoor visibility** in bright sunlight
- **Reduced glare** during long field days
- **Battery saving** on tablets and field devices
- **Better contrast** in all lighting conditions
- **Professional look** for AgTech platforms

## 💻 Implementation

```css
@media (prefers-color-scheme: dark) {
  :root {
    --background: #2A241F;
    --surface: #1E3A2A;
    --primary: #4A704A;
    --soil: #D2B48C;
    --alert: #FFD700;
    --weather: #4A7A8A;
  }
}

.field-mode {
  background: var(--background);
  color: var(--soil);
}
