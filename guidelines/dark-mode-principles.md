# 🌙 Dark Mode Principles for Healthcare

## Dark Mode Color Adaptations

### Original to Dark Mode Conversion
| Original | Dark Mode | Usage |
|----------|-----------|-------|
| #4ECDC4 | #3A9B94 | Primary (reduced brightness) |
| #2C3E50 | #E0E0E0 | Text (inverted) |
| #FFFFFF | #1A1E2B | Background |
| #FF6B6B | #B84A4A | Alerts (less saturated) |

### Benefits for Healthcare
- Reduced eye strain during night use
- Better sleep hygiene for patients
- 43% battery savings on OLED screens
- Reduced visual fatigue for medical staff

### Implementation Tips
```css
@media (prefers-color-scheme: dark) {
  :root {
    --background: #1A1E2B;
    --text: #E0E0E0;
    --primary: #3A9B94;
    --accent: #B84A4A;
  }
}
