# MarketNear

## Overview
MarketNear is a static single-page web application for a decentralized marketplace on the NEAR blockchain. The UI is built with Tailwind CSS (via CDN) and vanilla JavaScript, all contained in a single `index.html` file.

## Project Architecture
- **Type**: Static website (single HTML file)
- **Frontend**: Vanilla HTML/CSS/JS with Tailwind CSS (CDN)
- **Server**: Python `http.server` for local development (serves on port 5000)
- **Deployment**: Static deployment serving the root directory

## Key Files
- `index.html` - The entire application (670 lines)
- `server.py` - Simple Python HTTP server for development
- `.gitignore` - Python ignores

## Running Locally
The app is served via `python server.py` on `0.0.0.0:5000`.

## Recent Changes
- 2026-02-16: Initial Replit setup - added Python server, workflow, deployment config
