# CivilSeal

A single-page marketing site for CivilSeal, showcasing applied AI systems built for physical operations (vision inspection, predictive maintenance, autonomous material handling, environmental monitoring).

## Structure

```
.
├── index.html   # the entire site — self-contained, no build step
└── README.md
```

## Running it locally

Just open `index.html` in a browser. No server, build tools, or dependencies required.

## Publishing with GitHub Pages

1. Push this folder to a new GitHub repository.
2. In the repo, go to **Settings → Pages**.
3. Under "Branch," select `main` and `/ (root)`, then **Save**.
4. Your site will be live at `https://your-username.github.io/your-repo-name/` within a minute or two.

## Editing

Everything — copy, styling, and the hero diagram — lives in `index.html`. Colors and fonts are defined as CSS variables near the top of the `<style>` block, so palette or typeface changes only need to happen in one place.
