# 🌙 Education App - Dark Mode

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-Education-4A90E2?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Dark%20Mode-1A1E2B?style=flat-square)]()
  [![Study](https://img.shields.io/badge/Study-Night%20Optimized-00A86B?style=flat-square)]()
  
  ---
  
  | [🏠 Education Home](../README.md) | [🎨 Primary](./primary-palette.md) | [💎 Luxury](./luxury-style.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 🌙 Dark Mode Palette

| Color | Hex | Original | Usage | Preview |
|-------|-----|----------|-------|---------|
| Dark Slate | `#1A1E2B` | #FFF9F0 | Background | ████ |
| Surface Dark | `#252A3A` | #FFFFFF | Cards | ████ |
| Soft Blue | `#6A9AE5` | #4A90E2 | Primary | ████ |
| Warm Gray | `#D3D3D3` | #4A5568 | Text | ████ |
| Muted Green | `#4A8A5A` | #00A86B | Success | ████ |
| Dim Purple | `#4A3A6A` | #5E4B8A | Creative | ████ |

## 🧠 Benefits for Education

- **Reduced blue light** during nighttime study sessions
- **Better sleep quality** after late-night learning
- **Improved focus** with reduced distractions
- **Battery saving** on OLED devices during long study sessions

## 💻 Implementation

```css
@media (prefers-color-scheme: dark) {
  :root {
    --background: #1A1E2B;
    --surface: #252A3A;
    --primary: #6A9AE5;
    --text: #D3D3D3;
    --success: #4A8A5A;
    --creative: #4A3A6A;
  }
}

.study-mode {
  background: var(--background);
  color: var(--text);
  transition: all 0.3s ease;
}
