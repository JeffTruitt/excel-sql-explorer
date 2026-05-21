# Excel SQL Explorer

Upload Excel files and query them with SQL — entirely in the browser.

## Features

- **Drop-in Excel files**: Drag & drop `.xlsx` files to load them as queryable SQL tables
- **SQL queries**: Write and execute SQL queries against your data using AlaSQL
- **Data Explorer**: Browse tables, click column headers for distinct values, build IN clauses
- **Data Dictionary**: Inspect column types, value ranges, and distributions
- **Saved Queries**: Save, edit, organize, and share queries with page/section/tab categorization
- **Deep-link queries**: Each saved query has a shareable URL (`#query=ID`) for linking from tickets
- **Persistent storage**: Data and queries persist in IndexedDB across browser sessions
- **Case-insensitive SQL**: Table and column names resolve regardless of casing
- **CSV export**: Export query results to CSV

## Usage

1. Open `index.html` in a browser (or visit the GitHub Pages URL)
2. Drag & drop one or more Excel files onto the upload zone
3. Write SQL queries in the editor or use template chips
4. Save queries and share their URLs with teammates

## Hosting

This is a single HTML file with no backend. Host it on GitHub Pages, any static file server, or open it directly as a local file.

### GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings > Pages**
3. Set source to **Deploy from a branch**, select `main`, root folder
4. The site will be available at `https://<org>.github.io/excel-sql-explorer/`

## Data Privacy

All data stays in your browser. Excel files are parsed client-side and stored in IndexedDB. Nothing is sent to any server.
