RAW TUNE RECORDS — WEBSITE STARTER
Brand: Raw Tune Records featuring Willie Bang

WHAT'S INCLUDED
- Mobile-first dark/gold website
- Album section and tracklist for Cry Now, Laugh Later
- Persistent audio player for album tracks
- Searchable beat preview cards
- Placeholder license links and contact links
- No paid service or account required to edit the files

IMPORTANT LIMITS
- This is a starter website, not yet hosted on the internet.
- No audio is included. Add only music you own or are authorized to stream.
- Beat license buttons are placeholders; they do not charge a customer.
- Do not place untagged paid WAVs or stems in public website folders. Anyone may copy public files.
- No user accounts, protected downloads, subscriptions, or database are included yet.
- Replace REPLACE-WITH-YOUR-EMAIL before publishing.

ALBUM AUDIO
Put MP3 files in assets/audio/albums/ using these exact names:
in-the-dark.mp3
street-credit.mp3
bandit.mp3
forever-mine.mp3
ten-toes.mp3
private-life.mp3
right-now.mp3

BEAT PREVIEW AUDIO
Put tagged preview MP3s in assets/audio/beats/:
midnight-drive-preview.mp3
cold-heart-preview.mp3
pressure-preview.mp3

TEST LOCALLY
Open index.html in a browser. Add audio files first to test playback. If local playback acts differently, test via a local server or after deployment.

PUBLISH FREE (SUGGESTED ROUTE: CLOUDFLARE PAGES)
1. Create a GitHub account and a new repository. Keep in mind the site code is public if you use a public repo; do not upload private masters or sensitive data.
2. Upload index.html and the assets folder to the repository.
3. Create a Cloudflare account and open Workers & Pages > Create application > Pages > Import an existing Git repository.
4. Connect the repository. For plain static HTML, use build command `exit 0` and the folder containing index.html as the build output directory (if the repo root contains index.html, choose `/` or the dashboard's root option).
5. Deploy, then open the provided pages.dev address on your phone and test every link.
6. Read current hosting terms and file/bandwidth limits before serving a large music catalog. A separate audio host/CDN may be needed as listens grow.

SELLING BEATS
Before you accept orders, replace mailto links with real checkout/product links from a beat store or payment provider. Configure the license, verify the customer gets the right deliverables, and run a test purchase. Keep paid master files behind the provider's protected delivery mechanism.

FUTURE APP PATH
First get the mobile website working. Then add a web-app manifest, icons, and service worker for installable PWA behavior. App Store / Google Play distribution is a later phase and has extra review, billing, and maintenance requirements.
