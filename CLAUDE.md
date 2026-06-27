# Project notes

## Shortcuts
- When the user says **"github"**, package and present ALL of this app's project files for download (a zip of the whole project via `present_fs_item_for_download`), so they can upload them to GitHub. No need to ask for confirmation.

## App
- Main file: `Demo Access.dc.html` — email-gated entry page for the "HCP OS: The AI Marketing Platform" demo (Havener brand).
- Access gate is client-side: SHA-256 hashes of allowed emails (erik@havenercapital.com, stacy@havenercapital.com) are baked in; users enter their email to unlock.
