# BIP360 Introduction and Update


## Rendering

### Option 1 — Node.js dev server

```bash
npm install          # one-time setup — installs the 'serve' package
npm start            # serves on http://localhost:8000
```

### Option 2 — Python static server (no npm required)

```bash
python3 -m http.server 8000
# open http://localhost:8000 in a browser
```

## Exporting to PDF

1. Open the deck in Chrome or Chromium.
2. Append `?print-pdf` to the URL:
   ```
   http://localhost:8000/?print-pdf
   ```
3. Open the browser's Print dialog → **Save as PDF**.
   - Set paper size to A4 landscape or 1200×700 px.
   - Disable headers and footers.

---
