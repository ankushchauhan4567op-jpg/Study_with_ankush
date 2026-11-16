STUDY WITH ANKUSH — V2
Features: Daily homework checklist; notes library; TXT/PDF text extraction; image OCR (English, requires internet/CDN); quiz generation from notes; scoring and wrong-answer review; revision and wrong-answer print-to-PDF; progress history; PWA install/offline shell.

Important limitations:
- This is a client-side prototype. It does NOT yet have a connected AI model, so question generation is rule-based, not deep AI.
- Automatic daily homework delivery/push notifications need a secure backend and notification service.
- PDF/image extraction libraries load from CDNs and require internet. Scanned PDFs may need OCR support, which is not yet built into the PDF flow.
- Data is stored in this browser/device only, not synced across devices.

Deploy:
Upload all files to an HTTPS static host (e.g. GitHub Pages or Netlify). Open URL in Android Chrome and choose Install app / Add to Home screen.


Version 2.2: Updated app branding with the supplied Indian Railways / भारतीय रेल image. The logo is used in the app header, PWA icons, and iOS Home Screen touch icon.
