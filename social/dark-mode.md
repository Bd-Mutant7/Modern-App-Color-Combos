# 🌙 Social App - Dark Mode

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-Social-4A90E2?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Dark%20Mode-1A1E2B?style=flat-square)]()
  [![Night](https://img.shields.io/badge/Night-Scrolling-00A86B?style=flat-square)]()
  
  ---
  
  | [🏠 Social Home](../README.md) | [🎨 Primary](./primary-palette.md) | [💎 Luxury](./luxury-style.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 🌙 Dark Mode Palette

| Color | Hex | Original | Usage | Preview |
|-------|-----|----------|-------|---------|
| Deep Space | `#1A1E2B` | #FFFFFF | Background | ████ |
| Dark Surface | `#252A3A` | #F8F9FA | Cards | ████ |
| Soft Blue | `#6A9AE5` | #4A90E2 | Links | ████ |
| Muted Orange | `#B84A3A` | #FF6B4A | Notifications | ████ |
| Dim Purple | `#4A3A7A` | #6C5CE7 | Premium | ████ |
| Light Gray | `#E0E0E0` | #2C3E50 | Text | ████ |

## 🧠 Benefits for Social Apps

- **Reduced eye strain** during night scrolling
- **Better battery life** on OLED phones
- **Increased focus** on content
- **Modern, premium feel**
- **Less distracting** for bedtime use

## 💻 Implementation

```css
@media (prefers-color-scheme: dark) {
  :root {
    --background: #1A1E2B;
    --surface: #252A3A;
    --primary: #6A9AE5;
    --notification: #B84A3A;
    --premium: #4A3A7A;
    --text: #E0E0E0;
  }
}

.night-mode .feed {
  background: var(--background);
  color: var(--text);
}
