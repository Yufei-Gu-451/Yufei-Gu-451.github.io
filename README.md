# Yufei Gu's Personal Website

Source for my personal academic site: [yufei-gu-451.github.io](https://yufei-gu-451.github.io).

It hosts my biography, research interests, publications, notes, curated reading lists, and CV / contact details. The site is built with [Jekyll](https://jekyllrb.com/) on top of the [`minima`](https://github.com/jekyll/minima) theme and is deployed via GitHub Pages.

## Local development

Requires Ruby (see `.ruby-version`) and Bundler.

```bash
bundle install
bundle exec jekyll serve --livereload
```

The site is then available at `http://localhost:4000`.

## Project layout

```
.
├── _config.yml             # Jekyll configuration, header pages, collections
├── _includes/header.html   # Site-wide navigation
├── _layouts/               # Custom layouts (e.g. reading-list.html)
├── _reading_lists/         # Reading-list collection (one file per list)
├── assets/main.scss        # Custom styles layered on top of `minima`
├── index.md                # Home page (hero, news, highlighted work)
├── publications.md         # Publication list
├── blogs.md                # Notes index (rendered at /notes/)
├── reading-lists.md        # Reading lists index (/reading-lists/)
├── cv.md                   # CV & Contact page
├── cv/                     # Embedded CV PDF viewers (English / Chinese)
├── blogs/                  # Long-form notes
├── prompts/                # Drafting prompts kept under version control
└── logos/                  # Affiliation logos used on the home page
```

## Adding content

- **Publication.** Edit `publications.md` and add an entry under the appropriate section.
- **Note.** Add a new directory under `blogs/` for the post and link it from `blogs.md`.
- **Reading list.** Copy `_reading_lists/_TEMPLATE.md` to a new file in `_reading_lists/`, fill in the front matter (`title`, `subtitle`, `status`, `date`), and the list will appear automatically on `/reading-lists/`.
- **News update.** Add a `<li>` to the `Recent Updates` list in `index.md`.
- **CV.** Education, internships, and personal CV links live in `cv.md`; contact and social media now live as sections on the same page.

## Deployment

Pushes to `main` are built and served by GitHub Pages — no manual deploy step required.

## License

Code is released under the MIT License (see `LICENSE`). Written content (publications, notes, CV) is © Yufei Gu and is not covered by that license.
