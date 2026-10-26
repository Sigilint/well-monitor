# well-monitor

Sigilint's HackFW (May 2026) demo: a field of wells on a topographic map, each reporting methane, H₂S and VOC readings with alert states. All data is simulated. It is a no-build React app, so serve the folder over HTTP (for example `python3 -m http.server`) instead of opening `index.html` directly. Devpost: https://devpost.com/software/sigilint-well-monitor

## Deployment

Live at **https://wellmonitor.sigilint.com**, also served at `https://sigilint-well-monitor.netlify.app`. It is the Netlify site `sigilint-well-monitor`, which deploys automatically on every push to `main` of `Sigilint/well-monitor`. Build settings are in `netlify.toml`: no build step, and the repo root is published. **Note:** as of 2026-10-25 the Netlify site still builds from the older `fijiaaron/well-monitor` repo, and relinking it to this repo is still to do. See `DEPLOYMENT.md` in `Sigilint/sigilint-web` for how all the Sigilint sites are hosted.
