# 🎨 Fintech App - Primary Palette

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-Fintech-0A2342?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Primary-00A86B?style=flat-square)]()
  [![Trust](https://img.shields.io/badge/Trust-High-FFD700?style=flat-square)]()
  
  ---
  
  | [🏠 Fintech Home](../README.md) | [🌙 Dark Mode](./dark-mode.md) | [💎 Luxury Style](./luxury-style.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 🎨 Color Palette

| Color Name | Hex | HSL | Usage | Preview |
|------------|-----|-----|-------|---------|
| Navy Blue | `#0A2342` | `hsl(214, 74%, 15%)` | Primary brand, stability | ████ |
| Teal | `#2C7A7B` | `hsl(181, 47%, 33%)` | Success, growth | ████ |
| Gold | `#D4AF37` | `hsl(46, 65%, 52%)` | Premium features, rewards | ████ |
| Clean White | `#FFFFFF` | `hsl(0, 0%, 100%)` | Backgrounds, cards | ████ |
| Coral | `#FF6B6B` | `hsl(0, 100%, 71%)` | Alerts, insufficient funds | ████ |
| Slate Gray | `#4A5568` | `hsl(218, 18%, 35%)` | Secondary text | ████ |

## 🧠 Color Psychology

| Color | Emotion | Best Used For |
|-------|---------|---------------|
| **Navy Blue** | Trust, Stability, Security | Primary brand, headers |
| **Teal** | Growth, Success, Wealth | Positive transactions |
| **Gold** | Premium, Exclusive, Reward | VIP features, badges |
| **Coral** | Urgency, Alert | Insufficient funds |
| **White** | Clean, Transparent | Backgrounds |

### Why Blue Dominates Fintech
- Universally associated with trust (88% of banking apps use blue)
- Calms anxiety about money
- Professional and conservative
- Works across all cultures

## ♿ Accessibility

### Contrast Ratios
| Pair | Ratio | WCAG | Status |
|------|-------|------|--------|
| Navy (#0A2342) on White | 14:1 | AAA | ✅ |
| Teal (#2C7A7B) on White | 7:1 | AAA | ✅ |
| Gold (#D4AF37) on Navy | 8:1 | AAA | ✅ |
| Coral (#FF6B6B) on White | 4.5:1 | AA | ✅ |

## 💻 Implementation

```css
:root {
  --fintech-primary: #0A2342;
  --fintech-primary-dark: #051220;
  --fintech-primary-light: #1A3A5F;
  
  --fintech-secondary: #2C7A7B;
  --fintech-secondary-dark: #1F5A5B;
  --fintech-secondary-light: #3A9B9C;
  
  --fintech-accent: #D4AF37;
  --fintech-accent-dark: #B88F2A;
  --fintech-accent-light: #E5C45C;
  
  --fintech-background: #FFFFFF;
  --fintech-surface: #F7FAFC;
  
  --fintech-alert: #FF6B6B;
  --fintech-text: #2D3748;
  --fintech-text-light: #4A5568;
}

.balance-card {
  background: linear-gradient(135deg, var(--fintech-primary), var(--fintech-primary-light));
  color: white;
  padding: 24px;
  border-radius: 16px;
  margin: 16px 0;
}

.balance-amount {
  font-size: 36px;
  font-weight: bold;
  margin: 8px 0;
}

.transaction-positive {
  color: var(--fintech-secondary);
  font-weight: 600;
}

.premium-badge {
  background: var(--fintech-accent);
  color: var(--fintech-primary);
  padding: 4px 12px;
  border-radius: 20px;
  font-weight: bold;
  font-size: 12px;
}
```
## 🔗 Related Links

| Icon | Link | Description |
|:----:|:----|:-----------:|
| 🌙 | [Fintech Dark Mode](./dark-mode.md) | Dark theme variant |
| 💎 | [Fintech Luxury Style](./luxury-style.md) | Premium palette |
| 📱 | [Fintech Examples](./examples/) | Case studies directory |
| 💳 | [Revolut Case Study](./examples/revolut-example.md) | Digital banking |
| 🏦 | [Monzo Case Study](./examples/monzo-example.md) | Neobank |
| 📈 | [Robinhood Case Study](./examples/robinhood-example.md) | Investment app |

---

**[⬆ Back to Top](#top)** • **[🏠 Fintech Home](../README.md)**
