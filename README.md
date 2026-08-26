# Portfolio Website (GitHub Pages)

The GitHub Pages deployment of my 2023 portfolio — same React single-page site as
[`portfolio`](https://github.com/Sammy-05/portfolio), published from this repository.

**Live:** https://sammy-05.github.io/portfolio-website.github.io

Superseded by [`portfolio-website`](https://github.com/Sammy-05/portfolio-website), the current
portfolio.

## Sections

`Home` · `About` · `Education` · `Work` · `Projects` (with a `ProjectDesc` detail view) · `Footer`,
plus a custom animated `Cursor`.

An embedded résumé viewer is rendered with **react-pdf**, so the CV is readable in-page rather
than only downloadable.

## Stack

- **React 18** + React Router 6 (Create React App)
- **Tailwind CSS** (PostCSS pipeline)
- **react-pdf** — in-page résumé rendering
- **Font Awesome**

## Running it

```bash
npm install
npm start       # http://localhost:3000
npm run build   # output deployed to GitHub Pages
```

## Structure

```
src/
  components/       # one folder per section
  assets/
    projectImages/
```
