# vaisvila.github.io

Personal academic website of **Alexander Vaisvil**, Lead Biometrician and Population Modeler with the California Department of Water Resources.
Live at <https://vaisvila.github.io>.

The site is built with [Jekyll](https://jekyllrb.com/) and hosted on GitHub Pages. It is based on the
[academicpages](https://github.com/academicpages/academicpages.github.io) template, a fork of the
[Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme (MIT License, see `LICENSE`).

## Where the content lives

| What | Where |
| --- | --- |
| Site settings, sidebar profile, social links | `_config.yml` (`author:` block) |
| Top navigation menu | `_data/navigation.yml` |
| Home page (About) | `_pages/about.md` |
| CV | `_pages/cv.md` (publications and talks are pulled in automatically) |
| Publications (one Markdown file each) | `_publications/` |
| Talks and posters (one Markdown file each) | `_talks/` |
| Images (profile photo, etc.) | `images/` |
| Downloadable files (PDFs) | `files/` → served at `/files/<name>` |

To add a publication or talk, copy an existing file in `_publications/` or `_talks/`, rename it with the
date prefix, and edit the front matter. It will appear on its list page and on the CV.

## Run locally

Requires Ruby and Bundler.

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>. Restart the server after editing `_config.yml`.

## Deploy

Push to the `master` branch; GitHub Pages rebuilds the site automatically.
