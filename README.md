<p align="center"><img src="https://raw.githubusercontent.com/go-ruby-shellwords/brand/main/social/go-ruby-shellwords.png" alt="go-ruby-shellwords/go-ruby-shellwords.github.io" width="720"></p>

# go-ruby-shellwords.github.io

The organization's institutional landing page, served at
<https://go-ruby-shellwords.github.io> and built with [Hugo](https://gohugo.io). It
is a single page (custom `layouts/index.html`, capability cards driven by
`[[params.phases]]` in `hugo.toml`).

Documentation lives in a separate repository,
[go-ruby-shellwords/docs](https://github.com/go-ruby-shellwords/docs), served at
<https://go-ruby-shellwords.github.io/docs/>. This page links there.

`.github/workflows/deploy-pages.yml` builds the landing with Hugo and deploys it
to GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
