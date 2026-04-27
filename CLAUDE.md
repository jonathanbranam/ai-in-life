# AI in My Life — Presentation

A five-minute talk for sharing with my company (engineers and data scientists) about how I use AI tools in my personal life.

## What this project is

A personal presentation covering:
- My experience with vibe coding — what worked, where it broke down
- The shift to spec-driven development and why it helped
- Projects I built: productivity tools, a time tracker, and a casual video game about an otter built with my daughter
- The parking lot origin story: I started the otter game using Claude Mobile while waiting to pick up my son from a basketball game — Claude would output an HTML file that I could open and test right there

## Build approach

**Build in HTML first.** Iterate quickly on content and layout in `slides.html` before converting to a slide deck (PowerPoint, Keynote, etc.) or using HTML screenshots directly in the presentation.

`slides.html` is a self-contained slide deck with keyboard navigation (arrow keys) and Prev/Next buttons.

## OtterGame technical notes

The otter game was built with JavaScript and [Phaser.js](https://phaser.io/), a browser-based video game framework. This created an interesting challenge: the AI agent had no way to run or observe the game directly. Because Phaser renders to a canvas, the agent couldn't test or understand the game state — it needed a screenshot to see what was actually happening. So the workflow became: generate code → open in browser → take a screenshot → share it with the AI → iterate.

This is worth mentioning in the presentation as an honest look at AI limitations and how to work around them.

## Git workflow

After every file change, create a git commit. This keeps a full history so any change can be reverted. Steps:
1. `git add <changed files>`
2. `git commit -m "<short description of what changed>"`

This is a local-only repository — no remote push needed unless requested.

## Files

- `slides.html` — the presentation, 8 slides
- `CLAUDE.md` — this file
