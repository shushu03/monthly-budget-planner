# Monthly Budget Planner (iPhone PWA)

## What is included
- Mobile-friendly budget dashboard
- Initial budget data from the supplied JSON
- Monthly recurring expense list (add/edit/delete)
- Transaction records (income/expense, date, category)
- Monthly filtering and basic charts
- Savings target
- JSON backup and restore
- PWA manifest, icons, service worker

## Important
This first version saves data in the current browser on this device. It does not sync across devices and does not connect to bank accounts. Export a JSON backup regularly.

## Deploy for iPhone installation
PWA installation requires an HTTPS website. Easiest beginner route:
1. Create a GitHub account if needed.
2. Create a new repository and upload the files in this folder.
3. In repository Settings -> Pages, choose deploy from branch, select `main` and `/ (root)`.
4. Wait for GitHub Pages to provide the HTTPS URL.
5. Open that URL in Safari on iPhone -> Share -> Add to Home Screen.

You can also use a static hosting service such as Netlify by uploading the folder, if available.
