# 🌙 Messaging App - Dark Mode

<div align="center">
  
  [![Category](https://img.shields.io/badge/Category-Messaging-4A90E2?style=flat-square)](../)
  [![Type](https://img.shields.io/badge/Type-Dark%20Mode-1A1E2B?style=flat-square)]()
  [![Night](https://img.shields.io/badge/Night-Chatting-00A86B?style=flat-square)]()
  
  ---
  
  | [🏠 Messaging Home](../README.md) | [🎨 Primary](./primary-palette.md) | [💎 Luxury](./luxury-style.md) | [📱 Examples](./examples/) |
  |:---:|:---:|:---:|:---:|
  
</div>

## 🌙 Dark Mode Palette

| Color | Hex | Original | Usage | Preview |
|-------|-----|----------|-------|---------|
| Dark Navy | `#1A1E2B` | #FFFFFF | Background | ████ |
| Surface Dark | `#252A3A` | #F0F2F5 | Received messages | ████ |
| Soft Blue | `#6A9AE5` | #4A90E2 | Sent messages | ████ |
| Muted Green | `#2A6A4A` | #00A86B | Online status | ████ |
| Light Text | `#E0E0E0` | #2C3E50 | Text | ████ |
| Dim Coral | `#B84A3A` | #FF6B4A | Unread badges | ████ |

## 🧠 Benefits for Messaging Apps

- **Comfortable** late-night chatting
- **Reduced eye strain** in dark rooms
- **Battery saving** on OLED screens
- **Better focus** on conversations
- **Modern, sleek appearance**

## 💻 Implementation

```css
@media (prefers-color-scheme: dark) {
  :root {
    --background: #1A1E2B;
    --received: #252A3A;
    --sent: #6A9AE5;
    --success: #2A6A4A;
    --text: #E0E0E0;
    --unread: #B84A3A;
  }
}

.night-mode .chat-bubble-sent {
  background: var(--sent);
}

.night-mode .chat-bubble-received {
  background: var(--received);
  color: var(--text);
}
```
## 🔗 Related Links

| Icon | Link | Description |
|:----:|:----|:-----------:|
| 🎨 | [Messaging Primary Palette](./primary-palette.md) | Main color scheme |
| 💎 | [Messaging Luxury Style](./luxury-style.md) | Premium palette |
| 📱 | [Messaging Examples](./examples/) | Case studies |

---

**[⬆ Back to Top](#top)** • **[🏠 Messaging Home](../README.md)**
