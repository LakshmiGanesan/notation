<p align="center"><img src="icons/icon-512.png" width="120" alt="Notation icon: a fountain pen with a microphone crown, writing Sa on a notebook"></p>

# Notation

**A handwriting-and-audio notebook for Carnatic music and chants.**

Write your notation by hand on tāḷa templates, record the lesson, and let every mark sing back. Tap a mark on the page and Notation plays the passage that was being sung when you made it.

Notation grew out of many years of using a general note-taking app for Carnatic lessons, and from noticing where a general app falls short for music. It is built around one way of working:

1. **Before class**, write the notation on a template, such as Ādi, Rūpaka or Miśra Chāpu, or start from a plain grid.
2. **In class**, press Record. Each time a line or saṅgati begins, place a small mark in the margin. Every mark becomes an audio bookmark.
3. **When practising**, tap any mark to hear that passage. Loop it, or slow it down.

The same approach works for chants and ślokas: bring in the script as a PDF, record the chanting, and mark each verse.

## What it does

- **Pens:** an even-weight pen for notation in five sizes, and a pressure-sensitive calligraphy pen with a broad nib for headings.
- **Colour:** five built-in colours plus your own palette, with a colour picker and an eyedropper that picks any colour from the page.
- **Highlighter, eraser, undo and redo.** Apple Pencil writes, and fingers scroll and tap.
- **Lasso:** select ink freehand or with a rectangle, then move, copy, cut, duplicate, recolour or delete it. Paste works across pages and notes. On a Mac, ⌘C, ⌘X, ⌘V, ⌘D and Delete work too.
- **Audio bookmarks:** anything you draw while recording, or while a recording plays, is linked to that moment.
- **Hand tool:** tap any linked mark (pen, calligraphy or highlighter) to play from that moment. Tap ink written before class to link it to wherever the recording is now.
- **Practice:** tap-to-play with a short lead-in, loop a passage, play at 0.5×, 0.75× or 1.25×, and follow along as the page scrolls. Jumping to a bookmark from the list or the timeline turns straight to its page.
- **Templates:** Ādi, Rūpaka, Miśra Chāpu, Khaṇḍa Chāpu, Viloma Chāpu, Tisra Triputa, Khaṇḍa Triputa, Miśra Jhampa, and a plain grid.
- **Covers and section dividers:** a Song details page, plus 22 hand-printed textile designs, each with a label holder for the title.
- **Your own designs:** add any PDF or image to either library.
- **Notation books:** import a PDF of any length, or a set of photos and scans, then add, move or remove pages.
- **Folders:** Music and Chants come built in, with one level of subfolders.
- **Sharing:** export a note as a single file that plays the notation and audio in any browser.
- **Offline:** once opened online, Notation works without Wi-Fi.

Pages are sized for the iPad Pro 11" screen (2388 × 1668).

## Using it

Notation is a web app. It runs in the browser and can be added to the Home Screen or Dock like a native app.

- **iPad:** open the site in Safari, then Share → **Add to Home Screen**.
- **Mac:** open the site in Safari, then File → **Add to Dock**.
- **iPhone:** works as a reference viewer, the same way as on iPad.

The microphone works only when Notation is opened from its `https://` address.

## Where your notes live

Notes, recordings and your own designs are stored on each device, inside the app. Nothing is uploaded anywhere. Google Drive sync, to back up the library and share it between iPad and Mac, is planned.

## Status

Notation is in active, personal development. Features and storage formats may still change.

## In this repository

| Path | What it holds |
|---|---|
| `index.html` | The app |
| `templates/` | Notation templates, covers and their previews |
| `lib/pdfjs/` | The PDF reader used for importing PDFs ([PDF.js](https://mozilla.github.io/pdf.js/), Apache 2.0) |
| `icons/`, `manifest.webmanifest` | App icon and install details |
| `sw.js` | Offline support |

## Copyright

© 2026 Lakshmi Ganesan. All rights reserved.

The code, templates, cover designs and icon in this repository are not licensed for reuse, copying or redistribution. You may view them here, but please do not copy or republish them without written permission. PDF.js is included under its own Apache 2.0 licence.
