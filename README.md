# QRNova — SkillCraft Task 04

A modern QR Code Scanner + QR Code Generator web app.

## Features
- Camera QR scanning
- Scan QR from an image
- QR result actions: copy, open link, share, save
- QR generator for Text, Website, Wi‑Fi, Email, Phone and SMS
- Download generated QR as PNG
- Scan/generation history with search and delete
- LocalStorage persistence
- Dark/light mode
- Responsive mobile-first UI
- GitHub Pages friendly

## Run
Open `index.html` in a browser. For camera scanning, deploy on HTTPS (GitHub Pages is suitable).

## Deploy to GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html` and `README.md`.
3. Open repository **Settings → Pages**.
4. Select **Deploy from a branch**, choose `main` and `/root`.
5. Save and open the generated Pages URL.
6. Allow camera permission when you tap **Start Camera**.

## Libraries
- html5-qrcode for browser camera/image QR scanning.
- QRCode.js for QR generation.

Both are loaded from public CDNs in `index.html`.
