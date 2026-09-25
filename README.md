# Launcher Meetings

A Windows application that opens a Zoom meeting via link or ID and creates a desktop shortcut for it.

> **Disclaimer:** This is an independent application. It is not affiliated with, sponsored by, or endorsed by Zoom Video Communications, Inc.

## Features

- **Link & ID Parsing:** Accepts a Zoom link, Meeting ID, or full invitation text. The passcode from the link is saved and passed when launching. There is no separate passcode field: if a passcode is required, Zoom will prompt for it itself.
- **Participant Name:** Passes the participant's name to Zoom if provided. Leaving the field empty uses the default profile name.
- **Desktop Shortcuts:** Creates a meeting shortcut directly on your desktop. The default icon is a blue **LM** badge, which can be replaced with an emoji. Emoji icons feature a small LM badge in the corner.
- **Collapsible Form:** If meetings are already saved, the **New Shortcut** form stays collapsed into a compact card. Clicking it expands the form. Clicking **Cancel**, creating, or editing clears the fields and collapses the form again.
- **Meeting Management:** Saved meetings can be opened, edited, pinned to the desktop, or deleted. The pencil icon loads the link, participant name, shortcut title, and icon back into the form.
- **Unified Scrolling:** The entire screen scrolls as a whole; the meeting list does not scroll in an isolated inner container.
- **Client Check:** Checks whether Zoom is installed. If not, it opens the official installation page.
- **Multi-language Support:** Russian, German, and English. Until a language is explicitly selected in settings, the system language is used (falling back to English if unsupported).
- **Themes:** Supports Light, Dark, or System theme.
- **Settings:** Quick access to language, theme, auto-update preferences, current version, copyright, and the privacy policy link.
- **Automatic Updates:** Checks `version.txt` for updates. Auto-update is enabled by default: the new version downloads automatically, followed by an installation prompt. If disabled, the check does not run.
