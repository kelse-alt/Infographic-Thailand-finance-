# Phuket, Thailand — 30-Day Financial Guide

A single-page HTML, CSS, and JavaScript infographic exploring a 30-day Phuket
budget for two travelers, including Muay Thai training.

## What it demonstrates

- Travel-style budget comparisons and spending categories.
- Three Chart.js charts for budget allocation, daily costs, and food/drink prices.
- Responsive presentation with Tailwind CSS and the Inter font.

The figures are historical planning estimates for **October 2025**, using the
page's stated exchange rate of **£1 = 43 THB**. They are not current price quotes.

## View locally

The complete page source is stored in [text.txt](text.txt). No package install or
build is required:

1. Download `text.txt` or clone this repository.
2. Save a separate copy with an `.html` extension, such as `phuket-guide.html`.
3. Open that copy in a web browser. Keep the original tracked source unchanged.

Internet access is needed for Tailwind (`cdn.tailwindcss.com`), Chart.js
(`cdn.jsdelivr.net`), and Google Fonts (`fonts.googleapis.com` and
`fonts.gstatic.com`).

## Current limitations

The itinerary button is an unfinished integration: its API key is empty and its
request targets a dated Gemini preview model. AI itinerary generation is
unavailable out of the box.

GitHub displays the source file and its commit history. An interactive hosted
webpage requires a separate deployment; this README does not announce a live site.
