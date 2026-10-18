# TuteDude MERN Stack – Task 7: CSS Responsive Issues (Media Queries, Variables)

## Files Included
- `index.html` — HTML structure
- `style.css` — CSS with Flexbox, Media Queries, and CSS Variables
- `README.md` — This file

## How to Run
1. Unzip the folder.
2. Open `index.html` in Chrome or Firefox.
3. Use DevTools (F12 → Toggle Device Toolbar) to test Tablet and Mobile views.

## Responsive Breakpoints

| View    | Width       | Behaviour                                              |
|---------|-------------|--------------------------------------------------------|
| Desktop | > 768px     | Full navbar with links, hero in row layout             |
| Tablet  | ≤ 768px     | Smaller navbar text, smaller hero text and image       |
| Mobile  | ≤ 480px     | Nav links hidden, hero switches to column (text → img) |

## CSS Features Used

| Feature          | Where Used                                      |
|------------------|-------------------------------------------------|
| CSS Variables    | `--primary-color`, `--nav-font`, `--hero-h1` etc.|
| Flexbox (Navbar) | `display:flex` — NOT display:inline             |
| Flexbox (Hero)   | `flex-direction: row` (desktop/tablet)          |
| Flex column      | `flex-direction: column` on mobile              |
| Media Query 1    | `@media (max-width: 768px)` — Tablet            |
| Media Query 2    | `@media (max-width: 480px)` — Mobile            |

## Task Requirements Completed
- ✅ Navbar uses Flexbox (not display:inline)
- ✅ Navbar text smaller on tablet view
- ✅ Nav links hidden on mobile — only Logo and Username shown
- ✅ Hero text and image sizes reduced on tablet
- ✅ Hero switches to flex-direction:column on mobile (text on top, image below)
- ✅ CSS Variables used
- ✅ No Bootstrap — pure CSS only
- ✅ No inline CSS

## Submission
1. Put all 3 files in one folder (e.g. `YourName_Task7/`)
2. Compress to `.zip`
3. Rename → `YourName_Task7.zip`
4. Submit on TuteDude portal with deployed link