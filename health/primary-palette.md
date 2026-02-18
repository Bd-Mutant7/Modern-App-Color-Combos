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
```
## React Implementation

```jsx
// healthTheme.js
export const healthTheme = {
  primary: '#4ECDC4',
  primaryDark: '#3A9B94',
  secondary: '#2C3E50',
  background: '#FFFFFF',
  surface: '#F8FAFC',
  accent: '#FF6B6B',
  success: '#A8E6CF',
  sleep: '#6C5CE7',
  focus: '#4A90E2'
};

// HealthButton.jsx
import React from 'react';
import { healthTheme } from './healthTheme';

const HealthButton = ({ children, onClick, variant = 'primary' }) => {
  const getColor = () => {
    switch(variant) {
      case 'primary': return healthTheme.primary;
      case 'accent': return healthTheme.accent;
      case 'success': return healthTheme.success;
      default: return healthTheme.primary;
    }
  };

  return (
    <button
      onClick={onClick}
      style={{
        backgroundColor: getColor(),
        color: 'white',
        padding: '12px 24px',
        border: 'none',
        borderRadius: '8px',
        cursor: 'pointer',
        fontWeight: '600'
      }}
    >
      {children}
    </button>
  );
};

export default HealthButton;
```
## Flutter Implementation

```dart
// lib/theme/health_theme.dart
import 'package:flutter/material.dart';

class HealthTheme {
  static const Color primary = Color(0xFF4ECDC4);
  static const Color primaryDark = Color(0xFF3A9B94);
  static const Color secondary = Color(0xFF2C3E50);
  static const Color background = Color(0xFFFFFFFF);
  static const Color surface = Color(0xFFF8FAFC);
  static const Color accent = Color(0xFFFF6B6B);
  static const Color success = Color(0xFFA8E6CF);
  static const Color sleep = Color(0xFF6C5CE7);
  static const Color focus = Color(0xFF4A90E2);

  static ThemeData get theme => ThemeData(
    primaryColor: primary,
    scaffoldBackgroundColor: background,
    appBarTheme: AppBarTheme(
      backgroundColor: primary,
      foregroundColor: Colors.white,
    ),
    colorScheme: ColorScheme.light(
      primary: primary,
      secondary: accent,
      background: background,
      surface: surface,
    ),
  );
}
```
## SwiftUI Implementation

```swift
import SwiftUI

extension Color {
    init(hex: String) {
        let hex = hex.trimmingCharacters(in: CharacterSet.alphanumerics.inverted)
        var int: UInt64 = 0
        Scanner(string: hex).scanHexInt64(&int)
        let a, r, g, b: UInt64
        switch hex.count {
        case 3: // RGB (12-bit)
            (a, r, g, b) = (255, (int >> 8) * 17, (int >> 4 & 0xF) * 17, (int & 0xF) * 17)
        case 6: // RGB (24-bit)
            (a, r, g, b) = (255, int >> 16, int >> 8 & 0xFF, int & 0xFF)
        case 8: // ARGB (32-bit)
            (a, r, g, b) = (int >> 24, int >> 16 & 0xFF, int >> 8 & 0xFF, int & 0xFF)
        default:
            (a, r, g, b) = (1, 1, 1, 0)
        }
        self.init(
            .sRGB,
            red: Double(r) / 255,
            green: Double(g) / 255,
            blue: Double(b) / 255,
            opacity: Double(a) / 255
        )
    }
}

struct HealthTheme {
    static let primary = Color(hex: "4ECDC4")
    static let primaryDark = Color(hex: "3A9B94")
    static let secondary = Color(hex: "2C3E50")
    static let background = Color.white
    static let surface = Color(hex: "F8FAFC")
    static let accent = Color(hex: "FF6B6B")
    static let success = Color(hex: "A8E6CF")
    static let sleep = Color(hex: "6C5CE7")
    static let focus = Color(hex: "4A90E2")
}
```
## 🔗 Related Links

| Icon | Link | Description |
|:----:|:----|:-----------:|
| 🌙 | [Health Dark Mode](./dark-mode.md) | Dark theme variant |
| 💎 | [Health Luxury Style](./luxury-style.md) | Premium health palette |
| 📱 | [Health Examples](./examples/) | Case studies directory |
| 🧘 | [Headspace Case Study](./examples/headspace-example.md) | Meditation app analysis |
| 🏥 | [MyChart Case Study](./examples/mychart-example.md) | Patient portal analysis |
| 🔴 | [Clue Case Study](./examples/clue-example.md) | Period tracker analysis |

---

**[⬆ Back to Top](#top)** • **[🏠 Back to Health](../README.md)** • **[📚 Main README](../../README.md)**
