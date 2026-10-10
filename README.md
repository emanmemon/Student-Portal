# Smart Campus Student Portal

Front-end prototype built with HTML5, CSS3 and vanilla JavaScript. No build step: open `index.html` in a modern browser.

## Pages
| File | Purpose |
|---|---|
| index.html | Landing page: hero, next class, announcements, quick access, events |
| dashboard.html | Academic overview calculated by JavaScript |
| courses.html | Dynamic course cards with search and semester/status filters |
| schedule.html | Weekly timetable (turns into cards on phones) with day filter |
| tasks.html | Task manager: add, complete, delete, filter, saved in localStorage |
| announcements.html | Announcements filtered by category |
| profile.html | Registration form with inline validation and password strength |

## JavaScript files
- `theme.js` applies the saved theme before first paint
- `data.js` arrays of courses, schedule, announcements and events
- `main.js` shared helpers, navigation, theme toggle, toasts, task storage
- one script per page (`home`, `dashboard`, `courses`, `schedule`, `tasks`, `announcements`, `profile`)

## localStorage keys
`scp.theme`, `scp.tasks`, `scp.profile` (the password is never stored).
