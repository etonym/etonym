# Etonym

*mynote, reversed* — your folder, your git, your notes.

Etonym is a note app for a plain folder of Markdown files and git. There is no
server and no account: your notes stay as `.md` files in the folder you pick.

This repository holds release downloads only. Get the latest installer from
[Releases](https://github.com/etonym/etonym/releases/latest).

## What it does

- **Live preview editing** — headings, lists, tables, links and images render
  as you type; the line you are editing shows its Markdown source.
- **Your files stay as they are** — opening and saving never rewrites line
  endings, BOM or spacing, so git shows no changes you did not make. An
  existing Obsidian vault opens as is; `.obsidian` is never read or written.
- **Standard Markdown** — new links and images are relative links that GitHub
  and GitLab display the same way.
- **Mermaid diagrams** drawn inside the app, offline.
- **Git built in** — see what changed, view the diff and commit from the app.
  It uses the git installed on your computer.
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
