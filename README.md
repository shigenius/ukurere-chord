# Ukulele Chord

A browser-only ukulele chord helper.

## Usage

Open `index.html` in a browser. `index.html` is the GitHub Pages entry point and mirrors `ukulele.html`.

- Paste ChordWiki source text into the textarea.
- Load the song to transpose chords and show ukulele fingering diagrams.
- No build step or server is required.

The generated sample page is available at `sample-chord-chart.html`.

## Publish with GitHub Pages

In the GitHub repository:

1. Open `Settings`.
2. Open `Pages`.
3. Under `Build and deployment`, set `Source` to `Deploy from a branch`.
4. Set `Branch` to `main` and the folder to `/root`.
5. Click `Save`.

After GitHub Pages finishes deploying, the site should be available at:

```text
https://shigenius.github.io/ukurere-chord/
```

The sample page should be available at:

```text
https://shigenius.github.io/ukurere-chord/sample-chord-chart.html
```

## Files

```text
.
|-- index.html
|-- README.md
|-- sample-chord-chart.html
|-- ukulele.html
`-- .gitignore
```

## Ignored Files

`chordwiki_sources/` is treated as local source or working data and is not committed.
