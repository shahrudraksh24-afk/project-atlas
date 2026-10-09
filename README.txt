PROJECT ATLAS — PERSONAL FITNESS TRACKER

Files:
- index.html: the app
- manifest.json: installable web app metadata
- sw.js: basic offline caching
- README.txt: these instructions

QUICK START:
1. Extract the ZIP.
2. Open index.html in a modern browser to use the tracker.
3. The browser saves workouts, nutrition totals, meals, and check-ins in local storage on that device.
4. Use Progress > Export data to save a JSON backup.

INSTALLABLE / OFFLINE:
For reliable PWA installation and service-worker offline support, host these files over HTTPS (for example, a free static site host) and open the URL in Chrome on Android. In Chrome, use the browser menu and choose "Install app" or "Add to Home screen" if offered.
Opening index.html directly works for tracking but service workers generally require HTTPS or localhost.

NOTES:
- This prototype does not have accounts or cloud sync.
- Browser data can be lost if site data is cleared; export backups regularly.
- Calorie and protein numbers are estimates, not medical advice.
- Use good technique and take rest when needed.
