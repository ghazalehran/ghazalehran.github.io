# Ghazaleh Ranjbaran Personal Site

This repository contains the source for `ghazalehran.github.io`, a Jekyll-based personal website for portfolio, publications, blog posts, and resume content.

## Stack

- Jekyll
- GitHub Pages
- Vendored Minimal Mistakes theme files

The site keeps the Minimal Mistakes layouts, includes, Sass, and JavaScript in-repo so the content and presentation can be customized directly without depending on a remote theme.

## Main Content Files

- `index.md`: homepage
- `about.md`: about page and contact form
- `portfolio.md`: featured project page
- `publications.md`: publications page
- `resume.md`: resume page
- `assets/images/`: page and project images

## Local Development

Install Ruby gems:

```bash
bundle install
```

Run the site locally:

```bash
bundle exec jekyll serve
```

Then open `http://localhost:4000`.

## Notes

- The theme source is vendored into `_layouts`, `_includes`, `_sass`, and `assets/js`.
- Most page-level styling currently lives inline inside the Markdown pages.
- Comments are disabled; the contact form is handled through Formspree on the About page.

## Cleanup Decisions

Kept:

- Site content pages and posts
- Theme source files required for rendering
- Images and front-end assets used by the site
- `LICENSE`, because the repository contains vendored open-source theme code

Removed:

- Upstream theme README and build scaffolding
- Obsolete Travis CI config
- Placeholder portfolio collection entries not used by the live pages
- Staticman sample configuration
