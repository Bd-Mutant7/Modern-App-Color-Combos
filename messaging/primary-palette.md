# 🎨 Messaging App - Primary Palette

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-Messaging-4A90E2?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Primary-00A86B?style=flat-square)]()
  [![Trust](https://img.shields.io/badge/Trust-High-FFD700?style=flat-square)]()
  
  ---
  
  | [🏠 Messaging Home](../README.md) | [🌙 Dark Mode](./dark-mode.md) | [💎 Luxury Style](./luxury-style.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 🎨 Color Palette

| Color Name | Hex | HSL | Usage | Preview |
|------------|-----|-----|-------|---------|
| Trust Blue | `#4A90E2` | `hsl(214, 82%, 62%)` | Primary brand, sent messages | ████ |
| Secure Green | `#00A86B` | `hsl(156, 100%, 33%)` | Online status, delivered | ████ |
| Clean White | `#FFFFFF` | `hsl(0, 0%, 100%)` | Background, chat bubbles | ████ |
| Light Gray | `#F0F2F5` | `hsl(210, 20%, 95%)` | Received messages | ████ |
| Slate Gray | `#2C3E50` | `hsl(210, 29%, 24%)` | Text, timestamps | ████ |
| Accent Coral | `#FF6B4A` | `hsl(14, 100%, 64%)` | Unread badges, alerts | ████ |

## 🧠 Color Psychology

| Color | Emotion | Best Used For |
|-------|---------|---------------|
| **Trust Blue** | Reliable, Secure | Brand, sent messages |
| **Secure Green** | Safe, Online | Status indicators |
| **Clean White** | Clear, Simple | Chat backgrounds |
| **Light Gray** | Neutral, Calm | Received messages |
| **Accent Coral** | Attention | Unread notifications |

## 💻 Implementation

```css
:root {
  --messaging-primary: #4A90E2;
  --messaging-primary-dark: #3A70B0;
  --messaging-success: #00A86B;
  --messaging-background: #FFFFFF;
  --messaging-received: #F0F2F5;
  --messaging-text: #2C3E50;
  --messaging-unread: #FF6B4A;
}

.chat-bubble-sent {
  background: var(--messaging-primary);
  color: white;
  border-radius: 18px 18px 4px 18px;
  padding: 12px 16px;
  margin: 4px 0;
  max-width: 80%;
  align-self: flex-end;
}

.chat-bubble-received {
  background: var(--messaging-received);
  color: var(--messaging-text);
  border-radius: 18px 18px 18px 4px;
  padding: 12px 16px;
  margin: 4px 0;
  max-width: 80%;
  align-self: flex-start;
}

.status-online {
  background: var(--messaging-success);
  width: 10px;
  height: 10px;
  border-radius: 50%;
  display: inline-block;
  margin-left: 4px;
}

.unread-badge {
  background: var(--messaging-unread);
  color: white;
  min-width: 20px;
  height: 20px;
  border-radius: 10px;
  padding: 0 6px;
  font-size: 12px;
  font-weight: bold;
  display: inline-flex;
  align-items: center;
  justify-content: center;
}

.timestamp {
  color: var(--messaging-text);
  opacity: 0.6;
  font-size: 11px;
  margin-top: 4px;
}
