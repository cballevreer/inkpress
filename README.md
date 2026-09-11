# inkpress

Static blog generator: markdown in, tidy HTML out

Side project, maintained when I have time.

## What it does

- Index page with post list by date
- RSS feed generation
- Single template, plain str.format, no Jinja
- Markdown posts with fenced code and tables

## Installation

```bash
pip install -r requirements.txt
```

## Examples

```bash
mkdir posts && echo '# hello' > posts/first.md
python build.py
# site lands in dist/
```

## Project structure

```text
├── .github/
│   ├── workflows/
│   │   └── ci.yml
│   └── dependabot.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   └── usage.md
├── .gitignore
├── CHANGELOG.md
├── LICENSE
├── SECURITY.md
├── build.py
└── requirements.txt
```

## Why

Needed this for myself; figured others might too.

## License

MIT - see [LICENSE](LICENSE).
