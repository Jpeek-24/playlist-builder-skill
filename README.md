# crea-playlist

Una skill per Claude che crea playlist musicali su misura a partire da **artisti, anni, generi e occasione**.

- Se hai collegato **Spotify**, cerca ogni brano e crea la playlist direttamente, dandoti il link.
- Altrimenti produce un elenco `Artista - Titolo (anno)` che puoi importare su qualsiasi piattaforma (Apple Music, YouTube Music, ecc.) con copia e incolla o con un'app di importazione.
- Non inventa brani: se non è sicura che esistano, li scarta o li segnala come incerti.

## Installazione

1. Scarica questa cartella (o clona il repository).
2. In Claude vai nelle impostazioni delle skill e carica la cartella `crea-playlist` (oppure incolla il contenuto di `SKILL.md` in una nuova skill).
3. Facoltativo: collega il connettore Spotify per creare le playlist in automatico.

## Esempio d'uso

> Fammi una playlist per studiare: mi piacciono Fabrizio De André, Lucio Dalla e Battiato, soprattutto anni '70 e '80, circa 25 brani.

Claude chiede solo ciò che manca, costruisce la selezione, la verifica e te la consegna.

## Licenza

MIT, vedi `LICENSE`.

---

## English

A Claude skill that builds custom playlists from your **artists, years, genres and occasion**. It creates the playlist on Spotify if the connector is available; otherwise it outputs an `Artist - Title (year)` list you can import anywhere. It never invents tracks. The skill instructions are written in Italian and answer in Italian by default.

**Install:** download this folder and upload `crea-playlist` as a skill in Claude, or paste the contents of `SKILL.md` into a new skill.
