# 🌙 Music App - Dark Mode

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-Music-6C5CE7?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Dark%20Mode-1A1E2B?style=flat-square)]()
  [![Immersive](https://img.shields.io/badge/Immersive-Listening-00A86B?style=flat-square)]()
  
  ---
  
  | [🏠 Music Home](../README.md) | [🎨 Primary](./primary-palette.md) | [💎 Luxury](./luxury-style.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 🌙 Dark Mode Palette

| Color | Hex | Original | Usage | Preview |
|-------|-----|----------|-------|---------|
| Pure Black | `#000000` | #0A0A0A | Background (OLED) | ████ |
| Dark Surface | `#121212` | #1A1A1A | Cards | ████ |
| Dim Purple | `#4A3A7A` | #6C5CE7 | Primary | ████ |
| Muted Green | `#2A6A4A` | #00A86B | Accent | ████ |
| Soft White | `#E0E0E0` | #FFFFFF | Text | ████ |
| Dim Blue | `#3A5A8A` | #4A90E2 | Links | ████ |

## 🧠 Benefits for Music Apps

- **OLED perfect** for music players
- **Concert-like atmosphere** at night
- **Album art pops** against dark backgrounds
- **Reduced eye strain** during late listening
- **Battery saving** on mobile devices

## 💻 Implementation

```css
@media (prefers-color-scheme: dark) {
  :root {
    --background: #000000;
    --surface: #121212;
    --primary: #4A3A7A;
    --accent: #2A6A4A;
    --text: #E0E0E0;
    --link: #3A5A8A;
  }
}

.album-art {
  filter: brightness(1.1) contrast(1.1);
}
```
## 🔗 Related Links

| Icon | Link | Description |
|:----:|:----|:-----------:|
| 🎨 | [Music Primary Palette](./primary-palette.md) | Main color scheme |
| 💎 | [Music Luxury Style](./luxury-style.md) | Premium palette |
| 📱 | [Music Examples](./examples/) | Case studies |

---

**[⬆ Back to Top](#top)** • **[🏠 Music Home](../README.md)**
