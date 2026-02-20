# 🎨 News App - Primary Palette

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-News-2C3E50?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Primary-00A86B?style=flat-square)]()
  [![Trust](https://img.shields.io/badge/Trust-High-FFD700?style=flat-square)]()
  
  ---
  
  | [🏠 News Home](../README.md) | [🌙 Dark Mode](./dark-mode.md) | [💎 Luxury Style](./luxury-style.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 🎨 Color Palette

| Color Name | Hex | HSL | Usage | Preview |
|------------|-----|-----|-------|---------|
| Deep Navy | `#2C3E50` | `hsl(210, 29%, 24%)` | Headlines, authority | ████ |
| Breaking Red | `#E74C3C` | `hsl(6, 78%, 57%)` | Breaking news, alerts | ████ |
| Clean White | `#FFFFFF` | `hsl(0, 0%, 100%)` | Background, readability | ████ |
| Light Gray | `#F8F9FA` | `hsl(210, 17%, 98%)` | Cards, sections | ████ |
| Slate Gray | `#7F8C8D` | `hsl(184, 6%, 52%)` | Metadata, timestamps | ████ |
| Blue Link | `#4A90E2` | `hsl(214, 82%, 62%)` | Article links | ████ |

## 🧠 Color Psychology

| Color | Emotion | Best Used For |
|-------|---------|---------------|
| **Deep Navy** | Trust, Authority | Headlines, masthead |
| **Breaking Red** | Urgency, Alert | Breaking news |
| **Clean White** | Clarity, Truth | Article backgrounds |
| **Light Gray** | Neutral, Calm | Section dividers |
| **Slate Gray** | Secondary | Timestamps, bylines |

## 💻 Implementation

```css
:root {
  --news-primary: #2C3E50;
  --news-primary-dark: #1A2A3A;
  --news-breaking: #E74C3C;
  --news-background: #FFFFFF;
  --news-surface: #F8F9FA;
  --news-meta: #7F8C8D;
  --news-link: #4A90E2;
}

.article-card {
  background: var(--news-surface);
  border-radius: 8px;
  padding: 16px;
  margin: 8px 0;
  box-shadow: 0 1px 3px rgba(0,0,0,0.1);
}

.headline {
  color: var(--news-primary);
  font-size: 20px;
  font-weight: bold;
  margin-bottom: 8px;
}

.breaking-badge {
  background: var(--news-breaking);
  color: white;
  padding: 4px 8px;
  border-radius: 4px;
  font-size: 12px;
  font-weight: bold;
  text-transform: uppercase;
  display: inline-block;
  animation: pulse 2s infinite;
}

.timestamp {
  color: var(--news-meta);
  font-size: 12px;
}

.article-link {
  color: var(--news-link);
  text-decoration: none;
  font-weight: 500;
}
```
## 🔗 Related Links

| Icon | Link | Description |
|:----:|:----|:-----------:|
| 🌙 | [News Dark Mode](./dark-mode.md) | Dark theme variant |
| 💎 | [News Luxury Style](./luxury-style.md) | Premium palette |
| 📱 | [News Examples](./examples/) | Case studies |
| 📺 | [BBC News](./examples/bbc-example.md) | Global news |
| 📡 | [CNN](./examples/cnn-example.md) | Cable news |
| 📰 | [Reuters](./examples/reuters-example.md) | Wire service |

---

**[⬆ Back to Top](#top)** • **[🏠 News Home](../README.md)**
