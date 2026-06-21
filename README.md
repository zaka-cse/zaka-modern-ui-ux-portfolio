# MD Zaka Al Shahariar Tanvir — Portfolio

Animated personal portfolio for an AI/ML Researcher. Single-page static site
(`index.html`) with project gallery, an embedded "ZAKA AI" assistant
(voice input/output), live weather widget, and background music.

## Tech
- Plain HTML / CSS / JavaScript — no build step, no dependencies
- Web Speech API (voice in/out), Open-Meteo (weather), HTML5 Audio (BGM)

## Run locally
Serve the folder with any static server, e.g.:

```bash
python -m http.server 8000
# then open http://localhost:8000
```

> Use a local server (not `file://`) so the assets, fonts, and microphone/voice
> features work correctly.

## Structure
```
index.html          # the entire site
assets/
  projects/         # project & publication images
  audio/bgm.mp3     # background music
netlify.toml        # deploy config (publish from root)
```

## Deploy
Hosted on Netlify — pushes to the default branch deploy automatically.
