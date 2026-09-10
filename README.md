# mdfolio

My tiny static site generator, ~100 lines of Python

Started as a weekend hack, grew on me.

## How to use

```bash
mkdir posts && echo '# hello' > posts/first.md
python build.py
# site lands in dist/
```

## What it does

- Single template, plain str.format, no Jinja
- Markdown posts with fenced code and tables
- Index page with post list by date
- RSS feed generation

## Installation

```bash
pip install -r requirements.txt
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
│   └── roadmap.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── build.py
└── requirements.txt
```
