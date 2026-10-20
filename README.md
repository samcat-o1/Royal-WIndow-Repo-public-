## Install on an Android phone
1. Open that address in Chrome while the phone has internet.
2. Tap the three-dot menu, then "Install app" (or "Add to Home screen").
3. Open the app once from its new icon. After that it works with no connection.

## Changing the logo later
Replace these files in the `icons` folder, keeping names and sizes:
- `logo-header.png` is the logo shown next to the title inside the app
- `icon-192.png` (192 x 192) and `icon-512.png` (512 x 512) are the home-screen icons
- `icon-maskable-512.png` (512 x 512) is used when Android crops icons into circles or rounded squares. Keep the artwork in the central 60%.

Then open `sw.js`, raise the version name (for example `royal-v2` to `royal-v3`), and upload. You may need to remove and reinstall the app to see a new home-screen icon.

## Updating the app
Edit any file, bump the version name in `sw.js`, and push. Installed copies update the next time they open with internet.

## Install on a phone that is never online
Host the site once, then use PWABuilder (pwabuilder.com) to generate an Android APK from your Pages address. Copy the APK to the phone by USB or SD card and install it.

## Your data
Jobs are stored on each device. Use the Backup tab to copy them between devices or to keep a safe copy.
