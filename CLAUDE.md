# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Pure HTML5/CSS3 static website with no frameworks or build dependencies. Hosted on GitHub Pages at queirogaville.com.

## Architecture

**Main pages:**
- `index.html` - Landing page with logo and navigation links
- `kitty.html` - Interactive canvas-based cat animation with physics simulation
- `styles.css` - Styling for main page (using CSS custom properties)

**Interactive features in kitty.html:**
- Full custom canvas rendering for cat character ("Mochi") and yarn ball
- State machine-driven AI behavior (wander, chase, sleep, petted states)
- Physics simulation for yarn ball with gravity, friction, and bouncing
- Touch and mouse event handling for petting and yarn dragging

## Design System

Use the defined color palette from `:root` variables in styles.css:
- Primary: `#2C3E50` (Deep blue-gray)
- Secondary: `#3498DB` (Bright blue)
- Accent: `#1ABC9C` (Teal)
- Text Dark: `#2C3E50`
- Text Light: `#7F8C8D`
- Background: `#FFFFFF`
- Background Alt: `#ECF0F1`

## Development Workflow

**Local development:** Open `index.html` directly in browser - no build step required.

**Deployment:** Push to GitHub main branch. GitHub Pages automatically serves the site.

## Important Constraints

- Do not introduce any JavaScript frameworks, build tools, or dependencies
- Maintain vanilla HTML/CSS/JS approach
- Keep the minimalist, clean design aesthetic
