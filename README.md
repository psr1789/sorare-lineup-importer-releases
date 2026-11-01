# Sorare Lineup Importer — releases

Chrome extension that imports a lineup list (JSON) into Sorare's NBA compose page by doing the manual steps for you:
empty slot → search the player → click the exact card → confirm. You review the lineup and submit it yourself.

## Install
1. Download the zip of the [latest release](https://github.com/psr1789/sorare-lineup-importer-releases/releases/latest).
2. Unzip it; you get a `sorare-lineup-importer` folder. Keep it where it is (Chrome loads the extension from it).
3. Chrome → `chrome://extensions` → turn on **Developer mode** → **Load unpacked** → pick that folder.
4. Pin the extension from the puzzle menu to reach its popup (Paste JSON, settings).

## Update
When a new version is out, the extension's icon shows **NEW** and its popup shows a banner.
1. Click **Download** in the banner (or take the zip from the latest release).
2. Unzip it over the same folder, replacing the files.
3. Click **Reload** in the banner, then refresh the Sorare page.

Your list, ✓ marks and settings stay.

## Files here
- `version.json`: the newest version, read by installed extensions to show the update notice. Nothing about you is sent.
- Releases: one zip per version.
