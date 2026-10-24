# Banknote Collection

A simple web app for logging banknotes: front and back photos, a reference image, country/territory, value, currency and year. Organise notes into your own folders.

Each person's collection is stored privately in their own browser, so everyone who opens the link gets their own separate collection. Nothing is uploaded anywhere.

## Put it online with GitHub Pages
1. Create a new GitHub repository and upload `index.html` (and this README).
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. After a minute your app is live at `https://<your-username>.github.io/<repo-name>/`. Share that link.

## Using it
- On a phone, open the link and choose **Add banknote**. Tapping a photo box lets you take a picture or pick one.
- Use **Back up** to save your collection as a file, and **Restore** to load it on another device or after clearing browser data.
- Tip: use "Add to Home Screen" for an app-like icon.

## Good to know
- Data lives per browser and device. Clearing site data deletes it, so back up occasionally.

## Auto-fill (free)
1. Each person gets a free key at https://aistudio.google.com/apikey (Google account needed).
2. In the app, open **Settings** and paste the key. It stays in that browser only, never in your repo.
3. In **Add banknote**, add the photos and tap **Auto-fill from photos**. Check the result, then save.
4. Reference images are searched on Wikimedia Commons (free, no key). Tap the one that matches.

If auto-fill stops working, Google may have retired the model name. Put a current free Gemini Flash model name in Settings.
