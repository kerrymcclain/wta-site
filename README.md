# westtexasanalytics.com

The West Texas Analytics website, served by GitHub Pages.

- `index.html` — the whole site: animated sunrise over the Twin Buttes, menu (Home · Tools · Contact), contact footer.
- `CNAME` — custom domain for GitHub Pages.
- Icons (`favicon-32.png`, `apple-touch-icon.png`, `icon-512.png`) and the link-preview image (`og.jpg`).

Tools live in a separate repo: [`kerrymcclain/wta-tools`](https://github.com/kerrymcclain/wta-tools) → https://tools.westtexasanalytics.com

Design source (artwork generators, concepts, notes) is in the private `kerrymcclain/wta-website` repo.

## DNS (GoDaddy)

| Record | Name | Value |
|---|---|---|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | kerrymcclain.github.io |
| CNAME | tools | kerrymcclain.github.io |

Email (MX, SPF and related records) stays as-is at GoDaddy.
