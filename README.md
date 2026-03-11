# GHS OPD Morbidity System

This repository contains the **Ghana Health Service OPD Morbidity System** – a lightweight
Node.js/Express application for offline patient entry and morbidity reporting.

> The actual application code lives in the `ghsmorbidity/` subdirectory. Clone this
> repo and then `cd ghsmorbidity` to run or edit the server.

## Overview

- **Backend:** Node.js with Express, serving static files and a simple JSON file as the
  database (`morbidity.json`).
- **Frontend:** Vanilla HTML/CSS/JS, no build tools required.
- **Data export:** Excel spreadsheets via [SheetJS](https://github.com/SheetJS/js-xlsx).
- **Deployment:** Can be run locally or deployed to any Node-capable host (Render, Heroku,
  Railway, etc.).

## Quick Start

```bash
cd ghsmorbidity
npm install
node server.js         # or use start.bat / start.sh on Windows/Linux
```

Then open http://localhost:3456 in a browser.

## Deployment
See the `DEPLOYMENT.md` file in the `ghsmorbidity/` folder for instructions on pushing
this app to GitHub and deploying with Render or similar services.

## License & Credits
- Created by the Ghana Health Service
- Public domain / ISC license

Feel free to explore the `ghsmorbidity` subfolder for the full source code.
