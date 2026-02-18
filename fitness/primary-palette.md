# 🎨 Fitness App - Primary Palette

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-Fitness-FF6B4A?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Primary-00A86B?style=flat-square)]()
  [![Energy](https://img.shields.io/badge/Energy-High-FFD700?style=flat-square)]()
  
  ---
  
  | [🏠 Fitness Home](../README.md) | [🌙 Dark Mode](../dark-mode.md) | [💎 Luxury Style](../luxury-style.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 🎨 Color Palette

| Color Name | Hex | HSL | Usage | Preview |
|------------|-----|-----|-------|---------|
| Persimmon | `#FF6B4A` | `hsl(14, 100%, 64%)` | Primary CTA, workout start | ████ |
| Deep Indigo | `#2C3E50` | `hsl(210, 29%, 24%)` | Text, backgrounds | ████ |
| Clean White | `#FFFFFF` | `hsl(0, 0%, 100%)` | Cards, negative space | ████ |
| Acid Green | `#BFFF00` | `hsl(74, 100%, 50%)` | Achievements, PRs | ████ |
| Electric Blue | `#4A90E2` | `hsl(214, 82%, 62%)` | Recovery data, rest days | ████ |
| Success Green | `#00A86B` | `hsl(156, 100%, 33%)` | Completed workouts | ████ |

## 🧠 Color Psychology

| Color | Emotion | Best Used For |
|-------|---------|---------------|
| **Persimmon** | Energy, Urgency, Action | Start workout, CTA buttons |
| **Acid Green** | Achievement, Victory | Personal records, badges |
| **Electric Blue** | Calm, Recovery | Rest days, cool-down |
| **Deep Indigo** | Strength, Stability | Text, structure |
| **Success Green** | Completion, Done | Finished workouts |

## ♿ Accessibility

| Pair | Ratio | WCAG | Status |
|------|-------|------|--------|
| Indigo (#2C3E50) on White | 12:1 | AAA | ✅ |
| Persimmon (#FF6B4A) on White | 4.5:1 | AA | ✅ |
| Acid Green (#BFFF00) on White | 1.8:1 | Decorative | ⚠️ |

## 💻 Implementation

```css
:root {
  --fitness-primary: #FF6B4A;
  --fitness-primary-dark: #E04F4A;
  --fitness-secondary: #2C3E50;
  --fitness-background: #FFFFFF;
  --fitness-accent: #BFFF00;
  --fitness-recovery: #4A90E2;
  --fitness-success: #00A86B;
}

.workout-button {
  background: var(--fitness-primary);
  color: white;
  padding: 16px 32px;
  border-radius: 40px;
  font-weight: bold;
  text-transform: uppercase;
  letter-spacing: 1px;
  box-shadow: 0 4px 12px rgba(255, 107, 74, 0.3);
}

.pr-badge {
  background: var(--fitness-accent);
  color: var(--fitness-secondary);
  padding: 4px 8px;
  border-radius: 20px;
  font-weight: bold;
}
