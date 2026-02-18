# Online Pic Annotator

A simple, client-side web application for annotating images directly in your browser.

![Demo](https://img.shields.io/badge/Status-Ready-brightgreen) ![License](https://img.shields.io/badge/License-MIT-blue)

## Features

*   **Draw & Annotate:** Supports lines, arrows, dashed lines, rectangles, circles, and freehand drawing.
*   **Text & Styling:** Add text annotations with customizable color, size, and font.
*   **Editing Tools:** Includes an eraser, undo/redo functionality, and a clear canvas option.
*   **Flexible Loading:**
    *   Upload an image from your device.
    *   Load an image via URL.
    *   **Auto-Load via URL Parameters:** Preload an image automatically by passing a URL parameter (great for sharing direct links).
*   **Export:** Download the annotated image or copy it to the clipboard.

## Usage

### Basic Annotation
1.  Open the [Web App](https://dombor215.github.io/Online-Pic-Annotator/).
2.  Paste an image URL in the input box and click **Load URL**, or click **Upload** to choose a file.
3.  Select a tool from the toolbar (e.g., Rect, Arrow, Text).
4.  Draw on the canvas.
5.  Click **Download** to save your work.

### Preloading an Image via URL
You can create a direct link that automatically loads an image when the page opens. This is useful for sharing a specific image for annotation.

**Format:**
```
https://dombor215.github.io/Online-Pic-Annotator/?initial_url=YOUR_IMAGE_URL
```

**Example:**
```
https://dombor215.github.io/Online-Pic-Annotator/?initial_url=https://i.postimg.cc/jdThVHFH/elastic_pendulum.png
```

*Note: Ensure the image URL is publicly accessible.*

## License

This project is open source and available under the [MIT License](LICENSE).