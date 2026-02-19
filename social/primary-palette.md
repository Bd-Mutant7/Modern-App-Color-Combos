# 🎨 Social App - Primary Palette

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-Social-4A90E2?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Primary-00A86B?style=flat-square)]()
  [![Engagement](https://img.shields.io/badge/Engagement-High-FFD700?style=flat-square)]()
  
  ---
  
  | [🏠 Social Home](../README.md) | [🌙 Dark Mode](./dark-mode.md) | [💎 Luxury Style](./luxury-style.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 🎨 Color Palette

| Color Name | Hex | HSL | Usage | Preview |
|------------|-----|-----|-------|---------|
| Vibrant Blue | `#4A90E2` | `hsl(214, 82%, 62%)` | Primary brand, links | ████ |
| Energetic Orange | `#FF6B4A` | `hsl(14, 100%, 64%)` | Notifications, alerts | ████ |
| Royal Purple | `#6C5CE7` | `hsl(248, 53%, 63%)` | Premium features | ████ |
| Clean White | `#FFFFFF` | `hsl(0, 0%, 100%)` | Backgrounds | ████ |
| Soft Gray | `#F8F9FA` | `hsl(210, 17%, 98%)` | Cards, surfaces | ████ |
| Charcoal | `#2C3E50` | `hsl(210, 29%, 24%)` | Text, icons | ████ |

## 🧠 Color Psychology

| Color | Emotion | Best Used For |
|-------|---------|---------------|
| **Vibrant Blue** | Trust, Connection | Profile links, CTAs |
| **Energetic Orange** | Urgency, Action | Notifications, likes |
| **Royal Purple** | Creativity, Premium | Verified badges |
| **Clean White** | Fresh, Clean | Feed background |
| **Soft Gray** | Neutral, Calm | Cards, dividers |

## 💻 Implementation

```css
:root {
  --social-primary: #4A90E2;
  --social-primary-dark: #3A70B0;
  --social-notification: #FF6B4A;
  --social-premium: #6C5CE7;
  --social-background: #FFFFFF;
  --social-surface: #F8F9FA;
  --social-text: #2C3E50;
}

.notification-badge {
  background: var(--social-notification);
  color: white;
  padding: 2px 6px;
  border-radius: 12px;
  font-size: 12px;
  font-weight: bold;
}

.verified-badge {
  background: var(--social-premium);
  color: white;
  width: 20px;
  height: 20px;
  border-radius: 50%;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  font-size: 12px;
}

.post-card {
  background: var(--social-surface);
  border-radius: 12px;
  padding: 16px;
  margin: 8px 0;
  box-shadow: 0 2px 4px rgba(0,0,0,0.05);
}
