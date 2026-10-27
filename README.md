# TOMCAT publications page

This site is published free by GitHub Pages. The web page is built
automatically from one file, `_data/publications.csv`, which is a Scopus
CSV export used as-is, so you never need to edit any HTML.

## Turn on the website (once)
1. On GitHub, open **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*,
   pick the `main` branch and the `/ (root)` folder, then **Save**.
3. After a minute or two the site is live at
   `https://<your-username>.github.io/publications/`.

## Update the list
1. In Scopus, select the papers and choose **Export → CSV**. Include at
   least: Authors, Title, Year, Source title, Volume, Issue, Art. No.,
   Page start, Page end, DOI and Link.
2. On GitHub, open the `_data` folder, choose **Add file → Upload files**
   and upload the export renamed to `publications.csv` (it replaces the
   old one).
3. Click **Commit changes**. The live page updates within a minute or two.
   It sorts by year, then first author, and updates the "Last updated"
   date by itself.

Scopus sometimes lists the same paper twice; delete the extra row from the
CSV if you spot one.

If the page doesn't update, open the **Actions** tab. A red cross means the
build failed; click it to see why.

## Change the title, description or the bold name variants
Edit `_config.yml`.

## Change the look
Edit `assets/style.css`.
