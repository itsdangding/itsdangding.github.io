# Dang Ding — personal website

Static home for **Dang Ding / itsdangding**: https://itsdangding.github.io/

- `index.html` — introduction, current build, selected work, writing, and about.
- `assets/home.css` — responsive styles. System fonts; no build tools or JavaScript required.
- `russian-go/` — the original Russian Go directory, including its about and archive pages. All original navigation entries and shared CSS, JS, fonts, and images are retained.
- Historical `/about/`, `/archives/`, and `/2024/` URLs remain available; their home links lead back to Russian Go.

## Preview

Run `python3 -m http.server 8000` from this directory, then visit http://localhost:8000/ and http://localhost:8000/russian-go/.

## Publishing

GitHub Pages publishes the root of the `master` branch. No dependency installation or application build is needed. Edit the HTML and CSS directly. Keep shared legacy assets at their existing root paths so old pages continue to work.

`repo-to-launch` intentionally has no external link until a public destination exists. After the Prompt currently presents the writing thesis; add article links when published.
