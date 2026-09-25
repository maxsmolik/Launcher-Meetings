# Launcher-Meetings

A Windows application that opens a Zoom meeting via link or ID and creates a desktop shortcut for it.
This is an independent application. It is not affiliated with, sponsored by, or endorsed by Zoom Video Communications, Inc.

# Features
Accepts a Zoom link, Meeting ID, or invitation text. The passcode from the link is saved and passed when launching. There is no separate passcode field: if a passcode is required, Zoom will prompt for it itself.
Passes the participant's name to Zoom if provided. Leaving the field empty uses the default name.
Creates a meeting shortcut on the desktop. The default icon is a blue LM badge, which can be replaced with an emoji. Emoji icons feature a small LM badge in the corner.
If meetings are already saved, the "New Shortcut" form is collapsed into a similar card. Clicking it expands the form. "Cancel", creating, or editing clears the fields and collapses the form again.
Saved meetings can be opened, edited, pinned to the desktop, or deleted. The pencil icon loads the link, participant name, shortcut title, and icon back into the form.
The entire screen scrolls as a whole; the meeting list does not have a separate scroll area.
Checks whether Zoom is installed. If not, it opens the installation page.
Interface languages: Russian, German, and English. Until the user selects a language in settings, the system language is used, falling back to English if unsupported.
Theme: light, dark, or system default.
Settings include: language, theme, auto-update, version, copyright, and a link to the privacy policy.
Update check reads version.txt. Auto-update is enabled by default: the new version is downloaded, and installation is prompted. If auto-update is disabled, the check does not run.
