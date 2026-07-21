# New Tabs for Jira Data Center Kanban Boards

A small open-source Chrome extension that opens Jira Data Center Kanban board tickets in new tabs while preserving drag and drop.

## Requirements

For the smoothest possible board behavior, the Jira detail view should be hidden in the board settings. Version 1.8.0 includes a layered, non-invasive check that reports whether the detail view appears hidden, visible, or cannot be determined reliably.

## Features

- Opens ticket cards in new foreground or background tabs
- Preserves Jira drag and drop
- German, English, and Spanish interface
- Detects Jira Kanban cards
- Checks the Jira detail-view state using multiple UI signals
- No analytics, tracking, or external data transmission

## Privacy

Issue keys and links are processed locally in the browser. Settings are stored locally using Chrome storage.

## License

MIT License. Copyright (c) 2026 Steffen Liss.

This project is independent and is not affiliated with or endorsed by Atlassian.
