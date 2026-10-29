# TOMCAT publications page

Live at https://tomcat-ctm.github.io/publications/

The page is built automatically by GitHub Pages from one file,
`_data/publications.csv`, which is a Scopus CSV export used exactly as
Scopus produces it. You never need to edit HTML or YAML to add papers.

## Update the list (about 2 minutes, all in a web browser)
1. **Scopus:** run the TOMCAT search (save it once in Scopus so it is one
   click next time), select all results, choose **Export → CSV**, and tick
   **Citation information** (the default set). Download the file.
2. **Rename** the downloaded file to `publications.csv`.
3. **GitHub:** open the repository, click into the `_data` folder, then
   **Add file → Upload files**, drop in `publications.csv` and click
   **Commit changes**. It replaces the old file.
4. Wait a minute or two and reload the site. The paper count, year links and
   "Last updated" date change by themselves.

The CSV in the repository is the same file you use in Scopus for metrics and
plots, so the website and your Scopus numbers stay in step.

If the page doesn't update, open the **Actions** tab. A red cross means the
build failed; click it to see why. The usual cause is a file that is not a
Scopus CSV export, or one re-saved by Excel (if you must open it in Excel,
save it as "CSV UTF-8").

## Hide a duplicate or junk record
Scopus sometimes lists the same paper twice. Find the extra row in
`_data/publications.csv` and copy its EID (the last column, like
`2-s2.0-85054834664`). Add it to `hide_eids` in `_config.yml` (pencil icon →
edit → **Commit changes**). Hidden records stay hidden in every future
export, so you only do this once per record.

## Change the title or description
Edit `_config.yml`.

## Change the look
Edit `assets/style.css`.
