# 💎 Health App - Luxury Style

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-Health-4ECDC4?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Luxury-D4AF37?style=flat-square)]()
  [![Premium](https://img.shields.io/badge/Premium-Executive-6C5CE7?style=flat-square)]()
  
  ---
  
  | [🏠 Health Home](../README.md) | [🎨 Primary](./primary-palette.md) | [🌙 Dark](./dark-mode.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 💎 Luxury Palette

| Color Name | Hex | Usage | Preview |
|------------|-----|-------|---------|
| Deep Plum Noir | `#2D1B3C` | Primary background | ████ |
| Liquid Gold | `#D4AF37` | Accents, premium badges | ████ |
| Icy Blue | `#A5D8FF` | Interactive elements | ████ |
| Charcoal | `#2A2A2A` | Secondary backgrounds | ████ |
| Crystal | `#E8EFF9` | Text, icons | ████ |
| Rose Gold | `#B76E79` | Premium highlights | ████ |
| Platinum | `#E5E4E2` | Borders, dividers | ████ |

## 🧠 Why This Palette Works

### Target Audience
- **Executive Health Programs**: C-suite executives valuing privacy and premium service
- **Concierge Medicine**: High-net-worth individuals seeking personalized care
- **Wellness Retreats**: Luxury spa and wellness destinations
- **Genetic Testing**: Premium DNA analysis services
- **Anti-Aging Clinics**: Exclusive longevity treatments

### Emotional Response
| Color | Emotion | Association |
|-------|---------|-------------|
| Plum Noir | Sophistication, Mystery | Luxury, Exclusivity |
| Gold | Wealth, Success | Premium, Quality |
| Icy Blue | Innovation, Purity | Advanced technology |
| Crystal | Clarity, Precision | Medical accuracy |
| Rose Gold | Elegance, Warmth | High-end service |

## 💎 Luxury Design Elements

### Glassmorphism
```css
.luxury-card {
  background: rgba(45, 27, 60, 0.7);
  backdrop-filter: blur(10px);
  -webkit-backdrop-filter: blur(10px);
  border: 1px solid rgba(212, 175, 55, 0.3);
  border-radius: 24px;
  box-shadow: 0 20px 40px rgba(0, 0, 0, 0.4),
              0 0 0 2px rgba(212, 175, 55, 0.1) inset;
}

.premium-badge {
  background: linear-gradient(135deg, #D4AF37 0%, #F5D742 100%);
  color: #2D1B3C;
  padding: 8px 16px;
  border-radius: 40px;
  font-weight: bold;
  text-transform: uppercase;
  letter-spacing: 2px;
  box-shadow: 0 4px 15px rgba(212, 175, 55, 0.4);
}

.interactive-element {
  background: linear-gradient(135deg, #A5D8FF 0%, #7BC5FF 100%);
  color: #2D1B3C;
  transition: all 0.3s ease;
}

.interactive-element:hover {
  transform: translateY(-2px);
  box-shadow: 0 10px 25px rgba(165, 216, 255, 0.4);
}
```
## Full Page Example

```css
.luxury-health-app {
  background: linear-gradient(135deg, #2D1B3C 0%, #1A1023 100%);
  min-height: 100vh;
  color: #E8EFF9;
  font-family: 'Playfair Display', 'Times New Roman', serif;
}

.luxury-header {
  border-bottom: 1px solid rgba(212, 175, 55, 0.3);
  padding: 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.luxury-logo {
  font-size: 24px;
  font-weight: 300;
  letter-spacing: 4px;
  color: #D4AF37;
  text-transform: uppercase;
}

.luxury-nav a {
  color: #E8EFF9;
  text-decoration: none;
  margin-left: 30px;
  font-size: 14px;
  letter-spacing: 1px;
  transition: color 0.3s;
}

.luxury-nav a:hover {
  color: #D4AF37;
}

.luxury-hero {
  padding: 60px 40px;
  text-align: center;
}

.luxury-hero h1 {
  font-size: 48px;
  font-weight: 300;
  color: #E8EFF9;
  margin-bottom: 20px;
}

.luxury-hero .highlight {
  color: #D4AF37;
  font-weight: 400;
}

.luxury-hero p {
  font-size: 18px;
  color: #A5D8FF;
  max-width: 600px;
  margin: 0 auto;
  line-height: 1.6;
}

.luxury-button {
  background: transparent;
  border: 2px solid #D4AF37;
  color: #D4AF37;
  padding: 15px 40px;
  font-size: 16px;
  letter-spacing: 2px;
  text-transform: uppercase;
  cursor: pointer;
  transition: all 0.3s;
  margin-top: 40px;
}

.luxury-button:hover {
  background: #D4AF37;
  color: #2D1B3C;
  box-shadow: 0 10px 30px rgba(212, 175, 55, 0.3);
}

.luxury-card-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 30px;
  padding: 40px;
}

.luxury-metric-card {
  background: rgba(255, 255, 255, 0.05);
  backdrop-filter: blur(10px);
  border: 1px solid rgba(212, 175, 55, 0.2);
  border-radius: 20px;
  padding: 30px;
  transition: transform 0.3s;
}

.luxury-metric-card:hover {
  transform: translateY(-5px);
  border-color: rgba(212, 175, 55, 0.5);
  box-shadow: 0 20px 40px rgba(0, 0, 0, 0.3);
}

.metric-title {
  color: #A5D8FF;
  font-size: 14px;
  letter-spacing: 1px;
  text-transform: uppercase;
  margin-bottom: 10px;
}

.metric-value {
  color: #D4AF37;
  font-size: 36px;
  font-weight: 300;
  margin-bottom: 5px;
}

.metric-unit {
  color: #E8EFF9;
  font-size: 14px;
  opacity: 0.7;
}

.gold-divider {
  height: 1px;
  background: linear-gradient(90deg, 
    rgba(212, 175, 55, 0) 0%,
    rgba(212, 175, 55, 0.5) 50%,
    rgba(212, 175, 55, 0) 100%
  );
  margin: 30px 0;
}
```
## React Native with Animations

```jsx
// LuxuryHealthCard.js
import React from 'react';
import { View, Text, StyleSheet, Animated } from 'react-native';
import LinearGradient from 'react-native-linear-gradient';

const LuxuryHealthCard = ({ title, value, isPremium }) => {
  const scaleValue = new Animated.Value(1);
  
  const handlePress = () => {
    Animated.spring(scaleValue, {
      toValue: 0.98,
      useNativeDriver: true,
    }).start(() => {
      Animated.spring(scaleValue, {
        toValue: 1,
        useNativeDriver: true,
      }).start();
    });
  };

  return (
    <Animated.View 
      style={[styles.card, { transform: [{ scale: scaleValue }] }]}
      onTouchStart={handlePress}
    >
      <LinearGradient
        colors={['rgba(45,27,60,0.9)', 'rgba(26,16,35,0.95)']}
        style={styles.gradient}
      >
        {isPremium && (
          <View style={styles.premiumBadge}>
            <Text style={styles.premiumText}>PREMIUM</Text>
          </View>
        )}
        <Text style={styles.title}>{title}</Text>
        <Text style={styles.value}>{value}</Text>
        <View style={styles.goldAccent} />
      </LinearGradient>
    </Animated.View>
  );
};

const styles = StyleSheet.create({
  card: {
    borderRadius: 24,
    overflow: 'hidden',
    marginVertical: 8,
    marginHorizontal: 16,
    shadowColor: '#D4AF37',
    shadowOffset: { width: 0, height: 4 },
    shadowOpacity: 0.3,
    shadowRadius: 12,
    elevation: 8,
  },
  gradient: {
    padding: 20,
    borderWidth: 1,
    borderColor: 'rgba(212,175,55,0.3)',
  },
  premiumBadge: {
    position: 'absolute',
    top: 12,
    right: 12,
    backgroundColor: '#D4AF37',
    paddingHorizontal: 12,
    paddingVertical: 4,
    borderRadius: 20,
  },
  premiumText: {
    color: '#2D1B3C',
    fontSize: 12,
    fontWeight: 'bold',
    letterSpacing: 1,
  },
  title: {
    color: '#E8EFF9',
    fontSize: 18,
    marginBottom: 8,
    fontFamily: 'PlayfairDisplay-Regular',
  },
  value: {
    color: '#D4AF37',
    fontSize: 32,
    fontWeight: '300',
  },
  goldAccent: {
    position: 'absolute',
    bottom: 0,
    left: 0,
    right: 0,
    height: 2,
    backgroundColor: '#D4AF37',
    opacity: 0.5,
  },
});

export default LuxuryHealthCard;
```
## SwiftUI Implementation

```swift
import SwiftUI

struct LuxuryHealthTheme {
    static let plum = Color(hex: "2D1B3C")
    static let gold = Color(hex: "D4AF37")
    static let icyBlue = Color(hex: "A5D8FF")
    static let crystal = Color(hex: "E8EFF9")
    static let roseGold = Color(hex: "B76E79")
}

struct LuxuryHealthCard: View {
    let title: String
    let value: String
    let isPremium: Bool
    
    var body: some View {
        ZStack {
            // Background with glass morphism
            RoundedRectangle(cornerRadius: 24)
                .fill(LuxuryHealthTheme.plum.opacity(0.7))
                .background(.ultraThinMaterial)
                .overlay(
                    RoundedRectangle(cornerRadius: 24)
                        .stroke(LuxuryHealthTheme.gold.opacity(0.3), lineWidth: 1)
                )
            
            VStack(alignment: .leading, spacing: 12) {
                if isPremium {
                    HStack {
                        Spacer()
                        Text("PREMIUM")
                            .font(.caption)
                            .fontWeight(.bold)
                            .foregroundColor(LuxuryHealthTheme.plum)
                            .padding(.horizontal, 12)
                            .padding(.vertical, 4)
                            .background(LuxuryHealthTheme.gold)
                            .cornerRadius(20)
                    }
                }
                
                Text(title)
                    .font(.headline)
                    .foregroundColor(LuxuryHealthTheme.crystal)
                
                Text(value)
                    .font(.system(size: 36, weight: .light))
                    .foregroundColor(LuxuryHealthTheme.gold)
            }
            .padding(20)
        }
        .frame(height: 150)
        .shadow(color: LuxuryHealthTheme.gold.opacity(0.3), radius: 10, x: 0, y: 5)
    }
}
```
## 🔗 Related Links

| Icon | Link | Description |
|:----:|:----|:-----------:|
| 🎨 | [Health Primary Palette](./primary-palette.md) | Main color scheme |
| 🌙 | [Health Dark Mode](./dark-mode.md) | Dark theme variant |
| 📱 | [Health Examples](./examples/) | Case studies directory |
| 🧘 | [Headspace Case Study](./examples/headspace-example.md) | Meditation app analysis |
| 🏥 | [MyChart Case Study](./examples/mychart-example.md) | Patient portal analysis |
| 🔴 | [Clue Case Study](./examples/clue-example.md) | Period tracker analysis |

---

**[⬆ Back to Top](#top)** • **[🏠 Back to Health](../README.md)** • **[📚 Main README](../../README.md)**
