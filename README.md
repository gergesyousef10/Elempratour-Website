# El Empratour — website

The restaurant's website: the full menu with prices and photos, plus buttons to order on WhatsApp, book a table, call, and get directions.

## Changing the contact details

Open `config.js` and fill in:

| Field | Example |
|---|---|
| `whatsapp` | `"201001234567"` (country code, no `+`, no spaces) |
| `phone` | `"0653456789"` |
| `hours_ar` / `hours_en` | `"كل يوم من ١٢ الظهر لـ ٢ بالليل"` / `"Daily, 12 noon – 2 am"` |
| `facebook` / `instagram` / `tripadvisor` | the page links |
| `maps` / `mapsQuery` | the Google Maps link and the address the map shows |

Any field left empty (`""`) hides its button.

## Files

- `index.html` — the whole site (menu included)
- `config.js` — contact details
- `img/` — logo and dish photos
- `Empratour-menu.pdf` — the printable menu

## Publishing

Settings → Pages → Source: **Deploy from a branch** → Branch: **main** / **(root)** → Save.
The site is then at `https://gergesyousef10.github.io/Elempratour-Website/`.
