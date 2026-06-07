# AUD Exchange Dashboard

A lightweight exchange-rate dashboard for tracking the strength of the Australian Dollar (AUD) against up to three selected currencies.

Designed for monitoring exchange-rate trends over time, identifying favourable conversion opportunities, and maintaining a local history of exchange-rate movements.

## Features

- Current exchange rates with weekly movement indicators (🟢 ↑, 🔴 ↓, ⚪ →)
- 90-day best rate tracking and gap-to-best calculations
- Multi-axis trend graph with Hourly, Daily, Weekly and Monthly views
- Local history storage with Import and Export support

## Running the Dashboard

### Local HTML Version

1. Download the latest dashboard HTML file.
2. Save it anywhere on your device.
3. Open the file in your preferred browser.

No installation is required.

### GitHub Pages Version

1. Upload all repository files to GitHub.
2. Open **Settings → Pages**
3. Configure:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/** (root)
4. Save the configuration.

GitHub will generate a URL similar to:

```
https://yourusername.github.io/repository-name/
```

The dashboard will automatically update whenever changes are committed to the repository.

## Home Screen and Desktop Shortcuts

### Android

For the best experience, use the GitHub Pages deployment.

1. Open the dashboard URL in Brave, Chrome or Samsung Internet.
2. Open the browser menu.
3. Select **Add to Home Screen**.
4. Confirm the shortcut name.

The dashboard can then be launched like a normal application from your home screen.

### Windows

Chrome, Brave and Edge support installing the dashboard as an application.

1. Open the dashboard URL.
2. Open the browser menu.
3. Select **Install App** or **More Tools → Create Shortcut**.
4. Enable **Open as Window** if available.
5. Create the shortcut.

The dashboard can then be pinned to the taskbar or Start Menu.

## Data Storage

All data is stored locally within your browser using Local Storage.

Stored information includes:

- Historical exchange-rate data
- Selected currencies
- Dashboard preferences

Data remains on the device unless browser storage is cleared or a different browser is used.

## Import and Export

### Export

Use the **Export** button to create a JSON backup of all stored history.

### Import

Use the **Import** button to restore a previous backup.

Imported data is automatically merged and sorted chronologically.

## Future Enhancements

Potential future improvements include:

- Progressive Web App (PWA) support
- Push notifications for new 90-day highs
- Configurable polling intervals
- Additional currency support
- Cloud-based synchronisation
