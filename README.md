# Workout Dashboard

A mobile-first workout dashboard for upper body, lower body, and mobility training.

## Features

- Circuit-based workout flow
- Warm-up-first workout start
- 5-second start countdown
- Elapsed, circuit, and rest timers
- Smooth timed-exercise progress bars
- Automatic rest handling
- Audio and vibration alerts
- Pause/resume support
- Wake Lock support where available
- Resume interrupted workouts using local browser storage
- Exercise info panels with reference images and form cues
- Multi-workout architecture for adding additional routines

## Local use

Open `index.html` in a browser.

## GitHub Pages deployment

This repository includes a GitHub Actions workflow that publishes the site whenever changes are pushed to `main`.

One-time GitHub setup after publishing the repository:

1. Open the repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **GitHub Actions**.
4. The included workflow will deploy the site automatically.

Future updates only require committing and pushing changes to `main` in GitHub Desktop.
