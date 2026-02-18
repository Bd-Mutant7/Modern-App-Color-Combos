# 🧘 Headspace - Meditation App Case Study

<div align="center">
  
  [![App](https://img.shields.io/badge/App-Headspace-4ECDC4?style=flat-square)]()
  [![Category](https://img.shields.io/badge/Category-Health-00A86B?style=flat-square)](../)
  [![Downloads](https://img.shields.io/badge/Downloads-70M+-4A90E2?style=flat-square)]()
  [![Rating](https://img.shields.io/badge/Rating-4.9⭐-FFD700?style=flat-square)]()
  
  ---
  
  | [⬅️ Back to Examples](./) | [🏠 Health Home](../README.md) | [🎨 Primary Palette](../primary-palette.md) | [🌙 Dark Mode](../dark-mode.md) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 📱 App Overview
**Headspace** is a leading meditation and mindfulness app that helps users reduce stress, improve focus, and sleep better through guided exercises. With over 70 million downloads, it's one of the most popular wellness apps worldwide.

### Key Features
- Guided meditation sessions
- Sleep sounds and stories
- Focus music
- Mindfulness courses
- Daily reminders and progress tracking

## 🎨 Color Palette Used

```css
:root {
  --primary: #4ECDC4;        /* Teal - Calm & Trust */
  --secondary: #2C3E50;       /* Slate Gray - Focus */
  --background: #FFFFFF;       /* White - Clarity */
  --accent: #FF6B6B;           /* Coral - Energy */
  --sleep: #6C5CE7;            /* Purple - Sleep & Dreams */
  --calm: #A8E6CF;             /* Mint - Relaxation */
  --focus: #4A90E2;            /* Blue - Concentration */
}
```
## 🧠 Why This Palette Works
1. Color Psychology for Wellness
- Teal: Scientifically proven to reduce anxiety
- Purple: Associated with dreams and subconscious
- Mint: Triggers feelings of freshness and calm
- Coral: Provides gentle energy without aggression

2. Time-of-Day Adaptation

```css
/* Morning mode - Energizing */
.morning-mode {
  --accent: #FF6B4A;  /* Warmer coral */
  --primary: #4ECDC4; /* Bright teal */
}

/* Evening mode - Calming */
.evening-mode {
  --accent: #6C5CE7;  /* Purple for sleep */
  --primary: #3A9B94; /* Muted teal */
}
```
### 💻 Implementation Details

```css
:root {
  /* Headspace Theme */
  --headspace-primary: #4ECDC4;
  --headspace-primary-dark: #3A9B94;
  --headspace-primary-light: #7AD9D2;
  
  --headspace-sleep: #6C5CE7;
  --headspace-sleep-dark: #5A4AC7;
  --headspace-sleep-light: #8A7CE9;
  
  --headspace-focus: #4A90E2;
  --headspace-calm: #A8E6CF;
  
  --headspace-text: #2C3E50;
  --headspace-background: #FFFFFF;
  --headspace-surface: #F8FAFC;
  --headspace-accent: #FF6B6B;
}

/* Meditation Timer */
.meditation-timer {
  background: linear-gradient(135deg, var(--headspace-primary), var(--headspace-calm));
  color: var(--headspace-text);
  padding: 20px;
  border-radius: 20px;
}

/* Sleep Card */
.sleep-card {
  background: var(--headspace-sleep);
  color: white;
  padding: 16px;
  border-radius: 16px;
  box-shadow: 0 10px 20px rgba(108, 92, 231, 0.2);
}

.sleep-card:hover {
  background: var(--headspace-sleep-dark);
  transform: translateY(-2px);
  transition: all 0.3s ease;
}

/* Focus Mode */
.focus-timer {
  background: var(--headspace-focus);
  color: white;
  font-size: 48px;
  font-weight: 300;
  text-align: center;
  padding: 30px;
  border-radius: 30px;
}
```
React Component Example

```jsx
import React, { useState } from 'react';
import './HeadspaceTheme.css';

const MeditationCard = ({ title, duration, type }) => {
  const getTypeColor = () => {
    switch(type) {
      case 'sleep': return 'var(--headspace-sleep)';
      case 'focus': return 'var(--headspace-focus)';
      case 'calm': return 'var(--headspace-calm)';
      default: return 'var(--headspace-primary)';
    }
  };

  return (
    <div className="meditation-card" style={{ 
      background: getTypeColor(),
      padding: '20px',
      borderRadius: '15px',
      margin: '10px'
    }}>
      <h3 style={{ color: 'white', marginBottom: '8px' }}>{title}</h3>
      <p style={{ color: 'rgba(255,255,255,0.9)' }}>{duration} minutes</p>
    </div>
  );
};

const HeadspaceApp = () => {
  const [currentMode, setCurrentMode] = useState('meditate');
  
  return (
    <div className="headspace-app">
      <nav style={{ background: 'var(--headspace-primary)' }}>
        <button onClick={() => setCurrentMode('meditate')}>Meditate</button>
        <button onClick={() => setCurrentMode('sleep')}>Sleep</button>
        <button onClick={() => setCurrentMode('focus')}>Focus</button>
      </nav>
      
      <div className="content">
        {currentMode === 'sleep' && (
          <MeditationCard title="Sleep Stories" duration="45" type="sleep" />
        )}
        {currentMode === 'focus' && (
          <MeditationCard title="Focus Music" duration="60" type="focus" />
        )}
      </div>
    </div>
  );
};

export default HeadspaceApp;
```
### SwiftUI Implementation

```swift
import SwiftUI

struct HeadspaceTheme {
    static let primary = Color(hex: "4ECDC4")
    static let sleep = Color(hex: "6C5CE7")
    static let focus = Color(hex: "4A90E2")
    static let calm = Color(hex: "A8E6CF")
    static let accent = Color(hex: "FF6B6B")
    static let text = Color(hex: "2C3E50")
}

struct MeditationView: View {
    @State private var isBreathing = false
    
    var body: some View {
        ZStack {
            HeadspaceTheme.primary
                .ignoresSafeArea()
                .opacity(0.1)
            
            VStack(spacing: 20) {
                Text("Meditation")
                    .font(.largeTitle)
                    .foregroundColor(HeadspaceTheme.text)
                
                Circle()
                    .fill(HeadspaceTheme.calm)
                    .frame(width: 200, height: 200)
                    .scaleEffect(isBreathing ? 1.2 : 0.8)
                    .animation(
                        Animation.easeInOut(duration: 4)
                            .repeatForever(autoreverses: true),
                        value: isBreathing
                    )
                
                Button("Start") {
                    isBreathing.toggle()
                }
                .padding()
                .background(HeadspaceTheme.primary)
                .foregroundColor(.white)
                .cornerRadius(10)
            }
        }
        .onAppear {
            isBreathing = true
        }
    }
}
```
### Dark Mode Support

```css
@media (prefers-color-scheme: dark) {
  :root {
    --background: #1A1E2B;
    --surface: #252A3A;
    --text: #E0E0E0;
    --primary: #3A9B94;
    --sleep: #5A4AC7;
  }
}
```
## 🔗 Related Resources

### 📂 Internal Navigation
| Link | Path |
|------|------|
| [📁 Back to Health Examples](./) | `./` |
| [🎨 Health Primary Palette](../primary-palette.md) | `../primary-palette.md` |
| [🌙 Health Dark Mode](../dark-mode.md) | `../dark-mode.md` |
| [💎 Health Luxury Style](../luxury-style.md) | `../luxury-style.md` |
| [🏠 Back to Health Category](../README.md) | `../README.md` |
| [📚 Back to Main README](../../README.md) | `../../README.md` |

### 🌐 External Links
- [🌐 Headspace Official Website](https://www.headspace.com)
- [📱 Download on App Store](https://apps.apple.com/app/headspace)
- [📱 Get it on Google Play](https://play.google.com/store/apps/details?id=com.headspace.android)
- [📘 Headspace Blog](https://www.headspace.com/blog)
- [🐦 Headspace Twitter](https://twitter.com/headspace)

### 📖 Additional Reading
- [🧘 Mindfulness App Design Guidelines](../../guidelines/mindfulness-design.md)
- [😴 Sleep App Best Practices](../../guidelines/sleep-apps.md)
- [🎯 Meditation UI Patterns](../../guidelines/meditation-ui.md)
- [🧠 Color Psychology in Wellness Apps](../../guidelines/color-psychology.md#wellness)
- [♿ Accessibility in Meditation Apps](../../guidelines/accessibility.md#mindfulness)
Last updated: February 2026 • Report Issue
