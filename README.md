

https://buti-research.github.io/OMB_PdfCertStamp/


## Tech Stack

- **HTML/CSS**: For the structure and styling of the web application.
- **JavaScript**: For interactivity and PDF manipulation.
- **Libraries**:
  - [pdfjs-dist](https://github.com/mozilla/pdfjs-dist) for rendering PDF files to image.
  - [signature_pad](https://github.com/szimek/signature_pad) for signature creation.
  - [fabric.js](http://fabricjs.com/) for handling canvas and stamps.
  - [pdf-lib](https://pdf-lib.js.org/) for PDF manipulation.
  

## Getting Started

### Prerequisites

Ensure you have a modern web browser that supports HTML5 and JavaScript ES6.

## How It Works

1. **Load PDF**: Select a PDF file from your local system or input a URL to load a remote PDF.
2. **Add Stamps**: 
   - Click on the `Add` button to add a new stamp.
   - You can draw your signature on a canvas or upload an image to use as a stamp.
3. **Manage Stamps**: 
   - Drag and resize the stamp to fit the desired position on the PDF.
   - Adjust the opacity using the slider.
   - Set the repeat interval for the stamp to appear on multiple pages.
4. **Navigate Pages**: Use the `Prev` and `Next` buttons to navigate between pages.
5. **Download PDF**: Click the `Download` tab once you're satisfied with your stamps.

## Local Storage

Stamps are stored in the browser's `localStorage` under the key `pdf-stamps-srcStamps`. This allows you to reuse them even after refreshing the page.
