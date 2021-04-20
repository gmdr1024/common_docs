# honkit-dev
Honkit dev

## Description
Documentation dev based `Markdown & mermaid` 

## Feature
- Wrap [Honkit](https://www.npmjs.com/package/honkit) with `npm-scripts`
- Available `mermaid` by [mermaid-newface plugin](https://www.npmjs.com/package/gitbook-plugin-mermaid-newface)

## Requirement
Node.js 14.16.x

## Pre-Install
- [Node.js](https://nodejs.org/) 
- [EditorConfig](https://editorconfig.org/)
- Enable `ebook-convert` for generate PDF file
  1. Download & install [Calibre](https://calibre-ebook.com/download)
  2. Add the installation folder path to your environment variables


## Install
1. Download [code](https://github.com/gmdr1024/honkit-dev/archive/main.zip)
2. `npm i` under `docs`

## Usage
- Execute command under `docs`

### Create page
1. Add link to `~~.md` to `docs/SUMMARY.md` (Table of contents)
2. Add `~~.md` file  to `doc/pages`

### Start a local server and render
- `npm start`

### Generate static files
- `npm build` (To `_book`)

### Generate PDF file
- `npm pdf` 

## Author
[gmdr1024](https://github.com/gmdr1024)

## License
[CC0](https://github.com/gmdr1024/honkit-dev/blob/main/LICENSE) 
