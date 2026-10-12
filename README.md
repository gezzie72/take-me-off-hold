# Take Me Off Hold

A small web app for the monthly **"Add projects"** reminder and for keeping track of items that are
on hold until you take them off hold. It works on desktop and on phones, and can be installed to a
phone's home screen.

**Open the app:** https://gezzie72.github.io/take-me-off-hold/

## Features

- Monthly "Add projects" reminder on the 1st, with a done/undo toggle
- Notes per day, each marked **On hold** or **Off hold**
- Search across all notes (Ctrl/Cmd + K on desktop)
- **Setup** button: light/dark/auto theme, text size, weekends on/off, backup/restore, CSV export
- Sync between devices through a private GitHub Gist, with optional AES-256 encryption
- Works offline once installed

## Your data stays private

This repository holds only the app. Your notes are never stored here: they live in your browser,
and, if you turn on sync, in your own private Gist. With encryption on, the Gist only contains
scrambled data that needs your passphrase.

## Setting up sync

1. Create a GitHub token with the **gist** permission
   (GitHub → Settings → Developer settings → Personal access tokens).
2. In the app open **Setup**, paste the token, and press **Create new** to make a private Gist.
3. Optionally turn on **Encrypt synced data** and choose a passphrase.
4. On your other devices, paste the same token, Gist ID and passphrase.

## Install on a phone

- **iPhone (Safari):** Share → Add to Home Screen
- **Android (Chrome):** ⋮ menu → Add to Home screen / Install app

Version: v0.02
