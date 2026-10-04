Hamro G&G Auto - iOS .ipa (website untouched; app loads auto-stock-manager.vercel.app)

1. Create a GitHub repo, upload everything in this folder (keep .github/workflows/build-ios.yml).
2. Repo -> Actions -> "Build iOS IPA" -> Run workflow. Wait ~5-10 min.
3. Download the artifact "HamroGnGAuto-ipa" (zip containing HamroGnGAuto.ipa).
4. On Windows: install Sideloadly (needs iTunes + iCloud from apple.com, not Microsoft Store),
   plug in iPhone, drag in the .ipa, sign in with your Apple ID, Start.
5. iPhone: Settings -> General -> VPN & Device Management -> trust your Apple ID.
   Turn on Developer Mode (Settings -> Privacy & Security) if asked.

Free Apple ID: app expires after 7 days, re-sign with Sideloadly. Max 3 apps.
Paid account ($99/yr): lasts 1 year / TestFlight.
