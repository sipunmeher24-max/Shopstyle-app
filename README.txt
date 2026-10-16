SHOPSTYLE — ANDROID WEB APP STARTER (PHASE 1)

This is a Progressive Web App (PWA) starter for a men's clothing shop. It is not a signed APK yet.

PHASE 1 FEATURES
- Add several product photos in one batch
- Apply one shared size/category to a batch
- Edit product names and prices before saving
- Product catalogue and remove products
- Select products to build an outfit and calculate total price
- Share outfit details using the Android share sheet when supported
- Customer photo selection/preview (local only)
- Export/import catalogue backup
- Home-screen installation support when hosted over HTTPS
- Basic offline caching of the app shell after first online load

AI VIRTUAL TRY-ON STATUS
The AI try-on button is currently a placeholder; no AI provider is connected. A real try-on system needs a provider that accepts both a customer photo and a garment photo, plus a secure server/backend. Do not put secret API keys in index.html. A genuinely free service with suitable commercial terms and enough usage is not guaranteed, so we should test free tiers before choosing one. Customer photos should only be uploaded with explicit permission.

INSTALL ON ANDROID (FREE HOSTING ROUTE)
1. Extract this ZIP on a computer, or upload its contents to a GitHub repository.
2. On GitHub, open the repository Settings > Pages.
3. Under Build and deployment, choose deploy from a branch, select the main branch and /(root), then Save.
4. Wait for GitHub Pages to show the public HTTPS website address.
5. Open that address in Google Chrome on the Android phone.
6. Tap Chrome's three-dot menu (⋮) > Install app (or Add to Home screen) and confirm.

If you only have an Android phone, tell ChatGPT and we can go through the setup one screen at a time. Do not share passwords or verification codes.

DATA & PRIVACY
- Product data is saved in this browser on this phone using localStorage.
- Export a backup regularly. Clearing browser/site data can delete the catalogue.
- The selected customer photo is previewed locally in this starter and is not uploaded.
- The app shell can cache after the first successful online load, but this does not guarantee all browser data or images will survive clearing storage.

NEXT PHASE
1. Confirm the catalogue and outfit workflow on the phone.
2. Evaluate an AI try-on provider's free tier, API access, privacy policy, and commercial-use terms.
3. If suitable, connect it through a secure backend. If no appropriate free option exists, keep the app functional without AI until a provider is chosen.
