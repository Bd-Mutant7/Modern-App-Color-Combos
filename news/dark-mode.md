# 🌙 News App - Dark Mode

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-News-2C3E50?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Dark%20Mode-1A1E2B?style=flat-square)]()
  [![Reading](https://img.shields.io/badge/Reading-Night%20Mode-00A86B?style=flat-square)]()
  
  ---
  
  | [🏠 News Home](../README.md) | [🎨 Primary](./primary-palette.md) | [💎 Luxury](./luxury-style.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 🌙 Dark Mode Palette

| Color | Hex | Original | Usage | Preview |
|-------|-----|----------|-------|---------|
| Dark Navy | `#1A1E2B` | #FFFFFF | Background | ████ |
| Surface Dark | `#252A3A` | #F8F9FA | Cards | ████ |
| Light Text | `#E0E0E0` | #2C3E50 | Headlines | ████ |
| Soft Red | `#B84A3A` | #E74C3C | Breaking news | ████ |
| Gray Text | `#A0A0A0` | #7F8C8D | Metadata | ████ |
| Dim Blue | `#5A7AB0` | #4A90E2 | Links | ████ |

## 🧠 Benefits for News Apps

- **Comfortable reading** in low light
- **Reduced eye strain** during long reading sessions
- **Battery saving** on mobile devices
- **Focus on content** without bright backgrounds
- **Cinematic feel** for photo journalism

## 💻 Implementation

```css
@media (prefers-color-scheme: dark) {
  :root {
    --background: #1A1E2B;
    --surface: #252A3A;
    --text: #E0E0E0;
    --breaking: #B84A3A;
    --meta: #A0A0A0;
    --link: #5A7AB0;
  }
}

.night-mode .article-image {
  filter: brightness(0.8);
}
```
## 🔗 Related Links

| Icon | Link | Description |
|:----:|:----|:-----------:|
| 🎨 | [News Primary Palette](./primary-palette.md) | Main color scheme |
| 💎 | [News Luxury Style](./luxury-style.md) | Premium palette |
| 📱 | [News Examples](./examples/) | Case studies |

---

**[⬆ Back to Top](#top)** • **[🏠 News Home](../README.md)**
