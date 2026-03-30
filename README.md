# KannadaEasy

A Duolingo-style Progressive Web App for Hindi speakers to learn Kannada. No backend needed — runs entirely in the browser.

## Features

- **20 lessons** (17 main + 3 bonus Kannada script lessons)
- **5 exercise types**: Flashcards, MCQ, Reverse MCQ, Matching, Listen & Pick
- **Text-to-Speech** for Kannada pronunciation
- **Gamification**: XP, hearts, streaks, levels, daily goals
- **Spaced repetition** (Leitner system) for word review
- **Multi-profile support** with separate progress tracking
- **Offline support** via service worker
- **Light/Dark theme**
- **Installable PWA** — add to home screen on any device

## Try it

**[https://tushar0612.github.io/kannada-easy/](https://tushar0612.github.io/kannada-easy/)**

Works on any browser — desktop or mobile. On mobile, tap Share → "Add to Home Screen" to install as an app.

## How it works

All Kannada words are displayed in **Devanagari (Hindi) script** so Hindi speakers can read them immediately. Kannada script is taught only in optional bonus lessons.

Lessons progress from greetings and numbers to verbs, sentences, and daily phrases. Each lesson has 5 rounds of exercises with increasing difficulty.

## Tech

- Single HTML file, vanilla CSS/JS — no frameworks
- LocalStorage for state persistence
- Browser Speech Synthesis API for TTS
- PWA with manifest + service worker for offline use

## Run locally

```bash
cd kannada-easy
python3 -m http.server 8080
# Open http://localhost:8080
```
