# VIBEMode website

## Run locally
1. Install Node.js (LTS).
2. Open this folder in a terminal.
3. Run `npm install`.
4. Run `npm run dev` and open the local URL shown in the terminal.

## Production build
Run `npm run build`. Vite creates the deployable site in `dist/`.

## Deploy free with Netlify
1. Push this folder to a GitHub repository.
2. In Netlify, choose **Add new site → Import an existing project** and connect the repository.
3. Build command: `npm run build`.
4. Publish directory: `dist`.
5. Deploy. Netlify provides an HTTPS URL.

You can also deploy on Vercel by importing the GitHub repository; use build command `npm run build` and output directory `dist`.

## Important demo limitations
- Checkout is a front-end demonstration; no real payment gateway or order backend is connected.
- The AI design screen has a local visual fallback. Real Gemini image generation requires a secure server-side API integration; do not put a private API key in browser code.
- Camera-based try-on requires HTTPS and user camera permission. The 3D/VR-style preview is a visual demo, not a body-accurate garment fitting system.
- Replace placeholder contact details, delivery claims, company details and policies with verified business information before accepting real orders.
