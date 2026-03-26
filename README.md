# 📄 PDF Squish

**PDF Squish** is a privacy-first, on-device PDF compressor that runs entirely in your web browser. Unlike traditional online tools, your documents are never uploaded to a server—all "squishing" happens locally on your machine.

## ✨ Features

* **100% Client-Side**: Your files stay on your device for maximum security.
* **Real Compression**: Re-renders PDF pages at optimized quality levels.
* **Three Quality Modes**: Choose between Light, Medium (Recommended), or High compression.
* **Visual Metrics**: Displays original size, squished size, and total percentage saved.
* **No Setup**: A single-file HTML solution that works in any modern browser.

## 🛠️ How it Works

The tool uses a "rendering" technique to reduce file size:
1.  **Loading**: It uses `pdf.js` to read the original document.
2.  **Rendering**: Each page is drawn onto an HTML5 canvas at a specific scale.
3.  **Encoding**: The canvas is converted into an optimized JPEG image based on your chosen quality.
4.  **Rebuilding**: `pdf-lib` gathers these images and packages them into a brand-new, smaller PDF.

> [!IMPORTANT]
> **Text Selectability**: Because this tool re-renders pages as images to achieve high compression, the resulting PDF will have "flattened" pages. This means text will no longer be selectable or searchable.

## 🚀 Quick Start

1.  **Download** the `index.html` file from this repository.
2.  **Open** the file in your preferred web browser.
3.  **Drag and drop** your PDF and click **Squish It**.

## 📚 Libraries Used

* [pdf-lib](https://pdf-lib.js.org/) - For creating and modifying PDF documents.
* [pdf.js](https://mozilla.github.io/pdf.js/) - For rendering PDF pages.
* [Google Fonts](https://fonts.google.com/) - Using 'Syne' and 'DM Mono' for the interface.

## ⚖️ License

This project is open-source. Please ensure you comply with the licenses of the included third-party libraries (MIT and Apache 2.0).

## ⚖️ Legal & Attribution

This project is provided "as is" under the MIT License. It utilizes the following third-party libraries:

- **pdf-lib**: Copyright (c) 2019 Andrew Dillon ([MIT License](https://github.com/Hopding/pdf-lib/blob/master/LICENSE.md))
- **pdf.js**: Copyright (c) Mozilla Foundation ([Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0))
- 
