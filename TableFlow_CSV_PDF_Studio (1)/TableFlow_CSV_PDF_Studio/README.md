# TableFlow — CSV & PDF Studio

Static, browser-based CSV/PDF conversion and table editor for GitHub Pages. No database, account, or backend.

## Features
- Import CSV and edit cells in place.
- Rename headers, add/delete rows and columns.
- Export the edited table to CSV or a formatted PDF.
- Extract selectable text from PDFs into an editable table, then export as CSV.
- Drag-and-drop import and responsive interface.
- Files are processed locally in the browser.

## Run locally
Open `index.html`, or run `python -m http.server 8000` and visit `http://localhost:8000`.

## Publish on GitHub Pages
1. Create a repository and upload `index.html`, `style.css`, `app.js`, and `README.md` to the root.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select `main` and `/(root)`, then Save.

## Limitations
PDF-to-CSV is approximate because PDF documents do not always preserve row/column structure. Scanned PDFs need OCR, which is not included. External JavaScript libraries load from CDNs, so an internet connection is required. No files are uploaded to a server by this app.
