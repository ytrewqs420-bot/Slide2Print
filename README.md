# 🖨️ Slide 2 Print

**Slide 2 Print** is a premium, client-side web application designed to optimize, arrange, and prepare PDF slides for printing. Designed as a standalone, zero-server-upload utility, it runs entirely in your web browser—guaranteeing 100% data privacy and lightning-fast local performance.

Whether you need to print standard handouts, format dual-sided pages on a non-duplex printer, or design custom lined study workbooks from lecture slides, Slide 2 Print provides a complete visual studio layout to get it done.

---

## 🌟 Key Features

### 🔒 100% Client-Side & Private
No files are ever uploaded to a server. All PDF parsing, page manipulation, rasterization, and assembly happen directly in your browser using WebAssembly and modern JavaScript libraries. 

### 📐 Fully Customizable N-Up Layouts
- **Custom Grids**: Arrange slides in any custom grid up to 6x6 (e.g., 2-up, 4-up, or 6-up).
- **Orientation Control**: Auto-detects optimal layouts or lets you force Portrait or Landscape sheets.
- **Flow & Order**: Choose between column-first or row-first placement.
- **Precision Spacing**: Customize margins and padding to maximize slide visibility.
- **Slide Rotation**: Rotate individual slides (90°, 180°, 270°) to correct landscape/portrait mismatches.

### 📓 Interactive Workbook Mode
Convert any presentation deck into a professional note-taking workbook instantly.
- Inserts customizable note-taking spaces (lined, dashed, grid, or dot-grid styles) next to, before, or after each slide.
- Features a real-time ratio slider to adjust the split between the slide and note sections.
- Add a custom header (e.g., *"Lecture Notes"*, *"Meeting Minutes"*) to the note spaces.

### 🔋 Smart Ink & Paper Savers
- **Optimize Backgrounds**: Automatically detects light-colored slide backgrounds (yellowish paper, tints) and flattens them to pure white—saving immense amounts of printer ink.
- **Invert Dark Mode Slides**: Easily invert dark slides (light text on dark backgrounds) into light slides for cleaner, more readable prints that won't drain your black ink.
- **Fast Preview Mode**: Option to export drafts at a fast 72 DPI, saving CPU cycles and previewing layouts in seconds.

### ⚡ Professional Print Prep (Manual Duplex & Separators)
- **Manual Duplex Splitter**: No double-sided printer? No problem. The app can split your job into separate front-page and back-page PDFs, complete with reverse-order printing support for front-feed trays and auto-generated printing instructions.
- **File Separators**: Batch process multiple PDFs and automatically insert custom title divider sheets between each document.
- **Split Files**: Choose to start each document in your queue on a fresh sheet of paper.
- **Flexible Exporter**: Export as a single unified PDF or a ZIP archive containing individual document sheets.

---

## 🎨 Premium UI/UX Design

Built with modern aesthetics, the studio interface features:
- **Responsive Layout**: Resizable control surfaces and interactive panels.
- **Live Canvas Preview**: Real-time mockups of how your slides and notes will map onto paper sheets.
- **Dynamic Selection Modal**: Browse PDF pages as high-resolution thumbnails, filter specific pages (e.g., `1, 4-8, 12, last`), and build custom page sequences.
- **Local Presets Storage**: Save your custom grid configurations, layouts, and style parameters to load them instantly next time.
- **Clean Dark & Light Modes**: Beautiful transitions, custom typography (Manrope & Newsreader), and smooth animations.

---

## 🛠️ Built With

Slide 2 Print is built to run anywhere without configuration:
- **Core Framework**: React 18 (Client-side rendering via Babel)
- **Styling**: Tailwind CSS
- **PDF Core**: [pdf-lib](https://pdf-lib.js.org/) (PDF generation, merging, drawing) and [pdf.js](https://mozilla.github.io/pdf.js/) (Local page rendering and thumbnail creation)
- **Utilities**: [JSZip](https://stuk.github.io/jszip/) (Client-side zip archiving) and [download.js](http://danml.com/download.html) (Client-side downloads)

---

## 🚀 Quick Start (No Setup Required!)

Because Slide 2 Print is entirely standalone, there are no dependencies to install, no servers to boot, and no bundlers to run. 

1. **Download** or clone the folder containing `index.html`.
2. **Double-click** `index.html` to open it in any modern web browser (Chrome, Firefox, Edge, Safari).
3. **Drop your PDFs** into the dropzone and start customizing your print layout!

---

## 📝 License

This project is open-source. Feel free to fork, customize, and improve!
