---
name: playlist-builder
description: Build custom music playlists from the user's taste, artists, years and occasion; creates it on Spotify if connected, otherwise outputs a list that can be imported on any platform.
---

# Playlist builder

Use this skill when the user asks for a playlist, a selection of tracks, or "something to listen to" based on their taste.

## 1. Gather the taste
Collect the following, unless it is already clear from the conversation:
- 3-5 artists or bands they love
- genres and preferred years or decades
- occasion or mood (studying, workout, road trip, night out)
- length (number of tracks or duration)
- platform they use (Spotify, Apple Music, YouTube Music, other)
- what to avoid (tracks they already know, explicit content, certain genres)

Ask only for what is missing, in a single short message. Do not assume tastes the user has not stated.

## 2. Build the selection
- Around 60-70% in line with the artists they named, the rest related discoveries from the same period or genre.
- Respect the requested years; flag any exceptions.
- At most 2-3 tracks per artist unless asked otherwise; no duplicates.
- Order for flow: alternate energy levels and avoid abrupt jumps between neighbouring tracks.

## 3. Verify before delivering
- Never invent tracks, albums or years. If you are not sure a track exists, leave it out or mark it as uncertain.
- If a music connector is available (for example Spotify), search for every track and use only the ones found; replace any that are missing.

## 4. Deliver
- With a connector that can create playlists: create the playlist with a short name and description, and share the link.
- Without a connector: give a numbered list in the format `Artist - Title (year)`, with one line on why each track was chosen, and explain how to import it (copy and paste, or third-party apps that import a list).

## 5. Refine
Ask whether it is too well known, too slow or too similar, and offer a variant.

## Rules
- Reply in the language the user writes in.
- Do not reproduce song lyrics: describe the track, do not quote it.
- If the user does not know an artist, explain in one line why you included them.
