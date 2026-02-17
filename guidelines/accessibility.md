# ♿ Accessibility Guidelines

## WCAG 2.2 Requirements

### Contrast Ratios
| Text Type | Minimum Ratio | Enhanced Ratio |
|-----------|--------------|----------------|
| Normal Text | 4.5:1 | 7:1 |
| Large Text (18pt+) | 3:1 | 4.5:1 |
| UI Components | 3:1 | - |

### Color Blindness Considerations

#### Types of Color Blindness
- **Protanopia** (red-blind): 1% of males
- **Deuteranopia** (green-blind): 6% of males
- **Tritanopia** (blue-blind): 0.01% of population

#### Safe Combinations
✅ **Good combinations:**
- Blue + Orange
- Blue + Yellow
- Purple + Yellow
- Blue + Pink

❌ **Avoid:**
- Red + Green
- Green + Brown
- Blue + Purple
- Green + Blue

### Testing Tools
1. [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/)
2. [Color Oracle](https://colororacle.org/)
3. [Stark Plugin](https://www.getstark.co/)

### Implementation Checklist
- [ ] All text meets 4.5:1 contrast ratio
- [ ] Color is not the only indicator
- [ ] Focus states are visible
- [ ] Tested with grayscale
- [ ] Tested with color blindness simulators
