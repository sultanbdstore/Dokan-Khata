# দোকান খাতা · Dokan Khata
Bangla shop ledger (বাকির খাতা). Works offline, installable, no account, no server. Data stays in the phone's browser.

Features: customers and suppliers with live balance (পাবো / দেবো), বাকি and টাকা পেলাম entries with notes and dates, due-date reminders (⏰), WhatsApp reminder message, call button, share statement, print / save as PDF, daily cash book (sales, expenses, net cash), search, PIN lock, backup / restore (JSON), light and dark theme.

## Publish on GitHub Pages
Upload all files to a repo, then Settings → Pages → Source: **Deploy from a branch** → `main` → `/ (root)` → Save.
After editing `index.html`, change `VERSION` in `sw.js`.

Data is stored in the browser: clearing browser data erases it. Back up regularly. The PIN only locks the screen, it does not encrypt data.

MIT License.
