# Too Many Portfolios

A directory of every portfolio site I've built, all still online. Live at **[sc.is-a.dev/portfolios](https://sc.is-a.dev/portfolios/)**.

The background is a live ASCII wallpaper drawn on a canvas, with four scenes you can switch between (koi pond, sharks, cloud drift, night rain). Press `T` to cycle.

## Stack
One HTML file. Vanilla CSS and JavaScript, no dependencies, no build step.

## Run locally
```bash
python -m http.server 8000
```

## Adding a site
Add a screenshot to `shots/` (1440x900 webp) and copy one `<a class="card">` block in `index.html`.
