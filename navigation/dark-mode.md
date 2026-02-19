# 🌙 Navigation App - Dark Mode

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-Navigation-4A90E2?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Dark%20Mode-1A1E2B?style=flat-square)]()
  [![Night](https://img.shields.io/badge/Night-Driving-00A86B?style=flat-square)]()
  
  ---
  
  | [🏠 Navigation Home](../README.md) | [🎨 Primary](./primary-palette.md) | [💎 Luxury](./luxury-style.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 🌙 Dark Mode Palette

| Color | Hex | Original | Usage | Preview |
|-------|-----|----------|-------|---------|
| Deep Space | `#1A1A2E` | #FFFFFF | Map background | ████ |
| Soft Blue | `#4A90E2` | #4A90E2 | Primary route | ████ |
| Warm Gray | `#A0A0A0` | #4A5568 | Secondary roads | ████ |
| Muted Green | `#1E4A1E` | #2E7D32 | Parks | ████ |
| Dim Red | `#B84A4A` | #FF6B4A | Traffic alerts | ████ |

## 🧠 Benefits for Navigation

- **Reduced glare** during night driving
- **Better contrast** in low-light conditions
- **Less eye strain** on long trips
- **OLED battery savings** on car displays

## 💻 Implementation

```css
@media (prefers-color-scheme: dark) {
  :root {
    --map-bg: #1A1A2E;
    --route: #4A90E2;
    --secondary: #A0A0A0;
    --park: #1E4A1E;
    --alert: #B84A4A;
  }
}

.night-mode .map {
  background: var(--map-bg);
  color: white;
}
```
## 🔗 Related Links

| Icon | Link | Description |
|:----:|:----|:-----------:|
| 🎨 | [Navigation Primary Palette](./primary-palette.md) | Main color scheme |
| 💎 | [Navigation Luxury Style](./luxury-style.md) | Premium palette |
| 📱 | [Navigation Examples](./examples/) | Case studies |

---

**[⬆ Back to Top](#top)** • **[🏠 Navigation Home](../README.md)**
