# Minseob Kim Academic Website

This repository contains Minseob Kim's personal academic website, built from the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template.

## Content

* Home: `_pages/about.md`
* Research: `_pages/research.md`
* Projects: `_pages/projects.md`
* CV: `_pages/cv.md`
* Profile photo: `images/profile.jpg`
* PDF CV: `files/Minseob_Kim_CV.pdf`

## Local Preview

Academic Pages is a Jekyll site. If Ruby and Bundler are installed, run:

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open `http://localhost:4000`.

Alternatively, with Docker Desktop running:

```bash
docker compose up --build
```

## GitHub Pages Deployment

1. Create a GitHub repository named `MinseobKimm.github.io`.
2. Push this repository's `main` branch to `https://github.com/MinseobKimm/MinseobKimm.github.io.git`.
3. In GitHub, open **Settings > Pages** and select **Deploy from a branch**.
4. Use branch `main` and folder `/ (root)`.
5. The site URL will be `https://minseobkimm.github.io`.
