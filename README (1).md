# PDF Read Aloud

Upload a PDF and it reads the whole document aloud at a normal pace, from the first page to the last, highlighting each sentence as it goes.

**Live site:** https://edward-owusu.github.io/pdf-read-aloud/

## Features

- **Starts automatically**: choose a PDF and reading begins right away
- **Reads to the end**: continues page by page until the document is finished
- **Follow along**: the sentence being read is highlighted and the page scrolls with it
- **Full control**: play/pause, skip or go back a sentence, jump between pages, click any sentence to start there
- **Speed and voice**: Normal speed by default, with Slow to Fast options and a choice of voices
- **Remembers your place**: close the tab and pick up where you stopped
- **Scanned PDFs**: text is recognized page by page with OCR

## Privacy

Your PDF never leaves your device. Everything runs in your browser: nothing is uploaded, stored or tracked.

## How it works

- [PDF.js](https://mozilla.github.io/pdf.js/) extracts the text from the PDF
- The browser's built-in Web Speech API reads it aloud
- [Tesseract.js](https://tesseract.projectnaptha.com/) recognizes text in scanned pages (loaded only when needed)

It is a single `index.html` file with no build step and no server.

## Tips

- Microsoft Edge and Google Chrome usually offer the most natural voices.
- On phones, keep the screen on while it reads.
- Press the space bar to pause or play.

## Author

Built by [Edward Owusu, CISA](https://edward-owusu.github.io/)
