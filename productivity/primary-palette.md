# 🎨 Productivity App - Primary Palette

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-Productivity-4A5568?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Primary-00A86B?style=flat-square)]()
  [![Focus](https://img.shields.io/badge/Focus-High-FFD700?style=flat-square)]()
  
  ---
  
  | [🏠 Productivity Home](../README.md) | [🌙 Dark Mode](./dark-mode.md) | [💎 Luxury Style](./luxury-style.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 🎨 Color Palette

| Color Name | Hex | HSL | Usage | Preview |
|------------|-----|-----|-------|---------|
| Slate Gray | `#4A5568` | `hsl(218, 18%, 35%)` | Primary UI, headers | ████ |
| Forest Green | `#00A86B` | `hsl(156, 100%, 33%)` | Completed tasks, success | ████ |
| Clean White | `#F8F9FA` | `hsl(210, 17%, 98%)` | Backgrounds, cards | ████ |
| Deep Indigo | `#2C3E50` | `hsl(210, 29%, 24%)` | Text, important items | ████ |
| Vibrant Blue | `#4A90E2` | `hsl(214, 82%, 62%)` | Links, interactive | ████ |
| Soft Coral | `#FF9A8B` | `hsl(8, 100%, 77%)` | Urgent tasks, deadlines | ████ |

## 🧠 Color Psychology

| Color | Emotion | Best Used For |
|-------|---------|---------------|
| **Slate Gray** | Professional, Calm | Headers, navigation |
| **Forest Green** | Growth, Completion | Checkboxes, success |
| **Deep Indigo** | Focus, Importance | Task titles, priorities |
| **Vibrant Blue** | Trust, Action | Links, buttons |
| **Soft Coral** | Urgency, Alert | Deadlines, overdue |

## 💻 Implementation

```css
:root {
  --productivity-primary: #4A5568;
  --productivity-primary-dark: #2D3748;
  --productivity-success: #00A86B;
  --productivity-background: #F8F9FA;
  --productivity-text: #2C3E50;
  --productivity-link: #4A90E2;
  --productivity-urgent: #FF9A8B;
}

.task-item {
  background: white;
  border-radius: 8px;
  padding: 12px 16px;
  margin: 4px 0;
  border-left: 3px solid transparent;
}

.task-item.completed {
  border-left-color: var(--productivity-success);
  opacity: 0.8;
}

.task-item.urgent {
  border-left-color: var(--productivity-urgent);
}

.checkbox {
  width: 20px;
  height: 20px;
  border: 2px solid var(--productivity-primary);
  border-radius: 4px;
  cursor: pointer;
}

.checkbox.checked {
  background: var(--productivity-success);
  border-color: var(--productivity-success);
}
```
## 🔗 Related Links

| Icon | Link | Description |
|:----:|:----|:-----------:|
| 🌙 | [Productivity Dark Mode](./dark-mode.md) | Dark theme variant |
| 💎 | [Productivity Luxury Style](./luxury-style.md) | Premium palette |
| 📱 | [Productivity Examples](./examples/) | Case studies |
| 📝 | [Notion](./examples/notion-example.md) | All-in-one workspace |
| ✅ | [Todoist](./examples/todoist-example.md) | Task management |
| 🚀 | [ClickUp](./examples/clickup-example.md) | Project management |

---

**[⬆ Back to Top](#top)** • **[🏠 Productivity Home](../README.md)**
