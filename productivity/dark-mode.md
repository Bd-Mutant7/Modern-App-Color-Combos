# 🌙 Productivity App - Dark Mode

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-Productivity-4A5568?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Dark%20Mode-1A1E2B?style=flat-square)]()
  [![Deep Work](https://img.shields.io/badge/Deep%20Work-Optimized-00A86B?style=flat-square)]()
  
  ---
  
  | [🏠 Productivity Home](../README.md) | [🎨 Primary](./primary-palette.md) | [💎 Luxury](./luxury-style.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 🌙 Dark Mode Palette

| Color | Hex | Original | Usage | Preview |
|-------|-----|----------|-------|---------|
| Dark Slate | `#1A1E2B` | #F8F9FA | Background | ████ |
| Surface Dark | `#252A3A` | #FFFFFF | Cards | ████ |
| Soft Gray | `#A0A0A0` | #4A5568 | Primary UI | ████ |
| Muted Green | `#4A8A5A` | #00A86B | Success | ████ |
| Light Text | `#E0E0E0` | #2C3E50 | Text | ████ |
| Dim Blue | `#3A70B0` | #4A90E2 | Links | ████ |

## 🧠 Benefits for Productivity

- **Reduced eye strain** during long work sessions
- **Better focus** with fewer distractions
- **Professional appearance** for work apps
- **Battery saving** on laptops and devices
- **Calmer interface** for deep work

## 💻 Implementation

```css
@media (prefers-color-scheme: dark) {
  :root {
    --background: #1A1E2B;
    --surface: #252A3A;
    --primary: #A0A0A0;
    --success: #4A8A5A;
    --text: #E0E0E0;
    --link: #3A70B0;
  }
}

.deep-work-mode {
  background: var(--background);
  color: var(--text);
}
