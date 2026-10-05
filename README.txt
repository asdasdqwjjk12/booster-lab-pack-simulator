Booster Lab — online Google Sites + jsDelivr export

IMPORTANT — photos and local pack opening can be updated through GitHub now.
Friend trading separately requires publishing the updated Booster Lab backend
to Replit. A healthy public app URL does not prove its trading routes exist:
an older deployment can load while lacking those routes. Until the updated
backend is live, the game keeps friend trading disabled for save safety.

The CDN hosts only the Booster Lab frontend and static game images. Anonymous
online trading requires the updated live backend at https://fair-trade-forge.replit.app. This embed is
for anonymous guest trading only. Live account sign-in and account-specific
features are separate: the Google Sites code does not embed Clerk or a live
account session. Use the live Booster Lab app for account-based features.
All money, grading and rewards are simulated gameplay, not real transactions.

The Google Sites document is configured for anonymous online use. It initializes
BOOSTER_EMBEDDED_GUEST=true, BOOSTER_OFFLINE=false, BOOSTER_API_BASE=https://fair-trade-forge.replit.app,
and BOOSTER_ASSET_BASE=https://cdn.jsdelivr.net/gh/asdasdqwjjk12/booster-labpokemon@main/

Update an existing public repo (small ZIP):
1. Uploading the game/photo fix does not require waiting for Replit publishing.
   To enable friend trading too, publish the updated Replit backend and wait
   until its guest-trading routes are live.
2. Extract booster-lab-jsdelivr-online.zip and upload its new versioned .js and .css files
    and all included pack-photo files to the ROOT of https://github.com/asdasdqwjjk12/booster-labpokemon. Upload
   google-sites-embed.html and embed-code.txt for your records.
3. Keep older versioned JS/CSS files: an already-published embed may still use
   one of those immutable URLs. Do not rename the new files to booster-lab.js/css.
4. Paste all of embed-code.txt in Google Sites: Insert > Embed > Embed code.
   The document includes a viewport meta tag and a small iframe-safe reset.
   Set the Sites embed tall enough for the app and publish.
5. Open the newly published page and test embedded anonymous trading. The
   backend must allow requests from the published site's origin.

To open the game directly through jsDelivr instead of Google Sites, upload
booster-lab.svg to the repository root, then open:
https://cdn.jsdelivr.net/gh/asdasdqwjjk12/booster-labpokemon@main/booster-lab.svg#/
For this update, use the cache-safe versioned link:
https://cdn.jsdelivr.net/gh/asdasdqwjjk12/booster-labpokemon@main/booster-lab.14b631e4fdcd.svg#/
Open this as a webpage, not as an image element: scripts are disabled when SVG
is loaded through an img tag. The SVG launches the same online guest frontend
inside a regular HTML frame; the live backend is still required for trading.

For a mounted QA preview, place local-preview.html and its hashed JS/CSS files
beside one another at /cdn-check/. It uses this repo's CDN as its image base, so
the two large image folders do not need to be copied to the web app.

The small update ZIP includes pack photos at its root. Upload those files with
the new JS, CSS and SVG. Crown Zenith scans now also load from the repository
root, matching the flat upload layout. The full ZIP includes all 230 root-level
scans. The three crown-image batch ZIPs can be uploaded separately in smaller
batches. Upload their image FILES at the repository root, not inside a folder.


NEW REPOSITORY / COMPLETE FILE PACKAGE
Extract the full ZIP, then upload the CONTENTS of booster-lab-jsdelivr-online to your new
repository root (not the outer booster-lab-jsdelivr-online folder). Include all root files.
All 230 Crown Zenith scans and the pack photos are now root-level files.
No image folders are required for the CDN game. Do not rename the card images.
If uploading through GitHub's browser, use the small game update ZIP plus the
three crown-image batch ZIPs; each image batch contains fewer than 100 files.

The SVG launcher automatically uses the repository URL it was opened from:
https://cdn.jsdelivr.net/gh/asdasdqwjjk12/booster-labpokemon@main/booster-lab.14b631e4fdcd.svg#/
You do not need to edit the SVG or JavaScript for the new repository.
index.html also works with relative assets on GitHub Pages or another static host.
jsDelivr serves HTML as text, so open the SVG when using jsDelivr directly.
Google Sites embed-code.txt is already configured for https://github.com/asdasdqwjjk12/booster-labpokemon.
Trading still uses the existing published Replit backend, not GitHub.
