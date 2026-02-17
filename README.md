\# Secret QT Agent ID Generator



Simple static page that generates cute agent cards (emoji code, serial number and QR) for the Secret QT Club.



Usage

\- Open index.html in a browser (or run a simple server: `python -m http.server 8000`).

\- Enter a name, upload a photo, click "Generate".

\- Use Print to produce a physical card.

\- Optionally enable GitHub Pages to host it.



Notes

\- Uses QRCode from CDN: https://cdn.jsdelivr.net/npm/qrcode/build/qrcode.min.js

\- Images are client-side only (FileReader -> data URL); the page does not upload images to a server.



