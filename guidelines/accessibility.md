# ♿ Accessibility Guidelines for Healthcare Apps

## WCAG 2.2 Requirements

### Contrast Ratios
| Element | Minimum | Enhanced |
|---------|---------|----------|
| Normal Text | 4.5:1 | 7:1 |
| Large Text (18pt+) | 3:1 | 4.5:1 |
| UI Components | 3:1 | - |

### Color Blind Safe Combinations
✅ **Safe Pairs:**
- Blue (#4A90E2) + Orange (#FF6B4A)
- Purple (#6C5CE7) + Yellow (#BFFF00)
- Teal (#4ECDC4) + Coral (#FF6B6B)

❌ **Avoid:**
- Red + Green
- Green + Brown
- Blue + Purple

### Screen Reader Support
- All images need alt text
- Forms need proper labels
- Headers must be hierarchical (H1, H2, H3)
- Buttons need descriptive text

### Touch Targets
- Minimum size: 44x44px
- Adequate spacing between buttons
- No overlapping touch targets
- Easy to reach (thumb zone)


### Focus Indicators
- Visible focus states
- Keyboard navigable
- Skip navigation links
- Logical tab order
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
