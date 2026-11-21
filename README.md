# CopyPasteWin

**Clipboard manager, notes and top sites — right in your browser. Free, local-only, no account.**

CopyPasteWin is a free clipboard manager browser extension for Microsoft Edge and Google Chrome.
It keeps your last 50 copied items, saves selected text with one right-click, copies page title
and URL in one click, stores up to 10 notes, and shows your top 10 and last 10 visited sites.
All data stays local. No account, no telemetry.

Developed by **David Pirosmani** — [pirosmani.biz/ext](https://pirosmani.biz/ext/)

## Features

| Feature | What it does | Where |
|---|---|---|
| WEB Clipboard | Keeps the last 50 copied items, one click to re-copy | WEB Clipboard tab |
| Save selection | Right-click any selected text to save it | Context menu |
| Copy Page Info | Copies the page title and URL in one click | Context menu |
| My Notes | Pins up to 10 items as permanent notes | My Notes tab |
| My Top-10 | Shows the 10 most visited sites | My Top-10 tab |
| My Last-10 | Shows the 10 recently visited pages | My Last-10 tab |

## Why CopyPasteWin

- **Nothing to lose.** Your last 50 clipboard items stay one click away, in the order you copied them.
- **It cannot read your clipboard in the background.** Browser security rules do not allow any
  extension to silently grab content from the clipboard — so CopyPasteWin takes only what you copy
  yourself. Every item in the list is there because you put it there.
- **The address bar is off-limits too.** Extensions cannot touch it, so your current page URL is
  never collected behind your back.
- **No setup, no account, no cloud.** All data stays in your browser's local storage — nothing is
  sent to any server, ever.
- **30 seconds to install.** Download, unpack, load — and Ctrl+C never loses anything again.

## Privacy

CopyPasteWin never runs in the background watching what you copy. It only stores an item when
**you** copy it — with Ctrl+C, a right-click, or the Copy Page Info menu. Nothing reaches the list
without your explicit action.

- Passwords and card numbers you paste never enter the history unless you copy them yourself
- No clipboard monitoring, no background processes, no telemetry
- All data stays in your browser's local storage — nothing is sent to any server, ever
- One click on "Clear" wipes the list completely

## Installation

1. Download [copypastewin.zip](https://pirosmani.biz/ext/copypastewin.zip)
2. Unpack it to any folder
3. Open `edge://extensions` (or `chrome://extensions`) and enable Developer mode
4. Click "Load unpacked" and select the folder

## Comparison

| | Ctrl+C | Heavy clipboard managers | CopyPasteWin |
|---|---|---|---|
| Clipboard history | One item only | Unlimited, often in the cloud | Last 50 items, local |
| Save selected text | Manual | Yes | One right-click |
| Notes and top sites | No | Usually no | My Notes, My Top-10, My Last-10 |
| Background clipboard monitoring | — | Often yes | None — by browser design |
| Data leaves your device | No | Sometimes (cloud sync) | Never |

## Compatibility

Microsoft Edge, Google Chrome and any Chromium-based browser. Built on Manifest V3.

## FAQ

**Can CopyPasteWin read my clipboard without my knowledge?**
No. Browser security rules prohibit extensions from reading the clipboard silently or in the
background. CopyPasteWin only stores an item at the moment you actively copy it.

**Does CopyPasteWin send my data to a server?**
No. Everything stays in your browser's local storage. Nothing is sent to any server.

**Does it require registration?**
No. No account, no sign-in.

## License

MIT — see [LICENSE](LICENSE).
