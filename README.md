# PACE — first working prototype

This is a mobile-friendly Progressive Web App (PWA). It can be hosted as a website and installed from a supported mobile browser.

## Included
- Daily goal checklist with 25 points per goal
- Daily progress bar
- Basic streak counter
- Joinable sample challenges
- Editable local display name
- Sample leaderboard
- PACE Plus preview screen
- Local device storage and basic offline shell caching

## Important limitations
This is an MVP prototype, not a production social network:
- No real sign-in or cloud database
- No real friend connections or live/global leaderboard
- Leaderboard names/scores are sample data
- No automatic step counting, GPS, health-data integration or verified workouts
- No payments or active subscription purchase
- Progress is stored only in the browser/device where it is used

Do not collect sensitive health information from users in this prototype. Before public launch, add secure authentication, a backend database, privacy policy, terms, account deletion, moderation/reporting tools, security review and appropriate age/safety controls.

## Test on your Mac
1. Install a recent version of Node.js if you do not have it.
2. Open Terminal and `cd` into this folder.
3. Run `npx serve .` (or use another static web server).
4. Open the local URL printed in Terminal.

You can also open `index.html` directly to test core functions, but PWA installation/offline features require HTTPS or localhost.

## Publish as a website/PWA (recommended first)
1. Create a GitHub account with a parent/guardian if required by the service's age rules.
2. Create a new repository and upload all files in this folder.
3. Create a Vercel account with the appropriate adult account holder if required.
4. Import the GitHub repository into Vercel.
5. Use the default static deployment settings and deploy.
6. Open the HTTPS URL on your phone.
7. iPhone: open in Safari, tap Share, then Add to Home Screen.
8. Android: open in Chrome, use Install app / Add to Home screen.

See Vite/Vercel deployment documentation if you later convert this into a Vite project:
https://vite.dev/guide/static-deploy
https://vercel.com/docs/deployments

## App Store publishing later
A PWA website is not automatically an App Store or Google Play app. A native wrapper/build and store review are separate steps. Since the founder is under 18, a parent/guardian or eligible legal entity will need to handle store developer enrolment and legal agreements. Confirm the current store rules and fees before paying.
