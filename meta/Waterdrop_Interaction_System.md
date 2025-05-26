# 💧 Waterdrop Interaction System – im1ai.ca

**Symbol:** Waterdrop Logo Mark  
**Last Updated:** 2025-05-25  
**Designer:** Don Way

---

## 🎯 What Is the Waterdrop?

The **Waterdrop logo** is a floating, circular UI element designed as the **universal interaction control point** across the im1ai.ca platform.

> 💧 It represents purity, access, and simplicity — one drop, one interaction, many worlds.

The Waterdrop is meant to:
- Replace traditional menu bars
- Float independently across pages
- Control contextual actions and page-specific features

---

## ✅ Functional Roles

| Page         | Waterdrop Role                            | Status |
|--------------|-------------------------------------------|--------|
| StudyRoom    | Opens note-writing, file upload menu      | ✅ Demo active |
| VisitRoom    | Will offer AI Chat, Share Link, Bookmark  | 🔜 Not yet implemented |
| EntrancePage | Will act as portal selector, view control | 🔜 Not yet implemented |

---

## 🧩 Components It Will Trigger

- 📄 **Open PromptBox**
- 📁 **Drag-and-drop file embedding**
- ✍️ **Write Diary Entry**
- 🔗 **Get Shareable World Link**
- 💬 **Chat with AI (Contextual)**

---

## 🖼 UI & Positioning

- Appears **bottom-right corner** (floating)
- Resembles a water droplet (circular + ripple on hover)
- Click → expands radial menu
- Collapses into a single dot when idle

---

## 🔮 Development Notes

- React component will live in:
  - `/commonshare/shared-ui/WaterdropButton.js`
- Controlled using:
  - `position: fixed; bottom: 20px; right: 20px;`
  - Radial expansion via CSS/JS animations

---

## 🛠 Current Implementation

- ✅ **StudyRoom Demo** has basic Waterdrop with popup menu
- ❌ **VisitRoom** and **EntrancePage** still use default buttons
- 🚧 Planned update: apply consistent Waterdrop pattern across all modules

---

## 📌 Design Philosophy

The Waterdrop is not just a button — it is the **symbol of modular AI access**:

- **One user → One AI → One drop opens it**
- It makes interaction feel **natural, centered, portable**
- Future version may support **custom actions per user or module**

---

## 🔄 Update Log

| Date       | Change                                           |
|------------|--------------------------------------------------|
| 2025-05-25 | Created Waterdrop component doc and future plan |

---
