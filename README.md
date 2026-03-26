# 🛠️ PDF Tools (On-Device)

A suite of lightweight, privacy-focused PDF utilities that run entirely in your web browser. Your files are never uploaded to a server; all processing happens locally on your machine.

## 🚀 Included Tools

### 1. PDF Squish (Compressor)
- **File:** `index.html`
- **Function:** Re-renders PDF pages as optimized JPEGs to significantly reduce file size.
- **Best for:** Reducing large PDFs for email or web uploads.
- *Note: This tool flattens the PDF (text becomes non-selectable).*

### 2. PDF Extractor (Splitter)
- **File:** `pdf-splitter.html`
- **Function:** Preview and extract specific pages or ranges (e.g., 1-3, 5) into a new PDF.
- **Best for:** Removing unnecessary pages or splitting a large document.

## ✨ Key Features
- **100% Client-Side**: Powered by JavaScript. No data ever leaves your browser.
- **Instant Preview**: See thumbnails of your pages before you process them.
- **Zero Setup**: Works in any modern browser without installation.

## 🛠️ Built With
- [pdf-lib](https://pdf-lib.js.org/) - For PDF manipulation and assembly.
- [pdf.js](https://mozilla.github.io/pdf.js/) - For rendering and previewing PDF pages.

## ⚖️ License & Attribution
This project is open-source under the MIT License. 

- **pdf-lib**: Copyright (c) 2019 Andrew Dillon (MIT License)
- **pdf.js**: Copyright (c) Mozilla Foundation (Apache License 2.0)
