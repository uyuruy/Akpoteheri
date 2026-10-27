# Akpoteheri Tony Usiaphre | Separate Professional Portfolio

**Intended website:** `https://uyuruy.github.io/Akpoteheri/`  
**GitHub repository to create:** `https://github.com/uyuruy/Akpoteheri`  
**Status:** Prepared locally, not published yet.

This is a **separate GitHub Pages project**. It does not replace, modify, or share source files with your existing `https://uyuruy.github.io/Tony/` portfolio.

## Required folder structure

```text
Akpoteheri/                 ← all these files go in the ROOT of the NEW repository
├── index.html              ← website homepage
├── .nojekyll               ← tells GitHub Pages to serve files directly
├── README.md               ← this deployment guide
└── images/
    ├── PHOTO_UPLOAD_INSTRUCTIONS.txt
    └── profile-picture.jpg ← YOU UPLOAD THIS FILE; currently not included
```

### Exactly where to upload your photo

1. Open your NEW GitHub repository: `github.com/uyuruy/Akpoteheri`.
2. Open the `images` folder, which is included in this package.
3. Select **Add file → Upload files**.
4. Upload a real portrait photograph named **`profile-picture.jpg`**.
5. Select **Commit changes**. Refresh the new portfolio address after GitHub Pages deploys.

The website's photograph code points to **`images/profile-picture.jpg`** relative to the new project's own homepage. It makes *no requests* to `uyuruy/Tony` for that image. Until you upload your photo, the existing image card displays the initials **ATU**. There is no broken photo display. Do not merely rename a PNG file to JPG: export/convert it to JPEG first.

### How to create and publish the separate website

1. Sign in to your GitHub account `uyuruy`.
2. Select **New repository**. Enter the name **`Akpoteheri`**. Set visibility to **Public** (for GitHub Free Pages). Create the repository. *Do not use the existing `Tony` repository.*
3. Extract this ZIP on your computer. Open its `Akpoteheri` folder. The separate `supporting` folder contains your LinkedIn copy and Loom script; **do not upload that supporting folder to GitHub**. Upload the **contents of that folder**, not the folder as a nested directory, into the root of the new GitHub repository. GitHub's file uploader can accept multiple files/folders by dragging the extracted items. Ensure `index.html` is visible in the repository root.
4. In the NEW repository, open **Settings → Pages → Build and deployment**. Choose **Deploy from a branch**, choose **main**, folder **/(root)**, and save.
5. Open `https://uyuruy.github.io/Akpoteheri/` after GitHub Pages is published.
6. Upload your portrait as described above, if not already uploaded.
7. Update the LinkedIn portfolio link and LifeBank Featured link to the new address when it works.

## Independent website versus external examples

The portfolio's HTML, CSS, JavaScript, case-study popups and photo path are self-contained in **Akpoteheri**. Nothing is copied into or updated in the `Tony` repository.

**One outbound example link intentionally remains:** the Psalms live dashboard, which currently lives at `https://uyuruy.github.io/Tony/psalms/ops-dashboard.html`. It is merely a clickable reference to an existing published project and does not modify it. If you later want the dashboard hosted here too, that would require its own separate migration and technical check; copying a link does not move it.

Other external proof links are the supplied Loom walkthrough, official LifeBank OneSystem, Notion case study, leadership-course Dropbox PDF and YouTube project videos. These are external links, not website asset dependencies. Check their public viewing permissions.

## No changes to the old portfolio

- Existing repository: `uyuruy/Tony` — **unchanged**.
- New repository (to create): `uyuruy/Akpoteheri` — **entirely separate**.
- Old website: `https://uyuruy.github.io/Tony/` — **unchanged**.
- New website after publishing: `https://uyuruy.github.io/Akpoteheri/`.

## Quick quality checks

- Homepage portrait card displays ATU until `images/profile-picture.jpg` is uploaded.
- Click the LifeBank programme cards to open the SmartBank and OneSystem/OneBox project details and videos.
- Open the CarMinds Loom link, the official OneSystem site, the Psalms Notion case study and its dashboard.
- Open both desktop and mobile view before adding the public portfolio link to LinkedIn.
- Once published, confirm the link and image work in an incognito/private browser window.
