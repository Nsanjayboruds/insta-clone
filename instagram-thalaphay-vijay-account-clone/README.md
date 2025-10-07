# Instagram — Thalaphay Vijay Account (HTML & CSS clone)

**Project:** `instagram-thalaphay-vijay-account-clone`

A lightweight static clone of an Instagram profile page inspired by the *Thalaphay Vijay* account. Built **only** with **HTML** and **CSS** (no JavaScript) to showcase responsive layout, visual styling, and pixel-approximate UI of a social media profile.

---

## Demo

Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari) to view the page. No server required — just double-click the file.

---

## Features

* Pixel-style profile header with profile photo, name, bio and action buttons (Follow, Message).
* Responsive grid of posts (3-column on desktop, 2 on tablet, 1 on mobile).
* Post cards containing images, like/comment/share icons (purely visual — no interactivity).
* Basic responsive nav bar and mobile-friendly layout using CSS Grid and Flexbox.
* Clean, semantic HTML structure and well-organized CSS with variables for quick theming.

---

## Built With

* HTML5
* CSS3 (Flexbox, Grid, CSS variables, media queries)

*No JavaScript, no frameworks — pure static front-end.*

---

## Installation / How to run

1. Clone this repository or download ZIP.

```bash
git clone https://github.com/<your-username>/instagram-thalaphay-vijay-account-clone.git
cd instagram-thalaphay-vijay-account-clone
```

2. Open `index.html` in your browser. Example (macOS / Linux):

```bash
open index.html
```

Or on Windows, double-click `index.html` or run:

```bash
start index.html
```

---

## Project Structure

```
instagram-thalaphay-vijay-account-clone/
├─ index.html           # Main profile page
├─ css/
│  └─ style.css         # All styling (variables, layout, responsive rules)
├─ assets/
│  ├─ images/           # profile photo + post images
│  └─ fonts/ (optional) # custom fonts if used
└─ README.md
```

---

## Styling notes & customization

* The CSS uses variables at the top of `style.css` (colors, spacing, breakpoints) — change them to re-theme the page quickly.
* Grid layout for posts is implemented with `display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));` for responsive behaviour.
* Profile action buttons use subtle hover states created with `:hover` and CSS transitions.

---

## Accessibility

* Semantic elements (`header`, `nav`, `main`, `aside`, `footer`) are used for better structure.
* Images include `alt` attributes. If you add decorative images, mark them with empty `alt=""`.
* Ensure color contrast when customizing theme variables.

---

## Contributing

1. Fork the repo.
2. Create a branch: `git checkout -b feature/your-change`.
3. Make changes and commit: `git commit -m "Add a nice feature"`.
4. Push to your branch: `git push origin feature/your-change`.
5. Open a Pull Request with a description of your changes.

---

## License

This project is provided for learning and demo purposes. Use freely for personal and educational purposes. If you want a specific license, add a `LICENSE` file (e.g., MIT) to the repo.

---

## Credits

* Inspired by Instagram UI and the *Thalaphay Vijay* profile aesthetic.
* Built by **you** — replace this line with your name or GitHub handle.

---

## Tips & Next steps (optional)

* Add real images for posts in `assets/images` and update `index.html`.
* Add subtle animations with `@keyframes` for hover effects.
* Convert repetitive post cards into server-rendered templates if later ported to a backend.

---

Happy coding! 🎉
