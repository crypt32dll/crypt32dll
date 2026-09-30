# GitHub profile README

Files in this folder belong in a **special repository** named exactly like your username:

`https://github.com/crypt32dll/crypt32dll`

That repo’s root `README.md` is what GitHub renders on your profile.

## Setup

1. Create a **public** repository `crypt32dll/crypt32dll` (must match the username).
2. Copy these files into that repo:
   - `README.md` → repo root
   - `.github/workflows/snake.yml` → same path in the profile repo
3. Push to `main` (or `master`).
4. Open **Actions** → run **Generate contribution snake** once (or wait for the daily schedule).
5. Confirm an `output` branch appears with the two SVG files.

Until the workflow has run, the snake images in the README will 404 — that is expected.

## Customize

- Typing lines: edit the `lines=` query on the [readme-typing-svg](https://github.com/DenverCoder1/readme-typing-svg) URL in `README.md`.
- Skill icons: edit the `i=` query on [skillicons.dev](https://skillicons.dev) in `README.md`.
- Snake palette: see [Platane/snk](https://github.com/Platane/snk).
