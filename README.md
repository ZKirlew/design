# Zayna Kirlew · Graphic Design Portfolio (Healthcare)

A second version of my portfolio, tailored to graphic design roles in healthcare.
Plain HTML/CSS with no build step, hosted with GitHub Pages at:

**https://zkirlew.github.io/design/**

My main UX/product portfolio stays at https://zkirlew.github.io and is not affected.

## What's in here

```
index.html                 Home: hero, selected work, 3D band, contact
about.html                 About page
projects/coucou.html       Case study 01 · Brand identity (featured)
projects/bee-well.html     Case study 02 · Health app visual system
projects/medportal.html    Case study 03 · Healthcare information design
projects/cyberdream.html   Case study 04 · Illustration, 3D & texture painting
assets/css/style.css       All styling (colors live at the bottom as variables)
assets/js/main.js          Footer year, email menu, video autoplay
assets/img/                Images
assets/Zayna-Kirlew-Resume.pdf   Resume (replace with a file of the same name)
```

All links and image paths are relative, so the site works inside the `/design/` folder.

## Putting it live (one time)

1. On GitHub, click **New** (green button) to create a repository.
   - Name it **`design`**. The name becomes the web address.
   - Set it to **Public**, leave "Add a README" unchecked, and click **Create repository**.
2. Unzip `design-site.zip` on your computer.
3. On the new repository page, click **"uploading an existing file"**.
4. Open the unzipped folder and select **everything inside it** (`index.html`, `about.html`, `README.md`, and the `projects` and `assets` folders), not the folder itself.
   Drag the selection onto the GitHub upload page. The upload is 79 files, under the 100-file limit.
5. Wait until every file is listed, then click **Commit changes**.
6. Check that `index.html` sits at the top level of the repository, next to the `assets` and `projects` folders.
   If everything ended up inside a `design-site` folder, the folder was dragged instead of its contents. Delete it and repeat step 4.
7. Go to **Settings → Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, Branch to **main** and the folder to **/ (root)**, then click **Save**.
8. After a minute or two, visit **https://zkirlew.github.io/design/**.

Tip: if dragging folders doesn't work in your browser, use Chrome or Edge, which keep the folder structure on upload.

## Updating later

- **Text:** open the file on GitHub, click the pencil icon, edit and commit.
- **Resume:** upload your new PDF into `assets/` with the exact name `Zayna-Kirlew-Resume.pdf`. It replaces the old one.
- **After changing CSS or JS:** in every HTML file, change the `?v=20261125b` stamps to a new value (e.g. `?v=20261201a`) so browsers fetch the new version.
