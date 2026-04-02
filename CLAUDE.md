# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Orada Intelligence is a static single-page website hosted on GitHub Pages. No build process, package manager, or dependencies.

## Development Workflow

- Edit files directly in `/docs/` directory
- Push to `main` branch to deploy (GitHub Pages auto-deploys from /docs)
- Test locally by opening `/docs/index.html` in a browser

## Architecture

Single HTML file (`/docs/index.html`) containing:
- Embedded CSS styles in `<style>` tag
- SVG graphics inline
- No JavaScript currently

**Design System:**
- CSS custom properties define the color palette: `--deep`, `--ink`, `--slate`, `--gold`, `--gold-lt`, `--foam`, `--mist`, `--white`
- Typography: Cormorant Garamond (serif headings) and Tenor Sans (body)
- Animations: `fadeUp` and `fadeIn` keyframes with staggered delays
- Mobile breakpoint at 640px

## Key Files

- `/docs/index.html` - The entire website
- `/docs/CNAME` - Custom domain configuration (www.oradaintelligence.com)
