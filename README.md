# Clean Grid CSS

A clean, dependency-free CSS grid system compatible with Bootstrap 5 grid syntax.

This project provides containers, rows, columns and gutters only.
No components. No utilities. No JavaScript.

## Features

- Bootstrap 5 compatible class names
- Flexbox-based layout
- Responsive breakpoints (sm to xxl)
- Gutter support (g-0 to g-5)
- No reset, no opinionated styles
- Framework-agnostic

## File Structure

clean-grid-css/
├─ dist/
│  └─ grid.min.css      (Production-ready, minified)
├─ src/
│  └─ grid.css          (Readable source CSS)
├─ scss/
│  └─ _grid.scss        (Optional SCSS source)
├─ README.md
└─ LICENSE

## Usage

<link rel="stylesheet" href="grid.min.css">

<div class="container">
  <div class="row g-3">
    <div class="col-md-6">Left</div>
    <div class="col-md-6">Right</div>
  </div>
</div>

## Philosophy

This grid is intentionally limited to layout only.

No utilities.
No JavaScript.
No magic.

## License

MIT

Author: Michael Korte
Company: Michael Korte Software
Version: 0.1
