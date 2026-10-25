# Etonym

*mynote, reversed* — your folder, your git, your notes.

Etonym is a note app for a plain folder of Markdown files and git. There is no
server and no account: your notes stay as `.md` files in the folder you pick.

This repository holds release downloads only. Get the latest installer from
[Releases](https://github.com/etonym/etonym/releases/latest).

## What it does

- **Live preview editing** — headings, lists, tables, links and images render
  as you type; the line you are editing shows its Markdown source. A
  formatting toolbar is always in view.
- **Tables you can edit in place** — type in cells, and copy or paste cells
  to and from a spreadsheet.
- **Your files stay as they are** — opening and saving never rewrites line
  endings, BOM or spacing, so git shows no changes you did not make. Etonym
  keeps its own data outside your folder. An existing Obsidian vault opens as
  is; `.obsidian` is never read or written.
- **Standard Markdown** — new links and images are relative links that GitHub
  and GitLab display the same way. Find broken links from the command palette.
- **Mermaid diagrams** drawn inside the app, offline.
- **Git in one tab** — review changes, commit and push, fetch and pull,
  switch and merge branches, and resolve conflicts without a terminal. Each
  note has its own history. It uses the git installed on your computer.
- **A terminal and Explorer at hand** — open the OS terminal in your folder
  (for example to run an AI coding assistant), and open folders or notes from
  Explorer with **Open with Etonym**.
- **Copy anywhere** — copying keeps formatting when you paste into a word
  processor or mail. Print a note with `Ctrl+P`.
- **Search** across all notes, and quick open by file name.
- **Works offline** — the network is used only to check for updates.

## Install

Windows 10 or 11 (x64).

1. Download `Etonym_<version>_x64-setup.exe` from the
   [latest release](https://github.com/etonym/etonym/releases/latest).
2. Run it. No administrator rights are needed.
3. If Windows SmartScreen warns about an unrecognized app, choose
   **More info** and then **Run anyway**. The installer is not code-signed yet.
   Each release lists the installer's SHA-256 so you can check the download.

Git features need [Git for Windows](https://git-scm.com/download/win) 2.27 or
later; notes work without it. After installing, right-click a folder or a
`.md` file in Explorer and choose **Open with Etonym** (on Windows 11, under
**Show more options**). Your default app for `.md` files is not changed.

Etonym checks for updates when it starts and about once a day, and installs
one only after you agree. You can turn this off in Settings.

macOS support is planned.

## Privacy

Etonym collects nothing and sends your notes nowhere. See the
[privacy policy](PRIVACY.md).

## License

Etonym is free to use under its license agreement, which the installer shows
and Settings > About contains. The source code is not public.

## Feedback

Report problems or ideas in [Issues](https://github.com/etonym/etonym/issues).
