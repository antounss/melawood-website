# MelaWood Website

Custom woodwork, handmade products & Christmas collection.

## Files
- `index.html` — the whole website (all pages, styles and code)
- `mark.png` — the MelaWood logo mark

## Put it online with GitHub Pages
1. Create a new **public** repository on GitHub (e.g. `melawood`).
2. Click **Add file → Upload files**, drag in `index.html` and `mark.png`, then **Commit changes**.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set Source = **Deploy from a branch**, Branch = **main**, folder = **/ (root)**, then **Save**.
5. Wait 1–2 minutes. Your link appears at the top of that page:
   `https://YOUR-USERNAME.github.io/melawood/`

## Edit business details
Open `index.html`, search for `CONFIG` and change:
- `whatsapp` — number in international format, digits only (e.g. `9613123456`)
- `whatsappDisplay`, `instagram`, `location`, `hours`

## Add real photos
1. Upload photos next to `index.html` (e.g. `kitchen1.jpg`).
2. In `index.html`, find the item in `DESIGNS` or `PRODUCTS` and add `img:"kitchen1.jpg",`
   Example: `{id:'d1', img:'kitchen1.jpg', title:'Oak & Steel Kitchen', ...}`
3. Change names, prices and descriptions in the same lists.
