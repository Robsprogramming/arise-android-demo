# Arise & Set - live Android demo

This repository hosts the **live, in-browser build of Arise & Set's Android edition** so you can try the app without installing an APK.

**▶ Try it: https://robsprogramming.github.io/arise-android-demo/**

Arise & Set is a science-backed wellness companion: morning wake-up, daytime routines, and evening wind-down, with every habit anchored to a real peer-reviewed study. This is the **Flutter** codebase - the one that ships to Android (with Wear OS, watchOS, and Garmin companions), compiled to the web so it runs in a browser. On a desktop it renders inside a phone frame; on a phone it runs full-screen.

- **Web edition demo (React):** [arise-web-demo](https://robsprogramming.github.io/arise-web-demo/)
- **Engineering write-up:** [ariseandset-showcase](https://github.com/Robsprogramming/ariseandset-showcase)

### What differs from the real Android app

The demo is the same UI and logic, but the browser has no access to Android's platform services. These features are inert here and work on a real device:

- Scheduled routine reminders and notification actions (mark-complete, snooze)
- Home-screen widget, Wear OS / watchOS / Garmin sync
- Health and step-count sync
- Accelerometer tilt parallax

> This repo contains only the compiled static site (a build artifact). The application source is private. Your data stays in your browser's local storage - nothing is uploaded.
