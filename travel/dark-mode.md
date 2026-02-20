# 🌙 Travel App - Dark Mode

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-Travel-4A90E2?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Dark%20Mode-1A1E2B?style=flat-square)]()
  [![Night](https://img.shields.io/badge/Night-Planning-00A86B?style=flat-square)]()
  
  ---
  
  | [🏠 Travel Home](../README.md) | [🎨 Primary](./primary-palette.md) | [💎 Luxury](./luxury-style.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 🌙 Dark Mode Palette

| Color | Hex | Original | Usage | Preview |
|-------|-----|----------|-------|---------|
| Midnight Blue | `#0A1A2A` | #F5E6D3 | Background | ████ |
| Dark Surface | `#1A2A3A` | #FFFFFF | Cards | ████ |
| Soft Blue | `#6A9AE5` | #4A90E2 | Primary | ████ |
| Muted Orange | `#B85A3A` | #FF6B4A | Deals | ████ |
| Dim Green | `#2A6A4A` | #00A86B | Eco | ████ |
| Light Sand | `#D2B48C` | #0A2342 | Text | ████ |

## 🧠 Benefits for Travel Apps

- **Night flight planning** without eye strain
- **Reduced glare** on mobile devices
- **Battery saving** during long trips
- **Cinematic feel** for destination photos
- **Comfortable** for late-night booking

## 💻 Implementation

```css
@media (prefers-color-scheme: dark) {
  :root {
    --background: #0A1A2A;
    --surface: #1A2A3A;
    --primary: #6A9AE5;
    --accent: #B85A3A;
    --eco: #2A6A4A;
    --text: #D2B48C;
  }
}

.night-mode .destination-image {
  filter: brightness(0.8);
}
```
## 🔗 Related Links

| Icon | Link | Description |
|:----:|:----|:-----------:|
| 🎨 | [Travel Primary Palette](./primary-palette.md) | Main color scheme |
| 💎 | [Travel Luxury Style](./luxury-style.md) | Premium palette |
| 📱 | [Travel Examples](./examples/) | Case studies |

---

**[⬆ Back to Top](#top)** • **[🏠 Travel Home](../README.md)**
