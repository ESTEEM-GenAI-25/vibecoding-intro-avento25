## Personal Website — Alex Vento (ESTEEM @ Notre Dame)

Static site built with plain HTML/CSS/JS. Live sections: About, Projects, Experience, Education, Hobbies, Contact, and a 404 page.

### Run locally

- Open `index.html` directly in a browser, or serve with a simple HTTP server:

```bash
# Python 3
python -m http.server 5173
# then open http://localhost:5173
```

### Deploy to GitHub Pages

1. Commit and push to the `main` branch.
2. In GitHub repo settings → Pages, select:
   - Source: `Deploy from a branch`
   - Branch: `main` `/ (root)`
3. Save. Your site will be available at `https://<username>.github.io/vibecoding-intro-avento25/`.

Note: The `404.html` includes a meta refresh pointing to `/vibecoding-intro-avento25/` for Pages.

### Customize

- Replace the portrait image URL in `index.html` with your own.
- Update email/links, and drop `Alex_Vento_Resume.pdf` beside `index.html`.

