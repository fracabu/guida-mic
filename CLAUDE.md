# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a single-file static HTML website ("Guida allo Studio - MIC 1800 Assistenti") - an Italian-language study guide for a Ministry of Culture (MIC) job competition for 1,800 assistant positions.

## Architecture

**Single File Structure**: The entire site is contained in `index.html` with:
- Embedded CSS (no external stylesheets)
- Minimal vanilla JavaScript (sidebar scroll highlighting only)
- No build process, bundlers, or dependencies
- No package.json or node_modules

**Layout Pattern**: Dashboard layout with fixed sidebar navigation and scrollable main content area. Uses CSS Grid for card layouts and Flexbox for the main dashboard structure.

## Development

To preview locally, open `index.html` directly in a browser. No server required.

## Key Technical Details

- **Language**: Italian (lang="it")
- **Responsive**: Mobile-friendly with media queries at 900px breakpoint
- **Print styles**: Included for printing
- **Analytics**: GoatCounter tracking enabled
- **Color scheme**: Orange/amber gradient theme (#c2410c primary)

## Content Sections

The page covers exam structure, job profiles (Vigilanza and Tecnici), study materials, exam strategy, and external quiz resources. Content is organized into navigable sections via anchor links.
