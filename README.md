# Pocket Budget — local-first web app

## What this build does
- Mobile-first layout with rounded-square category budget tiles at the top; each tile shows budget, spent, amount left, and percentage left (no progress bars).
- Sticky bottom Add expense button opens a quick-entry modal; saving an expense immediately updates the tiles and transaction history.
- Inbound (monthly income) and month totals sit below the category tiles.
- Automatically saves income, budgets, EMI allocations, and expenses in the browser's localStorage.
- Keeps separate budgets and transactions for each month.
- Switching months does not clear any records.
- Allows editing monthly income and planned category allocations.
- Includes CSV export and JSON backup/restore.
- Includes a manual month-end carry-forward/savings recommendation. It does not move money automatically.

## Easiest way to use it on iPhone
For reliable Home Screen installation, host this static app over HTTPS (for example, GitHub Pages):
1. Create/sign in to GitHub and create a new repository named `pocket-budget`.
2. Upload `index.html` from this folder to the repository root.
3. In the repository, open Settings → Pages.
4. Under Build and deployment, choose Deploy from a branch, select `main` and `/ (root)`, then Save.
5. Wait for the published HTTPS URL shown in Pages.
6. Open that URL in Safari on your iPhone.
7. Tap Share → Add to Home Screen.

Data is saved in that browser on that device. It does not automatically sync between devices. Do not clear Safari website data for this site. Use Data & backup → Download backup periodically, and keep the JSON file somewhere safe. For stronger cross-device syncing, a cloud database and authentication would be needed.

## Local testing
Open `index.html` in a modern browser. Browser restrictions vary for local files; use HTTPS hosting for the most reliable iPhone Home Screen experience.
