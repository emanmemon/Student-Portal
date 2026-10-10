# Smart Campus Student Portal

A clean, responsive front-end prototype for a university student portal. It brings courses, class schedules, assignments, announcements, and student profile information together in one place.

## Overview

The **Smart Campus Student Portal** is a Web Technology course project built with **HTML5, CSS3, and vanilla JavaScript**. It is a front-end prototype, so it does not require a build process or a backend server for basic local use.

### Main features

- **Home page** — welcome section, next-class preview, announcements, quick links, and upcoming events.
- **Student dashboard** — a quick overview of academic information.
- **Courses** — browse course cards and filter by course name, semester, or status.
- **Weekly schedule** — view class timings and rooms, with a day filter and a mobile-friendly layout.
- **Task manager** — add tasks, mark them complete, delete them, and filter the list. Tasks are saved in browser `localStorage`.
- **Announcements** — browse notices by category.
- **Student profile** — enter student details with inline form validation and password-strength feedback.
- **Light and dark themes** — switch themes, with the selected preference saved in the browser.

## Project structure

The site expects the following files and folders to be kept in their relative locations:

```text
project-folder/
├── index.html
├── dashboard.html
├── courses.html
├── schedule.html
├── tasks.html
├── announcements.html
├── profile.html
├── css/
│   └── style.css
├── js/
│   ├── theme.js
│   ├── data.js
│   ├── main.js
│   ├── home.js
│   ├── dashboard.js
│   ├── courses.js
│   ├── schedule.js
│   ├── tasks.js
│   ├── announcements.js
│   └── profile.js
└── images/
    └── favicon.svg
```

> Keep the existing file and folder names unchanged unless you also update the corresponding references in the HTML.

## Requirements

- A modern web browser (Chrome, Edge, Firefox, or Safari).
- The HTML, CSS, JavaScript, and image files referenced by each page.
- Internet access is only needed to load the Google Fonts linked from the home page; fallback fonts are used if they are unavailable.

## Getting started

1. Place the project files in the structure shown above.
2. Open `index.html` in a modern browser.
3. Use the navigation menu to explore the pages.
4. Try the theme toggle, course filters, schedule day filter, task manager, announcements filters, and profile form.

No package installation or compilation step is required for the basic prototype.

## How data is handled

The prototype uses JavaScript to display sample academic information. Browser `localStorage` is used for selected preferences and user-entered data:

- `scp.theme` — saved theme preference.
- `scp.tasks` — task-manager entries.
- `scp.profile` — student profile data.

**Privacy note:** The profile password is not stored in `localStorage`. This is a front-end demonstration only; do not enter real passwords or sensitive personal information. Data saved in `localStorage` stays in that browser on that device and is not automatically synchronized to other devices.

## Limitations

- This is a **front-end prototype**, not a complete production student information system.
- No backend database or server-side authentication is described by the supplied project files.
- The contact details and academic information shown in the interface should be treated as demonstration content unless replaced with verified university information.
- Data saved in `localStorage` is browser- and device-specific.

## Troubleshooting

- **A page looks unstyled:** check that `css/style.css` exists at the expected path.
- **Buttons or dynamic content do not work:** check that the referenced files in `js/` exist and that their filenames match the HTML script references.
- **The favicon is missing:** check that `images/favicon.svg` exists.
- **Fonts do not load:** check your internet connection; fallback fonts may be used.
- **Saved tasks or theme seem missing:** open the project in the same browser and device where the data was saved. Clearing browser data may remove it.

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- Browser `localStorage`
- Google Fonts (optional external font loading)

## Academic use

This project is intended as a learning prototype for a Web Technology course. 
