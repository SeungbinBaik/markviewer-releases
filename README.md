# MarkViewer

> **Free, native Markdown viewer and editor for macOS.**
> Open `.md` files instantly with live WYSIWYG and an auto table of contents.
> Optionally, run the Claude Code or Codex CLI already on your Mac to draft or
> revise a document — and review the diff before anything is applied. 100% offline. Free.

[![Latest Release](https://img.shields.io/github/v/release/SeungbinBaik/markviewer-releases?label=download)](https://github.com/SeungbinBaik/markviewer-releases/releases/latest)
[![macOS](https://img.shields.io/badge/macOS-10.15%2B-blue)](https://markviewer.com)
[![Website](https://img.shields.io/badge/site-markviewer.com-2563eb)](https://markviewer.com)
[![Buy Me a Coffee](https://img.shields.io/badge/support-MarkViewer-FFDD00?logo=buy-me-a-coffee&logoColor=000)](https://www.buymeacoffee.com/markviewer)

![MarkViewer screenshot](https://markviewer.com/assets/screenshot-v2.png)

## Why MarkViewer

Double-click a `.md` file and it opens rendered — no workspace, no project, no configuration. That is the whole core of the app, and it is useful on its own.

If you also work with AI tools, two optional layers sit on top:

**Ask Agent** — describe a change and let an agent make it. MarkViewer detects the Claude Code or Codex CLI you already have installed and runs the task there. The agent works on an isolated copy of the folder; your file changes only after you review the diff and click Apply. No API key, no account setup.

**Review Loop** — for docs an agent already wrote:

- `⌘⇧R` — leave an inline review comment on selected text
- Resolve comments with an agent in place, or `⌘⇧↵` to open an editable prompt panel pre-filled with your annotations
- Paste into Claude, ChatGPT, Cursor, Gemini, Copilot — anywhere that takes text
- Annotations persist as HTML comments inside the markdown — no lock-in

## Quick start

1. **[Download `MarkViewer.dmg`](https://github.com/SeungbinBaik/markviewer-releases/releases/latest)** — Universal binary, signed & notarized
2. Drag to `Applications` and launch
3. Double-click any `.md` file — or set MarkViewer as your default app for `.md`

Or install with [Homebrew](https://formulae.brew.sh/cask/markviewer) — MarkViewer is in the official cask repository, so no tap is needed:

```sh
brew install --cask markviewer
```

## Features

- **Real-time WYSIWYG markdown** — type and render in one view, no preview pane to toggle
- **GitHub Flavored Markdown** — tables, task lists, code highlighting, Mermaid diagrams
- **Ask Agent** — run your local Claude Code or Codex CLI on a document; review the diff before it lands
- **AI Review Loop** — annotate + resolve with an agent, or hand off to any AI assistant
- **Auto Table of Contents** — navigate long documents from the left rail
- **Multi-tab & multi-window** — review several files side by side
- **100% offline** — MarkViewer holds no API key and uploads nothing; agents run locally under your own CLI login

## Compared to alternatives

| Alternative | Best for | Where MarkViewer fits |
|---|---|---|
| Full-featured markdown editors | Long-form writing | Lightweight preview without the weight |
| Code editors with markdown plugins | Devs already in an IDE | Sub-second launch, no workspace to load |
| Browser-based previewers | One-off rendering | Fully offline — files stay on your Mac |
| macOS Quick Look | Plain-text glance | Real GFM rendering plus AI handoff |

## Privacy

- 100% offline operation. No file content, paths, or names ever leave your Mac.
- Anonymous usage analytics are **opt-in** (Settings → Privacy & Analytics).
- Full policy: https://markviewer.com/privacy

## Links

- Website — https://markviewer.com
- Releases — https://github.com/SeungbinBaik/markviewer-releases/releases
- Issues — https://github.com/SeungbinBaik/markviewer-releases/issues
- Support — https://www.buymeacoffee.com/markviewer

## License

MarkViewer is proprietary software. All rights reserved.
