# Employee CRUD (plain HTML)

A practice exercise: a small employee management UI built with **plain HTML only** —
no JavaScript, no CSS, no inline styles.

| File | Purpose |
| --- | --- |
| `index.html` | Employee table (id, last_name, middle_name, first_name) with an Add button and per-row Update / Delete buttons |
| `add.html` | Form for creating a new employee |
| `edit.html` | Pre-filled form for updating an employee |
| `delete.html` | Delete confirmation page |
| `tests.html` | HTML-only manual test-case checklist |

Navigation is wired with real `<form>` elements using `method="get"`, so every button
works straight from the filesystem — no server needed.

Open it with:

    open index.html
