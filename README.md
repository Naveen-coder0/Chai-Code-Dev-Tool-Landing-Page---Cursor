
# Cursor Landing Page — Static Clone

A static HTML/CSS recreation of the Cursor landing page used as a frontend assignment. The project is desktop-first but includes responsive rules for narrower screens.

**Quick preview**
- Open `index.html` in a browser, or run a local server (recommended):

```bash
python -m http.server 5500
# then open http://127.0.0.1:5500
```

**What this project contains**
- `index.html` — the page markup.
- `style.css` — all styling (no JavaScript or frameworks).
- `Assets/` — images and icons used on the page.
- `README.md` — project overview and usage.

**Key features implemented**
- Top navigation, hero with CTA, and large showcase image.
- Trusted-by logo strip and feature sections with images.
- Feature cards, testimonials, changelog, and footer.
- Responsive CSS rules for smaller viewports.

Tech & assets
- HTML5, CSS3 (Google font: Inter via stylesheet link in `index.html`).
- No JavaScript; purely presentational.

Notes for contributors
- Replace files in `Assets/` to update imagery.
- Tweak layout via `style.css` — media queries start at `@media (max-width: 1024px)`.
- To test cross-browser appearance, open `index.html` in different browsers or use a local server as shown above.

License
- Use as a learning/demo project. No commercial distribution intended unless original assets are cleared.

If you want, I can also:
- Add a minimal `package.json` and dev server configuration.
- Optimize images in `Assets/`.

