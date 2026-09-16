# Private Spotify Console

A small static web app for listening to Spotify through your own Spotify account.

## What it does

- Uses Spotify's official OAuth flow and Web Playback SDK.
- Stores only your Spotify Client ID and session tokens in your browser storage.
- Plays music through your Spotify Premium account.
- Runs as a static site from `index.html`.

## Setup

1. Create an app in the Spotify Developer Dashboard.
2. Add your deployed site URL as the app redirect URI.
3. Open the site, paste your Spotify Client ID, and sign in.

## Wasmer

Wasmer can serve this repo directly because `index.html` is at the repository root.
