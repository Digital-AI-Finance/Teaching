# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

Static GitHub Pages landing page for Digital-AI-Finance teaching materials. Links to three BSc courses hosted on separate GitHub Pages sites.

## Architecture

Single-page static site with no build system:
- `index.html` - Landing page with embedded CSS (no external dependencies)
- GitHub Pages deployment from `master` branch

## Linked Courses

| Course | GitHub Pages URL |
|--------|------------------|
| Digital Finance | digital-ai-finance.github.io/digital-finance |
| Data Science | digital-ai-finance.github.io/data-science |
| Cryptoeconomics | digital-ai-finance.github.io/Cryptoeconomics-Blockchain |

Module description files (PDF/DOCX) are served from each course's GitHub Pages at `/module-description/` path.

## Deployment

Push to `master` triggers automatic GitHub Pages build. No manual deployment needed.

Live URL: https://digital-ai-finance.github.io/Teaching/
