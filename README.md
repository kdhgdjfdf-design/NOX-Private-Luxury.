# NOX — Private Luxury

A calm, Arabic-first personal space built around the idea:

**Luxury for yourself, not for attention.**

## First prototype

This repository currently contains a lightweight, mobile-friendly web prototype in `index.html`.

Included:
- Arabic right-to-left interface with a dark, restrained gold visual identity
- Conversational concierge-style home with a compact personal daily brief
- Editable personal context for appointments, outfit, fragrance, hairstyle, conversation guide, reading position, podcast position, and saved assistant requests
- Home details open inline from small icons; the rest of the app remains accessible from the home navigation
- Daily priorities with completion checkboxes
- A simple daily schedule with time-sorted entries
- Daily log for study, reading, podcasts, skills, and personal time
- Notes with separate original and corrected text, search, and editing
- Personal library for books, podcasts, articles, videos, and resources, with search, type filters, and editing
- Demo assistant directory (clearly labeled as informational cards, not connected AI)
- Local data export and clear-data controls

The weather field in this prototype is manually entered. Live weather integration is not connected yet, so NOX does not invent forecasts. Personal concierge details are stored locally in the same browser data store.

## Privacy

The prototype stores its entries in this browser's local storage. It has no account system, cloud sync, analytics, or external AI/API connection. Data is local to the browser/device and may be lost if browser data is cleared. Export a backup before clearing browser data.

## Run

Open `index.html` in a browser, or serve the repository with any static web host.

## Project direction

Keep NOX personal, quiet, useful, and simple. Do not add paid APIs, public social features, or unnecessary complexity. Preserve the user's control over their data and choices.
