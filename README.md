# RAMIZ STUDIO

A free, Bengali-first browser workspace for common photo, image and PDF tasks.

## Available tools
- AI background removal with transparent PNG or solid white/blue/red background (loads an open-source browser model on demand)
- Photo editor: crop ratios, rotate, brightness, contrast, saturation, grayscale and sepia
- Image resize by pixel dimensions, quality adjustment, approximate target KB and JPG/PNG/WebP output
- Passport photo sheet with configurable dimensions, copy count and A4 / 4×6 layout
- Multiple photo print sheet (A4)
- Image format conversion (JPG, PNG, WebP)
- Signature resize
- Images to multi-page PDF
- Merge PDF files
- Split PDF by page ranges
- PDF pages to PNG/JPG
- NID front/back A4 print layout
- CV maker with browser print / Save as PDF

## Run locally
Open `index.html` in a current browser. PDF and AI tools load open-source libraries/models from public CDNs, so an internet connection is needed for those tools. Basic image editing runs in the browser.

## Deploy
For GitHub Pages: repository Settings → Pages → Deploy from a branch → `main` → `/(root)`.
For Vercel: import this repository and use the project root. No build command is required for this static HTML app.

## Free / privacy
There are no payment screens, subscriptions, premium tiers, or paid feature locks in this app. Ordinary image operations run locally in the browser. Background removal and PDF tools download public open-source code/model assets when used. Files are not uploaded to a RAMIZ STUDIO server by this app. Do not use shared devices for sensitive identity documents.

## Important limitations
This is an original free toolkit, not a claim of exact feature parity with Studiozly. It currently implements the tools listed above. It does not include every possible Studiozly feature, server-side OCR, cloud accounts/sync, automatic face retouching, or professional document verification. Background-removal model loading depends on browser memory, device capability, CDN access and network speed. Target KB compression is approximate; some images cannot be reduced to a requested size without unacceptable quality loss. PDF rendering and print dimensions should be checked in the browser print dialog before official use. Multi-photo print sheet currently places the selected photos that fit on one A4 page; select fewer images if needed.

## Source
All application code is in `index.html`.