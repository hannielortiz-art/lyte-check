# Lyte Check

Bedside ICU electrolyte replacement from the hospital's non-cardiac ICU protocol: K, Mg, Phos and Ca doses for each route (PO, IV central, IV peripheral), dose times you can tick off, and recheck times from the monitoring tables. Tabs along the bottom: Home, Labs, Give, Ref.

The flags are prompts, not orders. The provider's orders and the unit's protocol decide what is given. Nothing is sent anywhere; numbers stay on the device until you tap Clear.

## Put it online (GitHub Pages, free)

Easiest on a computer.

1. Sign in at github.com (or create a free account).
2. Top right: **+** → **New repository**. Name it `lyte-check`, set it to **Public**, and click **Create repository**.
3. On the next page, click **uploading an existing file**. Drag in **all the files from this folder** (not the folder itself), then click **Commit changes**.
4. Go to **Settings** → **Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, Branch to **main** and folder to **/ (root)**, then click **Save**.
5. Wait 1–2 minutes. The address appears at the top of the Pages screen: `https://YOUR-USERNAME.github.io/lyte-check/`

## Put it on your iPhone

1. Open that address in **Safari** (or Chrome), and wait until the page has fully loaded once. That is when it saves itself for offline use.
2. Tap **Share** → **Add to Home Screen** → **Add**. It gets the LYTES icon and opens full screen.

## Put it on your computer

The same address works on a computer: a wider screen keeps Home on the left and shows the other tabs on the right.

- **Chrome or Edge (Mac or Windows):** open the address, then click the install icon at the right end of the address bar (or menu → **Cast, save and share** → **Install page as app**). It opens in its own window and works offline.
- **Safari on a Mac:** open the address, then **File** → **Add to Dock**.

The phone and the computer each keep their own data; they don't sync.

## Updating it

Upload the new files to the same repository (they replace the old ones). Each update changes `VERSION` at the top of `sw.js`; that is what tells phones to fetch the new version. Open the app once while online to pick it up.

## Files

- `index.html` – the app
- `manifest.webmanifest`, `*.png` – app name and icons
- `sw.js` – offline support
- `*.woff2` – fonts (SIL Open Font License; see the `OFL-*.txt` files)
- `LICENSE.md` – license: original content CC BY-NC-ND 4.0; the protocol belongs to Reston Hospital Center; code all rights reserved

## License

© 2026 Hanniel G. Ortiz. The app's original content is licensed under [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/). The protocol's ranges, doses and tables belong to Reston Hospital Center and are not covered. The software code is all rights reserved. Not affiliated with or endorsed by Reston Hospital Center or HCA Healthcare. See `LICENSE.md`.
