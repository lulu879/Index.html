
 ✅ Todo Item Card — Stage 1a

An advanced, interactive, and fully stateful **Todo / Task Card** component built with semantic HTML, CSS, and vanilla JavaScript.

Built as part of the **Frontend Wizards Internship Program — Stage 1a Task** (upgrade from Stage 0).

---

 🔗 Live Demo
https://index-html2-git-main-lulu879s-projects.vercel.app/


---

✨ What's New in Stage 1a (vs Stage 0)

| Feature | Stage 0 | Stage 1a |
|---|---|---|
| Edit mode | ❌ | ✅ Full edit form with save/cancel |
| Status control | Display only | ✅ Interactive dropdown |
| Priority indicator | Badge only | ✅ Badge + left border accent |
| Expand/collapse | ❌ | ✅ Collapsible long description |
| Overdue indicator | ❌ | ✅ Visual badge + red accent |
| Time granularity | Days only | ✅ Minutes, hours, days |
| Time updates | 60s | ✅ Every 30s, stops when Done |
| State sync | Basic | ✅ Checkbox ↔ Status ↔ Dropdown fully synced |
| Focus management | Basic | ✅ Returns focus to Edit btn on close |
| Keyboard flow | Tab order | ✅ Checkbox → Status → Expand → Edit → Delete |

---

 🧪 All Testable Elements

Stage 0 (preserved)
| Element | `data-testid` |
|---|---|
| Card container | `test-todo-card` |
| Task title | `test-todo-title` |
| Description | `test-todo-description` |
| Priority badge | `test-todo-priority` |
| Due date | `test-todo-due-date` |
| Time remaining | `test-todo-time-remaining` |
| Status badge | `test-todo-status` |
| Checkbox toggle | `test-todo-complete-toggle` |
| Tags list | `test-todo-tags` |
| Edit button | `test-todo-edit-button` |
| Delete button | `test-todo-delete-button` |

 Stage 1a (new)
| Element | `data-testid` |
|---|---|
| Edit form | `test-todo-edit-form` |
| Title input | `test-todo-edit-title-input` |
| Description textarea | `test-todo-edit-description-input` |
| Priority select | `test-todo-edit-priority-select` |
| Due date input | `test-todo-edit-due-date-input` |
| Save button | `test-todo-save-button` |
| Cancel button | `test-todo-cancel-button` |
| Status control | `test-todo-status-control` |
| Priority indicator | `test-todo-priority-indicator` |
| Expand toggle | `test-todo-expand-toggle` |
| Collapsible section | `test-todo-collapsible-section` |
| Overdue indicator | `test-todo-overdue-indicator` |

---

 🎨 Design Decisions

- **Priority indicator**: Left border accent — subtle yet immediately visible at a glance
- **Edit form**: Slides in below the card body rather than replacing it — preserves context
- **Status sync**: Three-way sync between checkbox, status badge, and status dropdown — no state drift
- **Overdue logic**: Overdue indicator only shows when `status !== 'Done'` — completed tasks don't show overdue
- **Expand/collapse**: Smooth CSS `max-height` transition — no layout jump

---

 ♿ Accessibility Notes

- All form fields have `<label for="">` associations
- Status dropdown has `aria-labelledby`
- Expand toggle uses `aria-expanded` + `aria-controls`
- Collapsible section has matching `id` and `role="region"`
- Time remaining uses `aria-live="polite"` + `aria-atomic="true"`
- Edit form closes on `Escape` key
- Focus returns to Edit button when form is closed
- Keyboard flow: `Tab → Checkbox → Status → Expand → Edit → Delete → (Save/Cancel in edit mode)`

---

 ⚠️ Known Limitations

- Edit form does not trap focus (bonus feature — not required for Stage 1a)
- Tags are hardcoded (not editable in the form)
- Delete is a dummy action (`alert`)
- Single card only — not a full list/app

---

 🛠️ Built With

- HTML5 semantic elements (`article`, `h2`, `time`, `ul`, `button`, `select`, `form`)
- CSS3 (custom properties, flexbox, CSS transitions, `max-height` animation)
- Vanilla JavaScript (state object, DOM manipulation, `Date` API, `setInterval`)

---

```

No build tools or dependencies required.



---

## 👤 Author
https://github.com/lulu879/Index.html

