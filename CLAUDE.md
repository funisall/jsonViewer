# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Single-file JSON formatter tool (`index.html`) with no dependencies. Open directly in a browser.

## Running

```bash
# Open in browser
xdg-open index.html  # Linux
open index.html      # macOS
start index.html     # Windows
```

## Architecture

Single HTML file containing embedded CSS and JavaScript:
- **Layout**: Flexbox-based responsive layout, editors auto-fill viewport height
- **Theme**: Light theme using Tailwind CSS color palette (Slate/Blue)
- **Core functions**: `formatJSON()`, `minifyJSON()`, `copyToClipboard()`, `filterNullValues()`
- **Auto-format**: Triggers on paste event in input textarea