# DevNotes Mobile / PWA

Open `index.html` on a desktop for local use. For phone installation, host the entire folder on an **HTTPS** static site (e.g. GitHub Pages, Netlify) and open the HTTPS URL on the phone. Android Chrome: menu → Install app / Add to Home screen. iPhone Safari: Share → Add to Home Screen. Once opened online, app shell can work offline.

**Important:** Notes are stored in browser localStorage, **per browser and device**. They do not automatically synchronize from your computer to phone. Export JSON on computer, transfer file to phone, and import in DevNotes on phone. Export backups regularly; clearing site data may delete notes. Opening via file:// cannot install the PWA/service worker.
