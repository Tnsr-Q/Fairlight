# Fairlight CMI Waveform Monitor - GitHub Pages

This repository deploys the Fairlight CMI Waveform Monitor to GitHub Pages automatically.

## Live Demo

Visit the deployed site at: `https://tnsr-q.github.io/Fairlight/`

## What's Deployed

- **Landing Page**: Overview and navigation to demos
- **Standalone Demo**: Self-contained HTML5 Canvas waveform visualizer
- **Enhanced Demo**: Version with Plotly integration (requires CDN)

## Features

- Authentic 1980s Fairlight CMI styling
- Interactive waveform visualization
- Retro terminal aesthetic with neon green on black
- HTML5 Canvas rendering
- Responsive design

## Automatic Deployment

The site is automatically deployed via GitHub Actions when changes are pushed to the main branch. The workflow:

1. Copies all files from the `fairlight-cmi-wave/` directory
2. Ensures proper `index.html` is available
3. Deploys to GitHub Pages using the standard Pages deployment action

## Local Development

To work on the project locally:

1. Clone the repository
2. Navigate to the `fairlight-cmi-wave/` directory
3. Open any of the HTML files directly in a browser
4. Or use a local server: `python -m http.server 8000`

## Built With

- HTML5 Canvas
- CSS3 with custom retro styling
- Vanilla JavaScript
- Quarto dashboard framework
- GitHub Actions for deployment