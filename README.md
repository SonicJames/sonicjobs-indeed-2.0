# SonicJobs — Indeed 2.0 Design Prototype

Static HTML/CSS prototype of the SonicJobs candidate platform.

## Pages

| File | Description |
|------|-------------|
| `matches.html` | Resume-driven match view — Great Matches vs Need Further Info |
| `dashboard.html` | Application dashboard — pipeline, resume versions, status tracking |
| `search.html` | Smart LLM-style search with blurred results behind resume upload gate |
| `styles.css` | Shared design system — colours, typography, components |

## Running locally

Just open any `.html` file in a browser. No build step required.

```bash
open matches.html
```

## Design notes

- Font: DM Sans via Google Fonts
- Icons: Tabler Icons webfont (CDN)
- Colour palette: SonicJobs purple `#7F77DD` / `#534AB7`
- All pages are static — no JS interactions yet
- Navigation links between all three pages
