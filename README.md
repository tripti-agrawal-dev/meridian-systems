# Meridian Systems website (front end)

Static front end for a software services company. No build step.

## Run locally
- Open the folder in VS Code, install the "Live Server" extension, right-click `index.html` and choose "Open with Live Server".
- Or from a terminal in this folder: `python -m http.server 5500` then open http://localhost:5500

## Structure
- `index.html` page shell
- `css/styles.css` all styles and responsive breakpoints
- `js/app.js` routing, service data, search, pop-ups, form validation

## Edit
- Company name, services and copy: `js/app.js` (arrays `SV`, `ST`, `M`, `FQ`, `TK`) and `index.html`.
- Colours and fonts: CSS variables at the top of `css/styles.css`.
- The contact form is front end only; connect it to a backend before launch.
