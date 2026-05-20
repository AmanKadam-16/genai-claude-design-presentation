# Generative AI Presentation

A web-based HTML presentation about Generative AI built with the `<deck-stage>` web component.

## Files

- `Generative AI.html` - Main presentation file
- `deck-stage.js` - Web component for slide management and navigation
- `tweaks-panel.jsx` - Interactive tweaks panel component

## Local Development

Simply open `Generative AI.html` in a web browser to view the presentation.

### Navigation

- **Arrow keys** or **Space** - Navigate between slides
- **← / →** - Previous / Next slide
- **PgUp / PgDn** - Page navigation
- **Home / End** - Jump to first / last slide
- **Number keys** - Jump to specific slide
- **R** - Reset to first slide

## Deployment to Vercel

This project is configured to deploy on Vercel as a static site.

1. Push this repository to GitHub
2. Connect your GitHub repository to Vercel
3. Vercel will automatically detect and deploy the static files

The presentation will be available at your Vercel URL.

## Customization

Edit `Generative AI.html` to:
- Modify slide content
- Change colors and typography variables in the `<style>` section
- Add or remove slides
- Adjust layout and formatting

The `--paper`, `--ink`, `--accent`, and other CSS variables control the color scheme and typography throughout the presentation.
