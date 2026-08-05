# vatra — public site

Public pages for the [vatra](https://github.com/vyshni-labs/vatra-tab-manager)
Chrome extension, served via GitHub Pages. The extension source lives in a
separate repository.

| Page | Purpose |
|------|---------|
| `index.html` | Landing page |
| `privacy.html` | Privacy policy — the URL given to the Chrome Web Store |
| `uninstall.html` | Exit survey opened by `chrome.runtime.setUninstallURL` |

Static HTML/CSS with no build step and no third-party scripts. The only
network call is the exit survey's form POST, and only when a visitor
submits it.

© 2026 Vyshni labs
