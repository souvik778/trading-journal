EDGE JOURNAL

What changed:
- Local-first static app with IndexedDB
- Screenshot support
- Playbook setup section
- Daily reviews and process scoring
- Calendar heatmap
- Better analytics dashboard
- PWA support for installable app feel
- Works locally and on GitHub Pages

Important limitation:
- Hosting on GitHub Pages does NOT sync your data across devices by itself.
- Data stays in each device/browser's IndexedDB.
- Use Export Backup / Import Backup to move the journal between devices.

How to use locally:
1. Extract the folder.
2. Open index.html in a browser.
3. Start logging trades.
4. Export backups regularly.

How to host on GitHub Pages:
1. Create a GitHub repository.
2. Upload all files in this folder.
3. In GitHub repo settings, enable Pages from the main branch / root.
4. Open the GitHub Pages URL on any device.
5. Import the same backup file on each device if you want the same journal data.

Future upgrade for true sync:
- Add Supabase, Firebase, or your own API/backend.
