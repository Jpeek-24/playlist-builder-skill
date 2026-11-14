---
name: playlist-builder
description: Build custom music playlists from the user's taste, artists, years and occasion; researches which tracks work best in that context and era, creates it on Spotify if connected, otherwise outputs a list that can be imported on any platform.
---

# Playlist builder

Use this skill when the user asks for a playlist, a selection of tracks, or "something to listen to" based on their taste.

## 1. Gather the taste
Collect the following, unless it is already clear from the conversation:
- 3-5 artists or bands they love
- genres and preferred years or decades
- occasion or mood (studying, workout, road trip, club, party, night out)
- length (number of tracks or duration)
- platform they use (Spotify, Apple Music, YouTube Music, other)
- what to avoid (tracks they already know, explicit content, certain genres)

Ask only for what is missing, in a single short message. Do not assume tastes the user has not stated.

## 2. Research what works, before picking any track
Do not choose tracks by guess. For every artist, check which of their tracks perform best in the context and years the user gave.

- **Context:** for the occasion the user named (club, workout, road trip, party, wedding, study...), find which of that artist's tracks are most played, requested or charted in that setting. For example, if the user says an artist plus "club", look at what actually works in clubs: DJ and club charts, popular playlists for that occasion, streaming numbers, what DJs play. Do the same for every other context and every artist.
- **Years:** for the years or decades the user asked for, prefer the tracks that were biggest in that period (chart positions, hits of the era, most-streamed tracks from those years) among the artists they named.
- **Sources:** use web search or the music connector when available. Prefer charts, play counts and real playlists over opinion pieces, and combine more than one signal.
- **Shortlist:** build a candidate list of about twice the length of the final playlist, ranked by how well each track fits the context and era.
- **Be honest about evidence:** never state popularity numbers or rankings you did not find. If no search tool is available, rely on well-known knowledge and say it is based on general knowledge, not live data.
- A track that is popular overall can still be wrong for the setting. Fit to the context beats the artist's biggest hit.

## 3. Build the selection
- Choose from the shortlist. Around 60-70% in line with the artists they named, the rest related discoveries that also work in that context and era.
- Respect the requested years; flag any exceptions.
- At most 2-3 tracks per artist unless asked otherwise; no duplicates.
- Order for flow: alternate energy levels and avoid abrupt jumps between neighbouring tracks.

## 4. Verify before delivering
- Never invent tracks, albums or years. If you are not sure a track exists, leave it out or mark it as uncertain.
- If a music connector is available (for example Spotify), search for every track and use only the ones found; replace any that are missing.

## 5. Deliver
- With a connector that can create playlists: create the playlist with a short name and description, and share the link.
- Without a connector: give a numbered list in the format `Artist - Title (year)`, with one line on why each track fits the context and era, and explain how to import it (copy and paste, or third-party apps that import a list).

## 6. Refine
Ask whether it is too well known, too slow or too similar, and offer a variant.

## Rules
- Reply in the language the user writes in.
- Do not reproduce song lyrics: describe the track, do not quote it.
- If the user does not know an artist, explain in one line why you included them.
