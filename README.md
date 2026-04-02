# MergeDocs - Premium PDF Merger

A beautiful, fast, and privacy-focused PDF merger that runs entirely in your browser. No uploads, no servers, no tracking.

**Live:** [https://pdf-merge-five-tawny.vercel.app/](https://pdf-merge-five-tawny.vercel.app/)

## Features

- **100% Client-Side** - Files never leave your device
- **Drag & Drop** - Easily upload multiple PDFs
- **Reorder Files** - Drag to reorder or use the arrow buttons
- **Dark/Light Mode** - Toggle between themes
- **Progress Indicator** - Visual feedback during merge
- **Custom Output Filename** - Name your merged file

## Usage

1. Open the app in your browser
2. Click or drag & drop PDF files into the upload area
3. Reorder files if needed using drag or arrow buttons
4. Enter a filename (optional)
5. Click "Merge & Download"

## Tech Stack

- HTML5, CSS3, JavaScript (Vanilla)
- [pdf-lib](https://pdf-lib.org/) - Client-side PDF manipulation
- [Outfit](https://fonts.google.com/specimen/Outfit) font from Google Fonts
- Vercel for deployment

## Local Development

No build step required. Simply open `index.html` in a browser.

Or serve locally:

```bash
npx serve .
```

## Privacy

All processing happens in your browser using WebAssembly (pdf-lib). Your files are processed locally and never uploaded to any server.
