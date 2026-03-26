# Mad Mood Music — EchoStory bundle

## Drop-in asset paths

Put the final MP3s here:
- `./audio/01-mad-mood-music.mp3`
- `./audio/02-seventy-six.mp3`
- `./audio/03-old-55-porsche.mp3`
- `./audio/04-good-kids.mp3`
- `./audio/05-not-that-kind-of-country.mp3`
- `./audio/06-weird-drops.mp3`
- `./audio/07-playlist-too-long.mp3`
- `./audio/08-retire-in-spain.mp3`

Current art is placeholder SVG art in `./images`. Replace those files in-place if you want to keep the existing wiring.

## GitHub Pages deploy

Upload the whole folder contents to a GitHub Pages repo root.

If you host in a subfolder, keep the relative paths as-is.

## Playback notes

- Auto-plays the next track.
- Saves track index + time in local storage.
- Uses Media Session for lock-screen controls where supported.
- Background/locked-screen playback depends on browser + OS policy.
