# NoobKratos AI Studio

A mobile-friendly frontend prototype for the NoobKratosPlay Roblox Shorts workflow.

## Deploy with GitHub Pages (no Python required)
1. Open this repository's **Settings → Pages**.
2. Under Build and deployment, choose **Deploy from a branch**.
3. Select branch `main` and folder `/(root)`, then Save.
4. Wait for the Pages URL to appear in Settings → Pages.

## Included
- Dark red/black creator dashboard
- Roblox Shorts script starter templates
- Browser-local saved ideas and research notes
- Starter 30-day content planner
- Manual analytics tracker
- CSV export for the calendar
- Quick links to Roblox Charts and YouTube Studio

## Important limitations
This is a static frontend prototype, not a fully autonomous AI agent. It does not yet fetch live trends, call an AI API, generate voice/audio, access private YouTube analytics, upload videos, or run scheduled cloud jobs. Saved data is stored in the browser and does not automatically sync between devices.

To integrate voice generation, first identify the provider and use its official API documentation. Store credentials in backend environment secrets, never in browser code or a public repository. The API key previously pasted in chat should be rotated/revoked.

GitHub Pages hosts static files only. Secure API calls and cloud scheduling require a backend/serverless service.
