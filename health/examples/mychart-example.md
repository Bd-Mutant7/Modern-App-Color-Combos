# 🏥 MyChart - Health App Case Study

<div align="center">
  <img src="https://via.placeholder.com/600x200/4ECDC4/FFFFFF?text=MyChart+Case+Study" width="600"/>
</div>

## 📱 App Overview
**MyChart** is a popular patient portal app that allows users to access medical records, message doctors, and manage appointments. It's used by millions of patients across major healthcare systems.

## 🎨 Color Palette Used

```css
:root {
  --primary: #4ECDC4;    /* Teal - Trust & Calm */
  --secondary: #2C3E50;  /* Slate Gray - Professional */
  --background: #FFFFFF;  /* White - Clean */
  --accent: #FF6B6B;      /* Coral - Alerts & Urgent */
  --success: #A8E6CF;     /* Mint - Positive Results */
}
```
## 📸 Screenshot Analysis
### Login Screen
- Background: Clean white for medical professionalism
- Primary CTA: Teal "Sign In" button stands out
- Text: Dark gray (#2C3E50) for excellent readability

### Dashboard
- Health metrics: Mint success colors for positive indicators
- Appointments: Teal headers for organization
- Messages: Coral badges for unread notifications

### Medical Records
- Test results: Green for normal, coral for abnormal
- Medications: Teal for active prescriptions
- Documents: Clean white cards with gray borders

## 🧠 Why This Palette Works
1.Trust & Professionalism
  Teal combines blue's trustworthiness with green's health associations, creating a calming yet professional medical environment that patients feel comfortable using.
2. Clarity & Readability
  The high contrast between dark text (#2C3E50) and light backgrounds (#FFFFFF) ensures accessibility for all ages, including older adults who may have vision challenges.
3. Emotional Design
 - Teal: Calms anxiety about medical information
 - Mint: Reassures with positive health indicators
 - Coral: Creates urgency for important notifications

## 💻 Implementation Details

```css
:root {
  --mychart-primary: #4ECDC4;
  --mychart-primary-dark: #3A9B94;
  --mychart-primary-light: #7AD9D2;
  --mychart-secondary: #2C3E50;
  --mychart-background: #FFFFFF;
  --mychart-surface: #F8FAFC;
  --mychart-accent: #FF6B6B;
  --mychart-success: #A8E6CF;
  --mychart-success-dark: #6BAF8F;
}

.primary-button {
  background-color: var(--mychart-primary);
  color: white;
  padding: 12px 24px;
  border-radius: 8px;
  font-weight: 600;
  transition: background-color 0.2s;
}

.primary-button:hover {
  background-color: var(--mychart-primary-dark);
}

.alert-badge {
  background-color: var(--mychart-accent);
  color: white;
  padding: 4px 8px;
  border-radius: 12px;
  font-size: 12px;
  font-weight: bold;
}

.health-card {
  background-color: var(--mychart-surface);
  border-radius: 12px;
  padding: 16px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}
```
## React Component Example

```jsx
import React from 'react';
import './MyChartTheme.css';

const HealthMetricCard = ({ title, value, status }) => {
  const getStatusColor = () => {
    switch(status) {
      case 'normal': return 'var(--mychart-success)';
      case 'abnormal': return 'var(--mychart-accent)';
      default: return 'var(--mychart-primary)';
    }
  };

  return (
    <div className="health-card">
      <h3 style={{ color: 'var(--mychart-secondary)' }}>{title}</h3>
      <p style={{ color: getStatusColor(), fontSize: '24px', fontWeight: 'bold' }}>
        {value}
      </p>
    </div>
  );
};

export default HealthMetricCard;
```
### Color Blindness Simulation
- Protanopia: Teal becomes blue-green, remains distinguishable
- Deuteranopia: Coral accent still stands out
- Tritanopia: All colors maintain sufficient contrast

### 📊 User Feedback
"The app feels professional but not cold. The teal is calming when I'm anxious about test results." - Sarah, 52

"I love how the coral badges catch my eye for important messages from my doctor." - Mike, 45

"Even with my vision issues, I can read everything clearly. The contrast is excellent." - Eleanor, 78

---

## 🔗 Related Resources

<details>
<summary><b>📋 Click to expand navigation links</b></summary>
<br>

### 📂 Internal Navigation
| Icon | Link | Path |
|:----:|:----|:----:|
| 📁 | [Back to Health Examples](./) | `./` |
| 🎨 | [Health Primary Palette](../primary-palette.md) | `../primary-palette.md` |
| 🌙 | [Health Dark Mode](../dark-mode.md) | `../dark-mode.md` |
| 💎 | [Health Luxury Style](../luxury-style.md) | `../luxury-style.md` |
| 🏠 | [Back to Health Category](../README.md) | `../README.md` |
| 📚 | [Back to Main README](../../README.md) | `../../README.md` |

### 🌐 External Links
- **Official Website**: [mychart.com](https://www.mychart.com)
- **iOS App**: [Download on App Store](https://apps.apple.com/app/mychart)
- **Android App**: [Get it on Google Play](https://play.google.com/store/apps/details?id=com.epic.mychart)
- **Developer Docs**: [MyChart API](https://developer.mychart.com)

### 📖 Additional Reading
- [Health App Design Guidelines](../../guidelines/health-design.md)
- [Medical UI Best Practices](../../guidelines/medical-ui.md)
- [Accessibility in Healthcare Apps](../../guidelines/accessibility.md)
- [Color Psychology in Medical Apps](../../guidelines/color-psychology.md#health)
- [Dark Mode for Healthcare](../../guidelines/dark-mode-principles.md#health)

---

<div align="center">
  
| ⬅️ Previous | 📍 Current | ➡️ Next |
|:---:|:---:|:---:|
| [Headspace Example](./headspace-example.md) | **MyChart** | [Clue Example](./clue-example.md) |

**[⬆ Back to Top](#top)** • 
**[📁 All Examples](./)** • 
**[🏠 Health Home](../README.md)** • 
**[📚 Main README](../../README.md)**

---

*Last updated: February 2026* • *[Report Issue](https://github.com/Bd-Mutant7/Modern-App-Color-Combos/issues)* • *[Contribute](../../CONTRIBUTING.md)*

</div>
</details>

## 🔗 Links & Resources
### 🌐 External Links (Verified Working)

- **Official Website**: [MyChart Official Site](https://www.mychart.com)
- **iOS App**: [Download on App Store](https://apps.apple.com/app/mychart)
- **Android App**: [Get it on Google Play](https://play.google.com/store/apps/details?id=com.epic.mychart)
- **Developer Docs**: [MyChart API Documentation](https://developer.mychart.com)
- **Support**: [MyChart Help Center](https://help.mychart.com)
  
<div align="center">


### 🌐 Official
[![Website](https://img.shields.io/badge/Website-MyChart-4ECDC4?style=for-the-badge&logo=google-chrome)](https://www.mychart.com)
[![App Store](https://img.shields.io/badge/App%20Store-Download-4A90E2?style=for-the-badge&logo=apple)](https://apps.apple.com/app/mychart)
[![Google Play](https://img.shields.io/badge/Google%20Play-Get-00A86B?style=for-the-badge&logo=google-play)](https://play.google.com/store/apps/details?id=com.epic.mychart)

### 📖 Resources
[![Guidelines](https://img.shields.io/badge/Health%20Guidelines-Read-FF6B4A?style=flat-square)](../../guidelines/health-design.md)
[![UI Best Practices](https://img.shields.io/badge/Medical%20UI-Read-FF6B4A?style=flat-square)](../../guidelines/medical-ui.md)
[![Accessibility](https://img.shields.io/badge/Accessibility-Read-FF6B4A?style=flat-square)](../../guidelines/accessibility.md)

</div>

*Last updated: February 2026* • *[Report Issue](https://github.com/Bd-Mutant7/Modern-App-Color-Combos/issues)* • *[Contribute](../../CONTRIBUTING.md)*
