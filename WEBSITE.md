# Yan Luo's academic website

Built with the existing AcademicPages template.

## Content

- Home: `_pages/about.md`
- Research: `_pages/research.md`
- Publications: `_pages/publications.html`
- CV: `_pages/cv.md`
- Navigation: `_data/navigation.yml`
- Profile and site settings: `_config.yml`

The personal content is based on `yanluo_site_v1.zip`. Publication metadata is
preserved as supplied; add verified ADS, arXiv, and journal links when available.
Place a CV at `files/Yan_Luo_CV.pdf` to show the download button automatically.
Set `author.avatar` in `_config.yml` when a profile photograph is available.

Template demo pages and collections are excluded from the published site.
The unused talk-location scraper has been removed.

## Preview

With a current Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000. Run `bundle exec jekyll build` to check the build.

## Deployment

The existing `.github/workflows/jekyll.yml` deploys pushes to `master`.
In repository Settings → Pages, select **GitHub Actions** as the source.
The published URL is https://yanluo-astro.github.io.
