# Slide 2 Print

Slide 2 Print is a client-side web utility that helps you format and arrange PDF slides for printing. Because it runs entirely in the browser, your files are processed locally and are never uploaded to any server.

This tool is useful for creating multi-page layouts, formatting handouts, or generating custom workbook templates for note-taking.

## Core Features

- **N-Up Layouts**: Arrange slides in custom grids (such as 2-up, 4-up, 6-up). You can control column/row count, orientation (auto, portrait, or landscape), fill order (rows or columns first), rotation, and margins.
- **Workbook Mode**: Insert lined, dashed, grid, or dot-grid note spaces next to, before, or after each slide. A split slider lets you adjust how much space is dedicated to notes.
- **Ink Saving**: 
  - *Optimize Backgrounds*: Flattens off-white or tinted slide backgrounds to pure white.
  - *Invert Colors*: Inverts dark slides (light text on dark backgrounds) to light pages to save printer ink.
- **Manual Duplex Split**: If you do not have a double-sided printer, the tool can split your document into separate front-page and back-page PDFs. It includes support for reversing back pages (for front-feed trays) and padding to even sheets.
- **File Management**: Merge multiple PDFs in a single queue, insert title separator pages between files, and export as a single PDF or a ZIP file of individual sheets.

## Technical Details

The application is built to run standalone in any web browser without any installation, command-line setup, or external dependencies.

- **React**: Renders the interface (compiled client-side via Babel).
- **Tailwind CSS**: Handles the visual layout.
- **pdf-lib**: Used for merging, drawing, and generating the final PDFs.
- **pdf.js**: Handles local PDF parsing and rendering page thumbnails.
- **JSZip & download.js**: Handles client-side archiving and file downloads.

## Quick Start

1. Download or clone this folder.
2. Open `index.html` in any web browser.
3. Drag and drop your PDFs into the browser window to start organizing.
