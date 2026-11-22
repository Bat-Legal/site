# Bat website · try-bat.com

The public website for **Bat (بَتّ)**, a law-firm system for Saudi firms with an AI team that does the work.

> Temporary demo site. It will be redesigned later, and the domain may move to bat.sa.

## What's here
| Path | What |
|---|---|
| `index.html` | The whole site (Arabic + English, all pages, styles and scripts in one file) |
| `assets/agents/` | Agent icons |
| `assets/favicon.svg` · `assets/og.png` | Browser icon and link-preview image |
| `CNAME` | Custom domain (`try-bat.com`). **Don't delete it**, or the domain stops working. |

## How to update
1. Edit `index.html` (or replace it with a new export) and keep asset paths relative (`assets/...`).
2. Push to `main`. GitHub Pages publishes in about 1 minute.
3. Check https://try-bat.com on desktop and phone.

## Demo form
"Book a demo" posts to FormSubmit, which emails **hello@try-bat.com**. The endpoint is the `FORM_ENDPOINT` constant at the top of the script. If the domain changes, the first submission from the new domain sends an activation email to hello@ that must be clicked.

## Rules
- This repo is **public**: no secrets, no client data, no internal docs.
- No prices, competitor names or "official Najiz/MoJ" claims on the site.
