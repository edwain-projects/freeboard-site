# Freeboard

Umbrella website for seafarer-focused apps, published with GitHub Pages at [freeboard.boats](https://freeboard.boats). Each app gets its own path.

## Apps

| App | Path | Description |
|---|---|---|
| Days at Sea | [/daysatsea](https://freeboard.boats/daysatsea/) | iOS app tracking rotation, contract, and sea time. Fully offline — no accounts, no ads, no tracking. |
| Yard | [/yard](https://freeboard.boats/yard/) | iOS + Android job diary and Gantt chart for refits and shipyard periods (name not final). Offline, no accounts. Support: support@freeboard.boats. |

## Pages

| Page | URL |
|---|---|
| Umbrella landing page | [freeboard.boats](https://freeboard.boats) |
| Days at Sea landing page | [freeboard.boats/daysatsea](https://freeboard.boats/daysatsea/) |
| Days at Sea Privacy Policy | [freeboard.boats/daysatsea/privacy.html](https://freeboard.boats/daysatsea/privacy.html) |
| Days at Sea Support | [freeboard.boats/daysatsea/support.html](https://freeboard.boats/daysatsea/support.html) |
| Days at Sea EULA | [freeboard.boats/daysatsea/eula.html](https://freeboard.boats/daysatsea/eula.html) |
| Yard landing page | [freeboard.boats/yard](https://freeboard.boats/yard/) |
| Yard Privacy Policy | [freeboard.boats/yard/privacy.html](https://freeboard.boats/yard/privacy.html) |
| Yard Support | [freeboard.boats/yard/support.html](https://freeboard.boats/yard/support.html) |
| Yard EULA | [freeboard.boats/yard/eula.html](https://freeboard.boats/yard/eula.html) |
| 404 page | [freeboard.boats/anything](https://freeboard.boats/this-page-does-not-exist) |

## Stack

Static HTML/CSS, no build step, no dependencies. Hosted on GitHub Pages with a custom domain (see `CNAME`). New apps get a new top-level folder (e.g. `/nextapp/`) with their own `index.html`, `privacy.html`, `support.html`, and `eula.html`, then get linked from the root landing page.

## Local preview

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Contact

support@seatimetracking.com
