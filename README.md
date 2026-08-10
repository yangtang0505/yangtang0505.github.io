# yang-tang.net

Personal academic website of Yang Tang (Nanyang Technological University),
rebuilt as a plain static site after Weebly wound down service in Singapore.

## Structure

- `index.html` — home page (bio, photo, contact)
- `research.html` — working papers and publications
- `cv.html` — CV download page
- `papers/` — paper PDFs and CV (`cv_yang.pdf`)
- `assets/` — photo
- `style.css` — all styling
- `uploads/6/9/4/4/69446089/` — copies of the PDFs at their old Weebly paths,
  so links to the old URLs keep working once the domain points here
- `CNAME` — custom domain for GitHub Pages

## Editing

Everything is plain HTML — open a page, edit the text, save, commit, push.
Common tasks:

- **Add a paper**: copy an existing `<li>...</li>` block in `research.html`
  and edit the title, coauthors, and journal. Put the PDF in `papers/` and
  link it as `papers/filename.pdf`.
- **Update the CV**: replace `papers/cv_yang.pdf` with the new file
  (keep the same filename).
- **Change the photo**: replace `assets/yang-tang.png`.

Or just ask Claude Code to make the change.
