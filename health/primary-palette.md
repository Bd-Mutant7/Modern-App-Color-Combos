# 🎨 Health App - Primary Palette

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-Health-4ECDC4?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Primary-00A86B?style=flat-square)]()
  [![WCAG](https://img.shields.io/badge/WCAG-AAA-FF6B6B?style=flat-square)]()
  
  ---
  
  | [🏠 Health Home](../README.md) | [🌙 Dark Mode](../dark-mode.md) | [💎 Luxury Style](../luxury-style.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 🎨 Color Palette

| Color Name | Hex | HSL | Usage | Preview |
|------------|-----|-----|-------|---------|
| Soft Teal | `#4ECDC4` | `hsl(174, 55%, 55%)` | Primary actions, navigation | ████ |
| Slate Gray | `#2C3E50` | `hsl(210, 29%, 24%)` | Body text, icons | ████ |
| Clean White | `#FFFFFF` | `hsl(0, 0%, 100%)` | Background, cards | ████ |
| Coral | `#FF6B6B` | `hsl(0, 100%, 71%)` | Alerts, urgent notifications | ████ |
| Mint | `#A8E6CF` | `hsl(144, 55%, 78%)` | Success states, progress | ████ |
| Purple | `#6C5CE7` | `hsl(248, 53%, 63%)` | Sleep, meditation | ████ |
| Blue | `#4A90E2` | `hsl(214, 82%, 62%)` | Focus, information | ████ |

## 🧠 Color Psychology

| Color | Emotion | Best Used For |
|-------|---------|---------------|
| **Teal** | Trust, Calm, Professionalism | Navigation, CTAs, headers |
| **Slate** | Stability, Authority | Body text, labels, icons |
| **White** | Clean, Precise, Sterile | Backgrounds, cards, space |
| **Coral** | Urgency, Alert, Attention | Error messages, notifications |
| **Mint** | Growth, Health, Success | Progress bars, achievements |
| **Purple** | Dreams, Rest, Subconscious | Sleep features, bedtime mode |
| **Blue** | Focus, Concentration | Study mode, information panels |

## ♿ Accessibility

### Contrast Ratios
| Pair | Ratio | WCAG | Status |
|------|-------|------|--------|
| Slate (#2C3E50) on White | 12:1 | AAA | ✅ |
| Teal (#4ECDC4) on White | 4.8:1 | AA | ✅ |
| Coral (#FF6B6B) on White | 4.5:1 | AA | ✅ |
| Purple (#6C5CE7) on White | 7.2:1 | AAA | ✅ |
| Mint (#A8E6CF) on White | 1.8:1 | *Decorative | ⚠️ |

### Color Blind Safe Combinations
✅ **Safe Pairs:**
- Teal + Slate (distinct in all visions)
- Purple + Coral (different luminance)
- Blue + White (maximum contrast)

❌ **Avoid:**
- Mint on White (low contrast - decorative only)

## 💻 Implementation

### CSS Variables
```css
:root {
  /* Primary Palette */
  --health-primary: #4ECDC4;
  --health-primary-dark: #3A9B94;
  --health-primary-light: #7AD9D2;
  
  --health-secondary: #2C3E50;
  --health-secondary-light: #5A6A7A;
  
  --health-background: #FFFFFF;
  --health-surface: #F8FAFC;
  
  --health-accent: #FF6B6B;
  --health-accent-dark: #E04F4F;
  
  --health-success: #A8E6CF;
  --health-success-dark: #6BAF8F;
  
  --health-sleep: #6C5CE7;
  --health-focus: #4A90E2;
}

/* Usage Examples */
.health-button {
  background-color: var(--health-primary);
  color: white;
  padding: 12px 24px;
  border-radius: 8px;
  border: none;
  font-weight: 600;
  cursor: pointer;
}

.health-button:hover {
  background-color: var(--health-primary-dark);
}

.health-card {
  background-color: var(--health-surface);
  border-radius: 12px;
  padding: 16px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.health-alert {
  background-color: var(--health-accent);
  color: white;
  padding: 12px;
  border-radius: 8px;
  margin: 8px 0;
}
