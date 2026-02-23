# Image Inserter Web App

A simple web application that allows users to insert images by URL, display them in a gallery, and copy the image URL by clicking on the image. Images are saved in the browser's localStorage so they persist across page reloads.

---

## Features

- Insert images using their URL.
- Display images in a responsive gallery.
- Click an image to copy its URL to the clipboard.
- Images are saved locally in the browser (localStorage) for persistence.

---

## Demo

> Enter an image URL, click **Add Image**, and the image will appear below. Clicking an image copies its URL.

---

## Installation / Usage

1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Enter an image URL in the input box and click **Add Image**.
4. Click any image in the gallery to copy its URL.

---

## File Structure

```
project-folder/
│
├── index.html        # Main HTML page
├── style.css         # External CSS file
└── README.md         # Project documentation
```

---

## Technologies Used

- HTML5
- CSS3 (external stylesheet)
- JavaScript (for interactivity and localStorage)

---

## Notes

- Only images accessible via URL can be added.
- Images are stored in the browser’s localStorage, so clearing browser data will remove saved images.
