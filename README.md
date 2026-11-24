# Jakob Reset

A static fitness and daily-care dashboard designed for GitHub Pages.

## Publish with GitHub Pages
1. Create a new GitHub repository (for example `jakob-reset`).
2. Upload **all files in this folder** to the repository root. `index.html` must be at the root, not inside another folder.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site. Open the URL it gives you.

## Import/export
- `plan.json` is the complete editable plan: schedule, workouts, exercises, instructions, photo search links, demonstration links, daily habits and care guidance.
- In the website, open **Data & settings → Import a plan** to import a replacement plan JSON.
- **Export progress JSON** backs up completed sessions, set records and habit checks.
- **Restore backup** loads a previously exported progress file.
- **Export current plan JSON** downloads the active plan.

## Exercise visuals
Each exercise includes a link to a Wikimedia Commons image search and a YouTube demonstration search. These are external links rather than bundled copyrighted images, so they open in a new tab and can be changed in `plan.json`.

## Data storage
Progress is stored in local browser storage on the device. It is not automatically synced between devices or backed up by GitHub. Export your progress regularly.

## Customize
Edit `plan.json` to change exercise descriptions, sets, reps, rest, schedule, links and daily care. Keep the JSON structure valid.
