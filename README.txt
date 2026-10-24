World GK Quiz - app package

Files: index.html, privacy.html, manifest.webmanifest, sw.js, icons/ (all must stay together in the same folder).

1) Put the folder online on free HTTPS hosting
   - GitHub Pages: create a repo, upload these files, Settings > Pages > deploy from main branch.
   - or Cloudflare Pages / Netlify: drag and drop the folder.
   You will get a link like https://yourname.github.io/world-gk-quiz/

2) Turn the link into an Android app
   - Open pwabuilder.com, paste your link, press Start.
   - Choose Android > Google Play. Fill in package ID (for example com.yourname.worldgkquiz), app name and version.
   - Download the zip. It contains a signed .aab file (needed for Play Store) and an .apk (for testing on your phone).
   - KEEP the signing key file and its password safe. You need them for every future update.

3) Publish on Google Play
   - Create a Play Console developer account (one-time fee, about $25).
   - Create the app, upload the .aab, add icon, screenshots, short and full description.
   - Add a privacy policy link (a one-page text hosted on your GitHub Pages is enough; this app collects no personal data).
   - New personal accounts must run a closed test with testers for a period before production release. Check the current requirement in Play Console.

4) Before publishing, open privacy.html and replace [add your email address here] with your email. Use the hosted link to privacy.html as the privacy policy URL. Store text is in store-listing.txt.
