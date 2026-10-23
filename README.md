# Floris Zoutman academic website

This is a static GitHub Pages site. Edit academic text and links directly in `index.html`; layout and colors live in `style.css`. No build step or JavaScript is needed.

## Editing papers and publications

Each paper is an `<article class="card">` inside the Working Papers or Selected Publications section of `index.html`. Copy an existing article, then edit its title, description, and links. The layout changes automatically: two columns on desktop and one on mobile.

## Profile photograph

Add the profile photo as `images/photo.jpg` in the repository. The page is already set to use that local path.

Some research PDFs still use their existing Dropbox links. Review those links when updating academic content.

PDFs hosted directly by the site can go in `documents/` (for example, `documents/cvzoutman.pdf`). Use that relative path when linking to them from `index.html`.

## Preview and publish

Open `index.html` locally to preview the site. Before publishing, check narrow and wide screens, keyboard focus, section navigation, and the photo in Safari, Firefox, Chrome, and Edge. Commit and push the files only after reviewing the local result.
