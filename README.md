

# ✅ Todo Item Card — Stage 0

A clean, accessible, and testable **Todo / Task Card** component built with semantic HTML, CSS, and vanilla JavaScript.

Built as part of the **Frontend Wizards Internship Program — Stage 0 Task**.

---



---

## 📸 Preview

> *(Add a screenshot here after deployment)*

---

## ✨ Features

- ✅ All required `data-testid` attributes for automated testing
- ♿ Fully accessible — keyboard navigable, ARIA labels, `aria-live` region
- 📱 Responsive from 320px to 1200px (mobile-first)
- ⏱️ Dynamic time remaining — calculates and updates every 60 seconds
- ☑️ Checkbox toggle — strikes through title and updates status to "Done"
- 🏷️ Priority badge (Low / Medium / High) and status indicator
- 🎨 Dark theme with modern card UI

---

## 🧪 Testable Elements

| Element | `data-testid` |
|---|---|
| Card container | `test-todo-card` |
| Task title | `test-todo-title` |
| Description | `test-todo-description` |
| Priority badge | `test-todo-priority` |
| Due date | `test-todo-due-date` |
| Time remaining | `test-todo-time-remaining` |
| Status indicator | `test-todo-status` |
| Checkbox toggle | `test-todo-complete-toggle` |
| Tags list | `test-todo-tags` |
| Edit button | `test-todo-edit-button` |
| Delete button | `test-todo-delete-button` |

---

## 🛠️ Built With

- HTML5 (semantic elements: `article`, `h2`, `time`, `ul`, `button`)
- CSS3 (custom properties, flexbox, responsive design)
- Vanilla JavaScript (DOM manipulation, `Date` API, `setInterval`)

---

## ♿ Accessibility

- Checkbox has visible label + `aria-label`
- All buttons have accessible names
- Time remaining wrapped in `aria-live="polite"`
- Visible focus styles on all interactive elements
- WCAG AA color contrast compliant
- Fully keyboard navigable: `Tab → Checkbox → Edit → Delete`

---

## 🚀 Getting Started

No build tools or dependencies required. Just open the file:

```bash
# Clone the repo
git clone https://github.com/your-username/todo-card-stage-0.git

# Open in browser
open index.html
```

---

## 📁 Project Structure

```
todo-card-stage-0/
├── index.html      # All-in-one component (HTML + CSS + JS)
└── README.md
```

---

## 👤 Author

**Your Name**
- GitHub: 

README.md
Displaying README.md.
