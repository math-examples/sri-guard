# 🔍 SRI Guard

Subresource Integrity Checker & Auto‑Fix — a 100% client‑side web tool.

## What it does
Scans HTML documents for SRI hashes on `<script>` and `<link>` tags, verifies each subresource with SHA‑384, reports pass/fail/mismatch, and generates a downloadable fixed HTML file.

## Features
- ✅ Remote URL & local file input
- ✅ Auto‑detects `onerror` fallback URLs
- ✅ One‑click hash correction & download
- ✅ Zero server dependency — runs entirely in your browser
- ✅ Clean, mobile‑friendly UI

## Usage
1. Paste a URL or choose an HTML file
2. Click **Check Remote** or select a file
3. Review results
4. Click **Auto‑Fix** to download a patched HTML file

## Tech
Pure HTML/CSS/JS · Web Crypto API (SHA‑384) · DOMParser · Blob API

## Limitations
Remote resources require CORS headers (`Access-Control-Allow-Origin`). This is a browser security restriction.

## Run locally
