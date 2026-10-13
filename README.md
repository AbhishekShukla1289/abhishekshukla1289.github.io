# abhishekshukla1289.github.io

Personal site of **Abhishek Shukla**, backend software engineer. Live at <https://abhishekshukla1289.github.io>.

One static HTML file, no framework and no build step. GitHub Pages serves it straight from `main`.

```
index.html        the whole site (markup, CSS and JS inline)
404.html          not-found page
favicon.svg       tab icon
og.png            1200×630 preview image for LinkedIn / Slack / X
assets/avatar.jpg headshot
.nojekyll         tells Pages to serve files as-is
```

## Editing

Everything lives in `index.html`. Search for these to update content:

- `id="about"`: intro paragraphs and the stack / education list
- `id="experience"`: one `<li class="entry">` per role; `.when` holds the dates
- `id="projects"`: two groups, *Systems* and *Apps & games*
- `id="writing"`: add published articles here as `.entry` items
- `id="contact"`: email address (appears twice: the text and the `mailto:` link)
- `TODO` comments mark spots that still need details

Colors and fonts are tokens in the `:root` block at the top of the `<style>` tag. Dark is the default, and the
light palette sits in the two blocks right after it.

## Preview locally

```bash
python3 -m http.server 8000   # then open http://localhost:8000
```
