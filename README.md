# Screen Update Interface

A browser-based maintenance-status interface built as a multi-screen front-end experience using standalone HTML, Tailwind CSS, canvas-driven visuals, and lightweight browser-generated alert cues.

## Project Structure

```text
.
├── .vscode/
├── img/
│   ├── main-screen.png
│   ├── success-screen.png
│   └── system-lock.png
├── maintenance.html
├── success.html
├── warning.html.zip
└── README.md
```

## Preview

### Access Lock Screen
![Access Lock Screen](img/system-lock.png)

### Maintenance Monitor
![Maintenance Monitor](img/main-screen.png)

### Completion Screen
![Completion Screen](img/success-screen.png)

## Overview

This project contains two main browser interfaces:

- `maintenance.html` — the primary maintenance monitor screen
- `success.html` — the completion screen shown after the process finishes

The maintenance interface includes a launch lock screen, a real-time system-style dashboard, canvas-rendered telemetry, animated waveform display, dynamic health metrics, and browser-generated alert cues.

The completion interface includes a success-state card, status summary blocks, and a completion action button.

## Main Features

### Maintenance Screen
- restricted-entry launch overlay
- real-time local system clock
- animated system-monitor layout
- memory usage graph rendered with canvas
- ECG-style health waveform
- dynamic health percentage display
- timed browser-generated alert tones
- responsive panel-based layout

### Completion Screen
- centered success-state confirmation card
- animated visual effects
- update verification summary
- completion button with browser close attempt fallback

## Front-End Stack

- HTML5
- Tailwind CSS via CDN
- custom CSS animations
- JavaScript
- Canvas API
- Web Audio API

## How to Run

Open these files directly in a browser:

- `maintenance.html`
- `success.html`

For best results, use a modern Chromium-based browser.

## Notes

- Browser audio usually starts after user interaction.
- Automatic tab closing may not work in all browsers.
- External CDN resources are required for full styling.
