# Personal Academic Website

A clean, minimal academic portfolio site built with plain HTML/CSS. No frameworks, no build step — just files.

## File structure

```
your-repo/
├── index.html       ← main page
├── cv.pdf           ← your CV (replace with your file)
├── paper.pdf        ← your hosted paper (replace with your file)
└── README.md
```

## Setup on GitHub Pages

1. Create a new GitHub repository named `yourusername.github.io`
   (replace `yourusername` with your actual GitHub username).

2. Upload all files — `index.html`, your CV PDF, and your paper PDF — into the repo root.

3. Go to **Settings → Pages**, set source to `main` branch and `/ (root)`.

4. Your site will be live at `https://yourusername.github.io` within a minute or two.

## Customisation checklist

Open `index.html` and search for `✏️` to find every placeholder:

- [ ] Your name (appears in `<title>` and `<h1>`)
- [ ] Title / affiliation tagline
- [ ] Bio paragraphs in the About section
- [ ] CV filename (`cv.pdf`) and LinkedIn URL
- [ ] Email address
- [ ] Each publication entry (title, authors, year, venue, link)
- [ ] Each project entry (title, description, link)
- [ ] Paper PDF filename (`paper.pdf`)
- [ ] Footer copyright year

## Adding more publications or projects

Copy any `<div class="entry">…</div>` block inside the relevant section and fill in the new details.
