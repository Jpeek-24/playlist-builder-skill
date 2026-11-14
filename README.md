# playlist-builder-skill

A Claude skill that builds custom playlists from your **artists, years, genres and occasion**.

- If you have connected **Spotify**, it looks up every track and creates the playlist directly, then gives you the link.
- Otherwise it outputs an `Artist - Title (year)` list you can import on any platform (Apple Music, YouTube Music, etc.) by copy and paste or with an import app.
- It never invents tracks: if it is not sure a track exists, it leaves it out or flags it as uncertain.

## Installation

1. Download this repository (or clone it).
2. In Claude, open the skills settings and upload the repository folder, or paste the contents of `SKILL.md` into a new skill.
3. Optional: connect the Spotify connector so playlists are created automatically.

## Example

> Build me a study playlist: I like Pink Floyd, Radiohead and Nick Drake, mostly from the 70s and 90s, about 25 tracks.

Claude asks only for what is missing, builds the selection, checks it and hands it over.

## Languages

The skill replies in the language you write in.

## License

MIT, see `LICENSE`.
