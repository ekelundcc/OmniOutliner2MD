# OmniOutliner2MD

## OmniOutliner to Markdown Exporter
A simple OmniOutliner plugin that exports your outlines to Markdown format with automatic numbering, hierarchical headers, and preserves links in notes.

## Features

- Converts outline hierarchy to Markdown headers (`#`, `##`, `###`, etc.)
- Automatic numbering (1, 1.1, 1.1.1, etc.)
- Preserves notes as plain text under each heading
- Converts links in notes to proper Markdown link format `[text](url)`
- Copies result directly to clipboard

## Installation

1. In OmniOutliner, go to **Automation > Console**
2. Click the **+** button to create a new action
3. Copy and paste the code from `copy-to-md.omnijs` into the editor
4. Save the action
5. The plugin will now appear in your Automation menu

## Usage

1. Open your outline in OmniOutliner
2. Run the "Copy to Markdown" action from the Automation menu
3. Paste the Markdown anywhere you need it

## Development

This plugin uses the [Omni Automation](https://omni-automation.com/tutorial/og-macos/index.html) JavaScript API for OmniOutliner.

## License

MIT License - see LICENSE file for details

## Requirements

- OmniOutliner 5 or later (macOS)

## Author

Fredrik Ekelund
