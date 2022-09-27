# Google Apps Script / Sheet API: Query Metabase API

> Custom JavaScript-based in-cell formula to fetch the data from a Metabase query (as CSV)

## Quickstart

a) Copy/paste scripts as `.gs` into Apps Script project

b) Local development with `node` & [`clasp`](https://github.com/google/clasp) ([Official Google Apps Script CLI](https://developers.google.com/apps-script/guides/clasp))

- `(p)npm install`
- **NOTE**: enable Google Apss Script for user: [https://script.google.com/home/usersettings]
- `clasp login`
- get Script ID `<scriptID>` from Apps Script GUI
- `clasp clone <scriptID>`
- deploy with `clasp push` (will overwrite remote state))
- **WARN**: (pull with `clasp pull` - will overwrite local state)
- open Apps Script GUI (browser) with `clasp open`
