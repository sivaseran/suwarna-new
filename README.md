# Suwarna Rota — Final Verified Release

Data range: **1 May 2026 to 7 March 2027** (311 consecutive dates).

## Publish on GitHub Pages
Upload every file in this folder to the repository root. In GitHub, open **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/ (root)`.

## Future rota updates
Replace `rota.csv` with columns:

```csv
date,shift
2027-03-08,Short Day
2027-03-09,NICU 1 LD
```

Blank shift values are treated as Off. Existing time rules are configured in `index.html`.
