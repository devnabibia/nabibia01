# Dennis Nangendo — portfolio

Static site: plain HTML, CSS and JavaScript (GSAP and Lenis load from a CDN). No build step.

## View it

Open `index.html` in a browser, or serve the folder:

    python3 -m http.server 8000     # then open http://localhost:8000

## Things to finish

1. **Your photo:** replace `img/dennis.jpg` (square, about 900×900). It is a grey "DN" placeholder now.
2. **Résumé:** put your PDF in a new `downloads/` folder, then uncomment the Resume button in the
   header of `index.html` (search for "To add a resume button").
3. **LinkedIn:** not added, because the link you gave me was not a valid URL. Add one next to the
   GitHub and X links in `index.html` (hero icons and the contact section).
4. **Experience:** check the wording of your current role (see the note in the chat).
5. **Domain and sharing preview:** once you have a domain, add `<link rel="canonical">`, `og:url` and an
   `og:image` to the `<head>`, and a `sitemap.xml`.

## Where things are

- `index.html` — all the content: hero, about, experience, stack, projects, contact
- `css/site.css` — styles (colors are the variables at the top)
- `js/site.js` — animations, the typing effect, the boot screen and the hero terminal
- Typed hero words: the `data-words` attribute on `#typer` in `index.html`
- Terminal lines: the `lines` list in `startTerminal()` in `js/site.js`

## Deploy (GitHub Pages)

Push this folder to a repository named `devnabibia.github.io` (or any repo with Pages enabled).
