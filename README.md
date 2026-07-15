# NaPiRE Page

This repository hosts a Jekyll-based website that makes core results of the NaPiRE initiative accessible.
The "Naming the Pain in Requirements" (NaPiRE) initiative aims at describing the contemporary practices and challenges experienced in requirements engineering through global surveys.

## Local preview

`_config.yml` fetches the Cayman theme via `remote_theme`, which needs network access to GitHub and won't work in the devcontainer. For local preview, use the vendored theme gem instead:

```sh
bundle install
bundle exec jekyll serve --config _config.yml,_config.local.yml
```

Then open http://localhost:4000. `_config.local.yml` is for local use only; the production build (GitHub Pages) only reads `_config.yml`.
