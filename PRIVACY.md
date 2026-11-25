# Privacy — LD Studio

**Summary: the app collects nothing and has no internet permission.**

## Data it handles

- **Tag UID and content**: read on the phone to show information and write the tag. Never sent
  anywhere.
- **Language and UIDs of detected original tags**: stored **locally** in the app WebView
  (`localStorage`) and internal files.
- **Log**: written locally to `filesDir/ldstudio.log` and logcat. You can export it to the app
  folder (`Android/data/io.github.matcarfer.ldstudio/files/exports/`) or share it through Android's chooser,
  only when you ask for it.
- **Diagnostics**: phone model, Android version, app version and tag state. Shown on screen and
  only leaves the device if you export or share it.

## What it does NOT do

- No `INTERNET` permission (not declared in the manifest).
- No analytics, ads, crash reporting or accounts.
- No access to contacts, location, camera, personal files or messages.
- No access to other tags or other phone data.

## Declared permissions

| Permission | Purpose |
|---|---|
| `android.permission.NFC` | Read and write NFC tags. Normal permission (no prompt). |

## Deleting your data

- Uninstalling removes internal logs.
- Exported files remain in `Android/data/io.github.matcarfer.ldstudio/files/exports/` until you delete them.

## Changes

Any change to this policy is published in this repository.

