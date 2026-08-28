# Yunfei Wang — Personal Website

Source for my academic homepage, built with Jekyll and deployed with GitHub Pages.

The site highlights my work on embodied AI, self-evolving agents, robot learning, publications, selected projects, education, and CV.

## Local development

Install Ruby and Bundler, then run:

```bash
bundle install
bundle exec jekyll serve
```

The site will be available at `http://127.0.0.1:4000/`.

## Deployment

The workflow in `.github/workflows/pages.yml` builds and deploys the site whenever the `main` branch is pushed. In the GitHub repository, set **Settings → Pages → Source** to **GitHub Actions**.

The personal-site URL is configured as:

```text
https://wangyf9.github.io/
```

## Credits

Based on [WowPage](https://github.com/WD7ang/WowPage), which is adapted from the Academic Pages theme. Released under the MIT License.
