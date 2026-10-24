# Tadiyos Banti — Personal Site

Static personal/academic homepage, served with GitHub Pages at https://tadiyos49.github.io/.

No build step: plain HTML, CSS, and a few lines of JavaScript.

```
index.html        all page content (Home, Experience, Projects, Education)
style.css         layout and light/dark theme
favicon.ico       site icon
assets/           avatar, CV (cv.pdf), touch icon
```

## Run locally

```
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Updating

- Edit text directly in `index.html`. Each page is a `<section id="page-...">`.
- Replace the CV by overwriting `assets/cv.pdf`, then bump the `?v=` number on the CV links so browsers fetch the new file.
