# Sic

A small native Mac editor for JSON, Markdown, and text files. Named for *sic*: your files, exactly as written.

[Website](https://iamjason.github.io/sic-site/) · [Releases](https://github.com/iamjason/sic-site/releases) · [Report an issue](https://github.com/iamjason/sic-site/issues)

Open each file exactly as written, format JSON only when requested, and edit Markdown as source or as a rendered page that stays in sync with it. Sic uses native document windows, file dialogs, Undo/Redo, and Find. Files stay on your Mac.

Requires macOS 15 or later. Universal builds support Apple silicon and Intel. Supports UTF-8 and BOM-marked UTF-16 text files up to 2 MB.

This public repository hosts the website, artwork, and signed, notarized releases. Application source is maintained separately.

## Install

Download [Sic 0.3.0](https://github.com/iamjason/sic-site/releases/download/v0.3.0/Sic-0.3.0.zip), unzip it, and drag Sic.app to Applications. A [SHA-256 checksum](https://github.com/iamjason/sic-site/releases/download/v0.3.0/Sic-0.3.0.zip.sha256) accompanies the release.

## Hyrule Compendium

The `hyrule.json` manifest and `hyrule-tool` repository topic register Sic with the [Compendium](https://iamjason.github.io/hyrule-compendium-site/).

The site is served by GitHub Pages from `main:/`. No build step or runtime dependencies are required.

## Usage statistics

This site records anonymous usage statistics: page views, download clicks and a daily visitor count derived from a hash of your IP address and browser. No cookies, no personal data, nothing stored in your browser. The collector is [Gossip Stone](https://github.com/iamjason/gossip-stone-swift#what-is-sent).
