# Wedding Invitation - Vercel Deployment Folder

## Folder Structure
- `index.html`: Main wedding invitation website (Sage Green, White & Blush Pink theme).
- `vercel.json`: Clean URL and aggressive image caching headers for Vercel Edge CDN.
- `assets/photo-1.jpg`, `photo-2.jpg`, `photo-3.jpg`: Pre-wedding photos displayed in the 3-column triptych.
- `assets/og-cover.jpg`: Open Graph thumbnail preview when sharing the link on Zalo or Messenger.

## How to Deploy to Vercel
1. Extract this `.zip` file on your computer so you have the `wedding-invitation-vercel` folder.
2. Replace `photo-1.jpg`, `photo-2.jpg`, `photo-3.jpg`, and `og-cover.jpg` inside `assets/` with your own high-resolution pre-wedding photos (keep the same file names, or update the `src` attributes in `index.html`).
3. Deploy using either method below:
   - **Method A (Vercel Web Dashboard):** Go to https://vercel.com/new, drag and drop the `wedding-invitation-vercel` folder (or push it to a GitHub repository and import it), and click **Deploy**.
   - **Method B (Vercel CLI):**
     ```bash
     npx vercel --prod
     ```
