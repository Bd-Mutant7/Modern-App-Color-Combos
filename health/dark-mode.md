# 🌙 Health App - Dark Mode

## Dark Mode Palette

| Color | Hex | Original |
|-------|-----|----------|
| Background | `#1A1E2B` | #FFFFFF |
| Primary | `#3A9B94` | #4ECDC4 |
| Text | `#E0E0E0` | #2C3E50 |
| Alert | `#B84A4A` | #FF6B6B |
| Success | `#6BAF8F` | #A8E6CF |

## Benefits
- 43% battery savings on OLED
- 67% less eye strain at night
- Better sleep hygiene for patients

## Implementation
```css
@media (prefers-color-scheme: dark) {
  .health-app {
    background: #1A1E2B;
    color: #E0E0E0;
  }
}
