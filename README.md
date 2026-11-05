# Freeboard

Umbrella website for seafarer-focused apps, published with GitHub Pages at [freeboard.boats](https://freeboard.boats). Each app gets its own path.

## Apps

| App | Path | Description |
|---|---|---|
| Days at Sea | [/daysatsea](https://freeboard.boats/daysatsea/) | iOS app tracking rotation, contract, and sea time. Fully offline — no accounts, no ads, no tracking. |
| Days in Dock | [/daysindock](https://freeboard.boats/daysindock/) | iOS + Android job diary and Gantt chart for refits and shipyard periods. Offline, no accounts. Support: support@freeboard.boats. |
| Days in Dock Desktop Version | [/daysindock/desktop](https://freeboard.boats/daysindock/desktop/) | Windows (macOS and Linux to follow) job tracker and Gantt chart for shipyard periods. Runs on the computer, no internet. Separate from the phone app (no sync). No download link, price or version number on the pages (readers are assumed to know where the app is). Support: support@freeboard.boats. |

## Pages

| Page | URL |
|---|---|
| Umbrella landing page | [freeboard.boats](https://freeboard.boats) |
| Days at Sea landing page | [freeboard.boats/daysatsea](https://freeboard.boats/daysatsea/) |
| Days at Sea Privacy Policy | [freeboard.boats/daysatsea/privacy.html](https://freeboard.boats/daysatsea/privacy.html) |
| Days at Sea Support | [freeboard.boats/daysatsea/support.html](https://freeboard.boats/daysatsea/support.html) |
| Days at Sea EULA | [freeboard.boats/daysatsea/eula.html](https://freeboard.boats/daysatsea/eula.html) |
| Days in Dock landing page | [freeboard.boats/daysindock](https://freeboard.boats/daysindock/) |
| Days in Dock Privacy Policy | [freeboard.boats/daysindock/privacy.html](https://freeboard.boats/daysindock/privacy.html) |
| Days in Dock Support | [freeboard.boats/daysindock/support.html](https://freeboard.boats/daysindock/support.html) |
| Days in Dock EULA | [freeboard.boats/daysindock/eula.html](https://freeboard.boats/daysindock/eula.html) |
| Days in Dock Desktop Version landing page | [freeboard.boats/daysindock/desktop/](https://freeboard.boats/daysindock/desktop/) |
| Days in Dock Desktop Version Privacy Policy | [freeboard.boats/daysindock/desktop/privacy.html](https://freeboard.boats/daysindock/desktop/privacy.html) |
| Days in Dock Desktop Version Support | [freeboard.boats/daysindock/desktop/support.html](https://freeboard.boats/daysindock/desktop/support.html) |
| Days in Dock Desktop Version EULA | [freeboard.boats/daysindock/desktop/eula.html](https://freeboard.boats/daysindock/desktop/eula.html) |
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
