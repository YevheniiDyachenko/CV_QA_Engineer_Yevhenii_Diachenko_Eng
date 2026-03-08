## 2025-05-14 - [Interactive element accessibility]
**Learning:** Using non-semantic elements like `<i>` or `<div>` for interactive components (buttons, toggles) without proper ARIA roles, `tabindex`, and keyboard event listeners makes them inaccessible to screen readers and keyboard-only users.
**Action:** Always ensure non-semantic interactive elements have `role="button"`, `tabindex="0"`, an appropriate `aria-label`, and handle both `click` and `keydown` (Enter/Space) events.
