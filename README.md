# dimmer-ext-app

Chrome extension that tracks reading time per tab

Built for my own use; public in case it helps someone.

## Highlights

- Popup shows today's total focus time
- Per-tab time persisted to chrome.storage
- Manifest V3, service worker based
- No remote calls, everything stays local

## Getting started

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Usage

```bash
# click the toolbar icon to see today's reading time
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
```
