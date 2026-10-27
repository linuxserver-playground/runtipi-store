# LinuxServer.io Runtipi app store

**This repository is generated.** Every file is written by the [hub](https://github.com/linuxserver-playground/hub) from each image's `image.yml`
and newest build, and pushed by its hourly refresh workflow; edits here are overwritten by the next run. Changes belong in
the image's repository (its `image.yml`) or in the hub's `lsio_hub/generate/runtipi.py`.

## Import

In Runtipi open *Settings*, choose *App Stores*, *Add App Store*, and paste `https://github.com/linuxserver-playground/runtipi-store`.

## Layout

`apps/<app>/` per image with `config.json`, `docker-compose.yml` (dynamic compose, `x-runtipi` schema 2) and `metadata/description.md`.

The same output is served at `https://linuxserver-playground.github.io/hub/stores/runtipi/`; the store index
with every platform is `https://linuxserver-playground.github.io/hub/api/v1/stores/index.json`.
