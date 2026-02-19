# 🎨 Education App - Primary Palette

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-Education-4A90E2?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Primary-00A86B?style=flat-square)]()
  [![Focus](https://img.shields.io/badge/Focus-High-FFD700?style=flat-square)]()
  
  ---
  
  | [🏠 Education Home](../README.md) | [🌙 Dark Mode](./dark-mode.md) | [💎 Luxury Style](./luxury-style.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 🎨 Color Palette

| Color Name | Hex | HSL | Usage | Preview |
|------------|-----|-----|-------|---------|
| Cool Blue | `#4A90E2` | `hsl(214, 82%, 62%)` | Primary interactive, links | ████ |
| Jade Green | `#00A86B` | `hsl(156, 100%, 33%)` | Progress, completion | ████ |
| Warm White | `#FFF9F0` | `hsl(40, 100%, 97%)` | Reading backgrounds | ████ |
| Deep Purple | `#5E4B8A` | `hsl(258, 30%, 42%)` | Creative subjects | ████ |
| Soft Coral | `#FF9A8B` | `hsl(8, 100%, 77%)` | Alerts, notifications | ████ |
| Slate Gray | `#4A5568` | `hsl(218, 18%, 35%)` | Body text | ████ |

## 🧠 Color Psychology

| Color | Emotion | Best Used For |
|-------|---------|---------------|
| **Cool Blue** | Focus, Calm, Trust | Navigation, links, CTAs |
| **Jade Green** | Growth, Progress | Quiz completion, badges |
| **Warm White** | Comfort, Readability | Reading backgrounds |
| **Deep Purple** | Creativity, Wisdom | Arts, literature sections |
| **Soft Coral** | Gentle urgency | Due dates, reminders |

## 💻 Implementation

```css
:root {
  --education-primary: #4A90E2;
  --education-primary-dark: #3A70B0;
  --education-primary-light: #6BA5E8;
  
  --education-success: #00A86B;
  --education-success-dark: #008C56;
  
  --education-background: #FFF9F0;
  --education-surface: #FFFFFF;
  
  --education-creative: #5E4B8A;
  --education-alert: #FF9A8B;
  
  --education-text: #4A5568;
  --education-text-light: #718096;
}

.lesson-card {
  background: var(--education-surface);
  border-radius: 12px;
  padding: 20px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.05);
  border-left: 4px solid var(--education-primary);
}

.progress-bar {
  background: var(--education-success);
  height: 8px;
  border-radius: 4px;
}

.creative-badge {
  background: var(--education-creative);
  color: white;
  padding: 4px 12px;
  border-radius: 20px;
}
