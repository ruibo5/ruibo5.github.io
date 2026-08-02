# Ruibo Duan Homepage

Personal academic website built with Jekyll and published with GitHub Pages.

## Local Development

Use Ruby 3.x. The current lockfile was generated with Bundler 2.7.1.

```
gem install bundler:2.7.1
bundle install
bundle exec jekyll serve --livereload
```

Then open `http://localhost:4000`.

## Deploy

Push the repository to `ruibo5.github.io` and enable GitHub Pages with **GitHub Actions** as the source. The workflow in `.github/workflows/deploy.yml` builds the site and deploys it automatically.

## Edit Content

Main homepage content lives in `index.md`. Site-wide metadata such as name, email, and URL lives in `_config.yml`.
