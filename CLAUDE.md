# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static HTML project containing a Japanese-themed payment form (`payment.html`). The project features:

- A single-page payment form with Japanese aesthetic design
- CSS animations including falling sakura (cherry blossoms) and swimming koi fish
- Japanese-inspired color palette with gradient backgrounds and traditional colors
- Form elements for name, phone, payment method selection, and amount input
- Responsive design with glassmorphism effects

## Development

### Running the Project

Since this is a static HTML project, simply open `payment.html` in a web browser:

```bash
# Open in default browser (macOS)
open payment.html

# Or serve locally with Python
python3 -m http.server 8000
# Then visit http://localhost:8000/payment.html
```

### Architecture

The project consists of:

- **payment.html**: Single-file application containing HTML structure, embedded CSS styles, and JavaScript functionality
- **Styling**: All CSS is embedded within `<style>` tags, featuring:
  - Japanese color scheme with pink/purple gradients
  - Animated sakura petals falling across the screen
  - Koi fish decorations with subtle swimming animations
  - Glassmorphism effects with backdrop-filter blur
  - Japanese fonts (Hiragino Sans, Yu Gothic, Meiryo)
- **Functionality**: Form validation and payment method selection handled via embedded JavaScript

### Design Elements

The Japanese theme is implemented through:
- Sakura emoji (🌸, 🌺) with CSS `@keyframes fall` animation
- Koi fish emoji (🐟, 🐠) with `@keyframes swim` animation
- Traditional Japanese color palette (#8B4B8C, #AD5A7A, #F4C2C2)
- Soft, rounded UI elements with extensive use of border-radius
- Gradient backgrounds mimicking cherry blossom season