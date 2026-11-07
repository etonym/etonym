# Etonym Privacy Policy

Last updated: November 7, 2026

Etonym is a note-taking application that runs on your device. This policy describes what the application (the "Software") does with information. In short: it collects nothing, and your notes never leave your device unless you send them somewhere yourself.

## 1. What We Collect

Nothing. The Software has no account, no usage statistics, no analytics, no crash or error reporting and no advertising. We do not receive your notes, file names, folder names or settings.

## 2. Where Your Data Stays

Your notes and attachments stay in the folders you open. The Software does not add its own files to them, with one exception: when you continue a Git rebase in the Software and choose to include your other edits, it keeps a copy of those edits in Git's own rebase folder inside ".git", so that cancelling the rebase can put them back. That folder goes away when the rebase ends.

The Software keeps its own data on your device only:

- (a) for each folder you open, a search cache, which holds a copy of the text of its notes, and the last open note with its cursor position, in the application data folder of your operating system. When a folder leaves the list of folders, this data is deleted;
- (b) the list of folders you opened, your settings, the window size and position, and copies of this policy, the license agreement and the open-source notices once you open them from Settings, in the same folder; and
- (c) an error log in the application log folder of your operating system. The log holds error codes, file and folder paths and program messages, including the error output of Git and of any Git hooks you set up. The Software does not write the text of your notes to it, but a hook that prints note text puts that text in the log. The log is never sent anywhere. You can open its folder from Settings > About > Log folder, and read it before you share it with anyone.

## 3. When the Software Uses the Network

The Software does not need the network to open, edit or display notes, including diagrams. It connects to the network only in these cases:

- (a) Update check. Unless you turn off "Check for updates" in Settings, the Software downloads a small public file describing the latest version when it starts and about once a day. The request names no note, file, account or device identifier. Like any web request, it reveals your IP address and the time of the request to the server that hosts the updates (currently GitHub, see https://docs.github.com/site-policy for its privacy statement). If you install an update, the installer is downloaded from the same server.
- (b) Git. When you run Git commands that contact a remote repository, Git exchanges your notes with that repository as you instructed. Cloning downloads from the address you enter. When you open a folder or its Git tab, the Software also asks Git to fetch from the remote that the current branch tracks, which only downloads. The Software does not choose or add any remote; Publish adds the address you enter. Signing in to a remote is handled by Git and its credential manager, under their own settings.
- (c) Links. When you open a web or email link in a note, it opens in your default browser or mail program, which follows its own policy. When Git is missing or too old and you choose Install Git, the Software opens the Git download page (https://git-scm.com/downloads) in your browser.

Pictures and other content that a note or an HTML file links to on the internet are not loaded.

When you open a terminal from the Software, the programs that you run in it use the network under their own settings and policies. The Software neither starts nor sees that traffic.

Your operating system and its components (for example, Microsoft Edge WebView2 on Windows) may connect to their own services under their own settings and policies. The Software does not send your notes to them.

## 4. Children

The Software collects no information from anyone, including children.

## 5. Changes and Contact

We may publish a new version of this policy with a later version of the Software. Questions can be sent through the issue tracker at https://github.com/etonym/etonym/issues.
