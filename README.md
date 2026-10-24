# Publications page

This site is published free by GitHub Pages. The web page is built
automatically from one list file, `_data/publications.yml`, so you never
need to edit any HTML.

## Add a new publication (from any web browser)
1. On GitHub, open `_data/publications.yml` and click the pencil icon (Edit).
2. Copy the template in the comment block at the top of the file and paste
   it just under the line `# ---- list starts here ----`.
3. Fill in the details, keeping the indentation and the double quotes.
4. Click **Commit changes**. The live page updates within a minute or two.
   The page sorts by year, puts your name in bold, and updates the
   "Last updated" date by itself.

If the page doesn't update, open the **Actions** tab. A red cross means
the list file has a formatting slip (usually a missing quote or wrong
indentation). Click it to see the line number.

## Correct or remove a publication
Edit or delete its block in the same file, then commit.

## Host your own PDF
Upload the PDF into the `papers/` folder (Add file → Upload files), then
set `pdf: "papers/your-file.pdf"` in that paper's entry.

## Change your name, affiliation, profile link or the bold name variants
Edit `_config.yml`.

## Change the look
Edit `assets/style.css`.
