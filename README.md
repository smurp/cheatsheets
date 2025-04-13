# Cheatsheets Collection

This repository contains a collection of cheatsheets for various tools and technologies, prepared in [Org-mode](https://orgmode.org/) format.

## About the Cheatsheets

Each cheatsheet is:
- Written in Org-mode, a powerful plain text markup language for Emacs
- Designed to be concise and practical for daily use
- Formatted for easy printing and reference
- Includes rendered PDF versions for immediate use

The PDF files include footer links back to the corresponding GitHub-rendered Org files, making it easy to access GitHub's HTML rendering from the .org sources.

## Current Cheatsheets

- **rTorrent**: A terminal-based BitTorrent client cheatsheet
  - [Org Source](rtorrent-ux.org)
  - [PDF Download](../../raw/main/rtorrent-ux.pdf)

- **Org-Mode TODO**: Org-Mode's TODO Management features
  - [Org Source](org-mode-todo.org)
  - [PDF Download](../../raw/main/org-mode-todo.pdf)

## Usage

You can use these cheatsheets in several ways:

1. **View directly on GitHub**: GitHub renders Org files fairly well
2. **Download the PDFs**: Ready-to-use reference documents
3. **Clone and modify**: Edit the Org files to customize for your needs

To generate PDFs from the Org files yourself:
1. In Emacs with Org-mode: `C-c C-e l p` (org-export-dispatch → LaTeX → PDF)
2. From the command line: `emacs --batch -l org rtorrent-ux.org -f org-latex-export-to-pdf`

## Requesting New Cheatsheets

I welcome requests for new cheatsheets, especially those related to:
- macOS
- Emacs
- Linux
- Command-line interfaces (CLI)
- Development tools

To request a new cheatsheet, please [open an issue](https://github.com/smurp/cheatsheets/issues/new) with:
- The tool or topic
- Key features that should be included
- Any specific format preferences

## Contributing

Contributions are welcome! If you'd like to:
- Fix errors in existing cheatsheets
- Add new sections to existing cheatsheets
- Create new cheatsheets

Please submit a pull request with your changes or additions.

## License

These cheatsheets are available under the [Creative Commons CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) license (CC0 1.0 Public Domain Dedication). This effectively places the content into the public domain, allowing anyone to use, modify, and distribute the material for any purpose without any restrictions.