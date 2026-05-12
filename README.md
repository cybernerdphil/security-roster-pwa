# Security Roster PWA

A Progressive Web App (PWA) for Security roster management.

## Overview

This repository contains a simple offline-capable PWA for managing security team rosters and availability.

## Files

- `index.html` — main application page
- `css/styles.css` — app styling
- `js/app.js` — application logic
- `manifest.json` — PWA metadata
- `service-worker.js` — offline caching and service worker logic

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/cybernerdphil/security-roster-pwa.git
   ```
2. Open `index.html` in your browser, or serve the folder using a local web server.

## Run Locally

For local development, use a simple static server such as `http-server`, `python`, or another tool.

Example with Python 3:

```bash
cd security-roster-pwa
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Features

- Offline-first PWA behavior
- Mobile-friendly layout
- Roster and availability interface

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contributing

Contributions are welcome. Open an issue or submit a pull request with improvements.