# 🌙 Fitness App - Dark Mode

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-Fitness-FF6B4A?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Dark%20Mode-1A1E2B?style=flat-square)]()
  [![Gym](https://img.shields.io/badge/Gym-Optimized-00A86B?style=flat-square)]()
  
  ---
  
  | [🏠 Fitness Home](../README.md) | [🎨 Primary](./primary-palette.md) | [💎 Luxury](./luxury-style.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 🌙 Dark Mode Palette

| Color | Hex | Original | Usage | Preview |
|-------|-----|----------|-------|---------|
| Charcoal Black | `#121212` | #FFFFFF | Background | ████ |
| Dark Surface | `#1E1E2E` | #F8FAFC | Cards | ████ |
| Lava Orange | `#FF5722` | #FF6B4A | Primary CTA | ████ |
| Soft Green | `#8BC34A` | #BFFF00 | Achievements | ████ |
| Dim Blue | `#1976D2` | #4A90E2 | Recovery | ████ |
| Light Gray | `#E0E0E0` | #2C3E50 | Text | ████ |

## 🧠 Benefits for Fitness

- **Gym lighting**: Perfect for low-light gym environments
- **Night runs**: Reduces glare during evening workouts
- **Battery saving**: 43% less battery on OLED screens
- **Focus**: Removes distractions during intense workouts

## 💻 Implementation

```css
@media (prefers-color-scheme: dark) {
  :root {
    --background: #121212;
    --surface: #1E1E2E;
    --primary: #FF5722;
    --text: #E0E0E0;
    --accent: #8BC34A;
  }
}

.workout-timer {
  background: var(--surface);
  color: var(--primary);
  font-size: 48px;
  font-weight: bold;
  text-align: center;
  padding: 20px;
  border-radius: 16px;
  border: 1px solid var(--primary);
}
```
## 🔗 Related Links

| Icon | Link | Description |
|:----:|:----|:-----------:|
| 🎨 | [Fitness Primary Palette](./primary-palette.md) | Main color scheme |
| 💎 | [Fitness Luxury Style](./luxury-style.md) | Premium fitness palette |
| 📱 | [Fitness Examples](./examples/) | Case studies directory |
| 💪 | [Strava Case Study](./examples/strava-example.md) | Running tracker analysis |
| 🏋️ | [Nike Training](./examples/nike-training-example.md) | Workout app analysis |
| 📊 | [MyFitnessPal](./examples/myfitnesspal-example.md) | Nutrition tracker analysis |

---

**[⬆ Back to Top](#top)** • **[🏠 Fitness Home](../README.md)**
