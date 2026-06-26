# reps-tracker
Personal and customisable fitness tracker

# ⚽ Reps Tracker

A mobile-first Progressive Web App for tracking daily exercise reps. Built as a personal project after completing the Lifeline Push Up Challenge.

**Live app → [nabiddle.github.io/reps-tracker](https://nabiddle.github.io/reps-tracker)**

---

## Features

- **Lap wheel input** — drag your finger around the circular wheel to log reps. Each full rotation = 10 reps. Five laps = target reached.
- **Layered lap colours** — each completed lap leaves a permanent arc on the wheel in a progressively different shade, so you can see your history at a glance.
- **Two activity wheels** — track any two exercises simultaneously from a list of six: Push Ups, Sit Ups, Squats, Chin Ups, Planks, Lunges.
- **Day complete state** — the entire app shifts to a deep green theme when you hit both daily targets.
- **Weekly progress bar chart** — see your whole week at a glance with daily bars that turn gold or green on completion.
- **Weekly stats panel** — weekly totals per activity, days target hit, current streak, days remaining in the week, and weekly target percentage.
- **Configurable targets** — set independent rep targets for each activity via the settings panel. Targets adjust in steps of 10 to match the lap wheel mechanic.
- **Rest day support** — mark a day as rest and it shows clearly in the weekly chart without counting against your streak.
- **Offline support** — works fully offline via service worker caching.
- **Installable** — add to your iPhone home screen via Safari → Share → Add to Home Screen for a full standalone app experience.

---

## Install on iPhone

1. Open the live app link in **Safari**
2. Tap the **Share** button (box with arrow)
3. Tap **Add to Home Screen**
4. Tap **Add**

The app will appear on your home screen and run in full screen with no browser chrome.

---

## Tech

Plain HTML, CSS, and vanilla JavaScript. No frameworks, no dependencies, no build step. Data persists via `localStorage`. Offline support via the Cache API and a service worker.

---

## Background

Built after completing the [Lifeline Push Up Challenge](https://www.pushupchallenge.com.au/) — 3,000+ push ups over 24 days. The goal was to replicate the satisfying lap-wheel logging mechanic from the challenge app and keep the daily habit going post-challenge.

---

## Licence

MIT
