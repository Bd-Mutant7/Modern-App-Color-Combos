# 🎨 Entertainment App - Primary Palette

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-Entertainment-6C5CE7?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Primary-00A86B?style=flat-square)]()
  [![Energy](https://img.shields.io/badge/Energy-High-FFD700?style=flat-square)]()
  
  ---
  
  | [🏠 Entertainment Home](../README.md) | [🌙 Dark Mode](./dark-mode.md) | [💎 Luxury Style](./luxury-style.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 🎨 Color Palette

| Color Name | Hex | HSL | Usage | Preview |
|------------|-----|-----|-------|---------|
| Electric Purple | `#6C5CE7` | `hsl(248, 53%, 63%)` | Primary brand, energy | ████ |
| Vibrant Orange | `#FF6B4A` | `hsl(14, 100%, 64%)` | CTAs, highlights | ████ |
| Deep Black | `#0A0A0A` | `hsl(0, 0%, 4%)` | Background, immersion | ████ |
| Acid Green | `#BFFF00` | `hsl(74, 100%, 50%)` | Gaming achievements | ████ |
| Electric Blue | `#4A90E2` | `hsl(214, 82%, 62%)` | Video player controls | ████ |
| Pure White | `#FFFFFF` | `hsl(0, 0%, 100%)` | Text, icons | ████ |

## 🧠 Color Psychology

| Color | Emotion | Best Used For |
|-------|---------|---------------|
| **Electric Purple** | Creativity, Magic | Brand identity |
| **Vibrant Orange** | Energy, Action | Play buttons, CTAs |
| **Deep Black** | Immersion, Mystery | Backgrounds, cinema mode |
| **Acid Green** | Achievement, Level up | Gaming elements |
| **Electric Blue** | Calm, Interface | Video controls |

## 💻 Implementation

```css
:root {
  --entertainment-primary: #6C5CE7;
  --entertainment-primary-dark: #5A4AC7;
  --entertainment-accent: #FF6B4A;
  --entertainment-background: #0A0A0A;
  --entertainment-gaming: #BFFF00;
  --entertainment-controls: #4A90E2;
  --entertainment-text: #FFFFFF;
}

.play-button {
  background: var(--entertainment-accent);
  color: white;
  width: 60px;
  height: 60px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  box-shadow: 0 4px 20px rgba(255, 107, 74, 0.4);
}

.gaming-badge {
  background: var(--entertainment-gaming);
  color: black;
  padding: 4px 12px;
  border-radius: 20px;
  font-weight: bold;
}
