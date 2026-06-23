# Dynamic Average Calculator

A modern, responsive, single-file web app that calculates the average of numbers entered by the user — in real time, with no backend, frameworks, or external libraries.

**Live demo:** [dynamic-average-calculator.vercel.app](https://dynamic-average-calculator.vercel.app)

## Features

- **Live calculation** — the average updates automatically as you type (no Calculate button).
- **Auto-expanding inputs** — starts with 5 fields; a new field appears whenever the last one is filled, so there's always an empty box ready.
- **Smart validation** — allows decimals and negative numbers; ignores empty fields and flags invalid entries with an inline red message.
- **Copy Average Value** — one click copies the computed average to your clipboard, with on-button confirmation.
- **Reset button** — clears all fields and restores the default state.
- **Instructions modal** — a quick how-to popup (close button, click-outside, and Escape to dismiss).
- **Responsive design** — two-column layout on desktop, stacks vertically on mobile.

## Usage

Just open `index.html` in any browser — it works fully offline. No build step, no install.

## Tech Stack

- HTML5
- CSS3 (Grid + Flexbox)
- Vanilla JavaScript

Everything lives in a single file: `index.html`.
