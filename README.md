# BridgeHaven Medical Equipment website

Static pre-launch website for BridgeHaven Medical Equipment, LLC (https://bridgehavendme.com).

- `index.html` home page
- `privacy.html`, `terms.html`, `accessibility.html` legal and accessibility pages
- `training/` staff-only Employee Training portal (linked as "Employee Login" in every footer). Settings are at the top of its script: `API_URL` (the Google Apps Script web app address) and `VIDEOS` (one unlisted YouTube video ID per module). Grading, records and email happen in the Apps Script attached to the "BridgeHaven Training Records" Google Sheet, so quiz answers never appear on this site.
- `logo.png`, `logo-mark.png`, `favicon.png` brand images
- `CNAME` tells GitHub Pages the custom domain
- `.nojekyll` tells GitHub Pages to serve the files as they are

No build step, no cookies, no analytics. The public pages make no third-party requests; only `training/` loads YouTube and talks to Google Apps Script. Edit the HTML files directly.

Contact details that appear on the site (update every page if they change):
office phone 757-734-7155, info@bridgehavendme.com, 900 Commonwealth Place, Suite 210, Virginia Beach, VA 23464.

Before changing any claims on the site (accreditation, payer participation, product availability), check that they are true on the day they are published.
