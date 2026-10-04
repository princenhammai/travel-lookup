# Travel lookup snapshot — 2026-10-05

Source Google Sheet (read-only clone; sheet itself was not modified):
https://docs.google.com/spreadsheets/d/1bBZSX-9K6BQNAW3wI-zt1S_7LqwsgXmxECuZo0R5RZg

Public HTML view:
https://docs.google.com/spreadsheets/d/1bBZSX-9K6BQNAW3wI-zt1S_7LqwsgXmxECuZo0R5RZg/htmlview

Tabs discovered from htmlview `items.push`:

| Tab | gid | CSV rows | Export |
|-----|-----|----------|--------|
| Visa + Review | 0 | 281 | ok |
| Các nước miễn Visa cho VN | 1495900775 | 78 | ok |

Files under `travel-clone/` are the exact CSV exports plus JSON row arrays.
Site uses:
- `travel-data.json` — 277 review/article cards (from Visa + Review tab)
- `visa-data.json` — parsed visa country list (from Các nước miễn Visa cho VN)
- `index.html` — static UI; fetches only those committed JSON files

GitHub Pages target: https://princenhammai.github.io/travel-lookup/ (branch main, folder /)
