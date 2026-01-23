# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static GitHub Pages site for the Burlingame family, hosted at **www.theburl.com**. The site uses a Swiss-inspired design with no build process or framework.

## Deployment

- Hosted on GitHub Pages (gburlingame.github.io)
- Custom domain configured via `CNAME` file (www.theburl.com)
- Deployments happen automatically when pushing to the default branch

## Architecture

- `index.html` - Main single-page site with all content and inline CSS
- `home.html` - Redirect page to theburl.com
- Image files (PNG/JPG) stored in root directory

## Design System

CSS variables defined in `:root` of `index.html`:
- `--color-accent: #FF0000` (Swiss Red)
- `--color-text: #111111`
- `--color-bg: #ffffff`
- `--font-main: 'Inter'`

Key visual features:
- Images display grayscale by default, colorize on hover (use `class="colorized"` to override)
- Responsive grid layout with breakpoints at 1024px, 768px, and 640px
- 20px red accent bar at top of page
