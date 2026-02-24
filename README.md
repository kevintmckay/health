# Daily Health Tracker

A single-page habit tracker for health and fitness programs with built-in CBT (Cognitive Behavioral Therapy) tools for managing anxiety-driven eating.

**[Live Demo](https://kevintmckay.github.io/health/)**

## Features

- **Phase-aware checklist** — items appear based on your current program week, so you're never overwhelmed
- **Expandable details** — tap any item for quick-reference tips on what to do and how to progress
- **CBT tools** — interactive forms for food/mood logging, thought catching, challenging & reframing, and urge surfing
- **Progress tracking** — daily completion bar with streak counter
- **History calendar** — month view with color-coded days to spot patterns
- **Reference docs** — built-in viewer for all your plan documents
- **100% private** — all data stays in your browser's localStorage, nothing is sent anywhere

## Getting Started

1. Open `index.html` in any browser (or visit the [live demo](https://kevintmckay.github.io/health/))
2. Click the gear icon to set your program start date
3. Check off items as you complete them each day

## Customizing Your Plans

The `.txt` files in the root are generic templates. To use your own:

1. Create a `personal/` folder
2. Copy any `.txt` file into `personal/` and edit it with your details
3. The app loads from `personal/` first, falling back to the templates

The `personal/` folder is gitignored so your data stays private.

## Program Structure

| Week | New Items Added |
|------|----------------|
| 1 | Morning daylight, meditation, walking, diet, water, sleep schedule, food/mood log |
| 2 | Kitchen closes rule |
| 3 | Core + hip exercises (Routine A), CBT thought catching |
| 4 | Resistance training (Routine B) |
| 5 | Pool/aquatic exercise, CBT challenge & reframe |
| 7 | CBT urge surfing |

## No Server Required

Everything runs in a single HTML file — no build tools, no dependencies, no accounts. Just open it.
