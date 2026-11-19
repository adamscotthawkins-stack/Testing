# Fitness

A phone app for training, meals and progress: weekly plan, set logging with
add-weight tips, rest timer, meal plan and recipes, body weight, lift charts,
calendar, badges and daily stretches.

It's a home-screen web app (PWA). No app store is needed, it works offline,
and all data stays on the phone.

## Install on iPhone

1. Open the app's GitHub Pages link in **Safari**.
2. Tap **Share**, then **Add to Home Screen**, then **Add**.
3. Open it from the **Fitness** icon. It runs full-screen like a normal app.

## Your data

Everything is saved on the phone. To keep a copy or move to a new phone, go to
**Tools → Your data → Download backup**, then **Restore from backup** on the new
install. Do this regularly: deleting the app from the home screen deletes its data.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole app |
| `manifest.webmanifest` | App name, icon and full-screen setting |
| `sw.js` | Offline support |
| `icons/` | Home-screen icons |

## Updating

Change `index.html`, then raise `VERSION` in `sw.js` (for example `fitness-v2`)
so phones pick up the new version. Changes show the second time the app is
opened after an update.
