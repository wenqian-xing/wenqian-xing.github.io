# wenqian-xing.github.io

Personal academic website, built with [Jekyll](https://jekyllrb.com) and hosted on
GitHub Pages at <https://wenqian-xing.github.io>.

No theme gem and no JavaScript — the layouts and the single stylesheet live in
this repository.

## Layout

```
_config.yml            Site settings, author details, build options
_data/navigation.yml   Header links
_layouts/              default (shell), home (front page), page (everything else)
_includes/             head, header, footer
_pages/                about (front page), research, service, 404
assets/css/main.css    The whole stylesheet
images/                Profile photo and favicon
```

## Editing

- **Front page** — `_pages/about.md`. The name, photo and one-line bio beside it
  come from `author:` in `_config.yml`.
- **Research** — `_pages/research.md`. Each entry is a bold linked title, then the
  author list, then italic venue and award lines. Section headings (`## Working
  Papers`) render as small caps rules.
- **Teaching & Service** — `_pages/service.md`.
- **Header links** — `_data/navigation.yml`.
- **Contact links in the footer** — the `author:` block in `_config.yml`; each one
  is omitted if left blank.

## Running locally

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

## License

[MIT](LICENSE). Originally forked from
[academicpages](https://github.com/academicpages/academicpages.github.io).
