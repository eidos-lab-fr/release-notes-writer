# Release Notes Writer

Turn a list of commits or tickets into release notes written for the people who use the product.

**[Website](https://eidos-lab-fr.github.io/release-notes-writer/about.html)** · **[Open the app](https://eidos-lab-fr.github.io/release-notes-writer/)**

## Features

- Entries written from the reader's point of view, grouped into New, Improved and Fixed
- Internal changes are listed under "Not included" rather than dropped silently
- Three audiences (customers, internal teams, developers), three tones, three languages
- Streams the notes, then copy or download them as Markdown

## Usage

Open `index.html` in a browser, paste an [Anthropic API key](https://console.anthropic.com/), and run it. There is nothing to install and nothing to build.

## Your key, your cost

This page has no server. It calls the Anthropic API straight from your browser with **your own key**:

- The key is kept in the browser tab, or on the device if you tick "Remember". It is sent only to `api.anthropic.com`.
- Nobody else's key is involved, so hosting this page publicly costs its owner nothing.
- Each run shows the tokens used and an estimated cost. Use a key with a spending limit.

The Anthropic SDK is loaded from `esm.sh` at a pinned version. You can choose between Claude Opus 5.5, Sonnet 5.5 and Haiku 5.5.

## Stack

A single HTML file. Anthropic TypeScript SDK loaded as an ES module.

## License

[MIT](LICENSE) © 2026 Eidos Lab
