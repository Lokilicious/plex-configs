# Configs for my Plex Infrastructure

1. Kometa ✔️ (check https://kometa.wiki/en/latest/ for their official docs)
2. ImageMaid ✔️ (check https://github.com/Kometa-Team/ImageMaid for their official docs)
3. DAPS ✔️ (check https://github.com/Drazzilb08/daps/wiki for their official docs)

## How it looks:

![Screenshot_2024-05-15_at_08 01 51](https://github.com/user-attachments/assets/2e7eef6f-4f7f-41f5-ac7b-5e2c7b407cd5)

## What it does:

### Kometa
- Set overlays for Language Flags, Resolution, HDR & a Low Quality banner for TELESYNCS.
- Create Collections for Universe, Animation, Disney and some Actors.
- Create Collections for Media which was previously only English but now also has a German release.
- Create Collections for Media which was previously only a TELESYNC but has now a Web or Bluray release.
- Creates Collections for Media which is trending on Trakt and sends missing media to Radarr / Sonarr.
- Fixes Plex Categories by syncing them from TMDB.
- Updates Ratings by syncing them from Rotten Tomatoes and Trakt.

### ImageMaid
- Remove bloat which piles up in Plexes directory (thumbnails, old assets, ...).

### DAPS
- Pulls standardized posters in MM2K style from community google drives and applies them to plex.
- Removing the standard white border from MM2K style posters.
- Syncs labels between Radarr/Sonarr and Plex.
- Log media which are missing custom posters.
