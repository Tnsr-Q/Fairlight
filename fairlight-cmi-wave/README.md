# Fairlight CMI Waveform Monitor

A retro-styled waveform visualizer inspired by the classic Fairlight CMI digital sampler, built using Quarto dashboard tools.

## Features

- **Authentic 1980s CMI Styling**: Black background with neon green (#39ff14) elements
- **Retro Typography**: Monospace font (Share Tech Mono / Courier New fallback)
- **Interactive Visualization**: Real-time waveform rendering with HTML5 Canvas
- **Grid Display**: Classic oscilloscope-style grid pattern
- **Channel Selection**: Interactive dropdown for channel selection (locked to amplitude)

## Files

- `index.qmd` - Main Quarto dashboard file
- `custom.scss` - Fairlight CMI retro styling
- `data/wave.csv` - Sample waveform data
- `images/cmi-logo-green.svg` - Custom CMI logo
- `standalone-demo.html` - Working HTML demo (no dependencies)
- `demo.html` - Enhanced version with Plotly (requires external CDN)

## Quick Demo

Open `standalone-demo.html` in any modern web browser to see the working Fairlight CMI waveform visualizer.

## Technical Details

- Uses HTML5 Canvas for waveform rendering
- Pure CSS/JavaScript implementation (no external dependencies in standalone version)
- Responsive design that works on all screen sizes
- Authentic retro color scheme (#39ff14 on #000000)
- Grid-based oscilloscope display style

## Sample Data

The included sample data shows a typical audio waveform with:
- Time range: 0-9 units
- Amplitude range: -0.6 to +0.9
- 10 data points demonstrating various waveform characteristics

## Quarto Dashboard

The project is structured as a Quarto dashboard with:
- Custom SCSS theming
- R code chunks for data processing
- OJS chunks for interactivity
- Dashboard layout configuration

## Getting Started

1. **Quick Demo**: Open `standalone-demo.html` directly in your browser
2. **Quarto Version**: Use `quarto render` to build the dashboard (requires R and Quarto)
3. **Dependencies**: Install ggplot2, plotly, and readr if using the R version

Built with the copilot-quarto tool suite for automated dashboard creation.
