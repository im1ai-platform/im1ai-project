# 📦 CommonShare – Shared Logic & Components

**Folder:** commonshare/  
**Last Updated:** 2025-05-25  
**Maintainer:** Don Way  

---

## 🎯 Purpose

The `commonshare/` folder contains reusable logic, UI components, and configuration shared across all core modules of the im1ai.ca platform (EntrancePage, VisitRoom, StudyRoom, ThoughtLens).

This structure enables modular design, consistent behavior, and centralized updates.

---

## 📁 Subfolders

| Subfolder       | Purpose                                                   |
|------------------|-----------------------------------------------------------|
| `auth-lib/`       | Login hooks, Firebase integration, access control logic |
| `config-lib/`     | OpenAI API keys, base model names, app-wide constants   |
| `navigation-lib/` | Hooks and helpers for routing or tab switching          |
| `shared-ui/`      | Universal UI elements like `WaterdropButton`            |

---

## 🧩 Example Usage

Each module imports from `commonshare/` like this:

```js
import { useAuth } from '../../commonshare/auth-lib/useAuth';
import WaterdropButton from '../../commonshare/shared-ui/WaterdropButton';
import openaiConfig from '../../commonshare/config-lib/openaiConfig';
