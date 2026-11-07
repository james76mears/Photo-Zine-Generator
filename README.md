# Photo Zine Generator

A lightweight, browser-based utility built with Vanilla JavaScript, Tailwind-inspired styling, and vintage typewriter aesthetics.
Photographers can compile up to 36 JPG images and their EXIF metadata into a clean, landscape-oriented PDF.

Run the project live here https://james76mears.github.io/Photo-Zine-Generator/

## Features
* **EXIF Data Extraction:** Automatically reads camera settings (`F-Number`, `ExposureTime`, `ISO`, and `DateTimeOriginal`) from uploaded JPEG files using `exif-js`.
* **Client-Side Processing:** Runs entirely in the browser using `jsPDF`—no server uploads or backend required.
* **Smart Image Resizing:** Automatically scales and compresses images client-side for efficient PDF file sizes.
* **Vintage Aesthetic:** Features a nostalgic retro design complete with custom Courier typography and warm paper tones.
* **Catalogue Index Page:** Generates a structured two-column summary index containing all image filenames and EXIF data on the final page.
* **Flexible Paper Formats:** Supports both A4 and US Letter landscape layouts.

## Built With
* [HTML5 / CSS3](https://developer.mozilla.org/)
* [jsPDF](https://github.com/parallax/jsPDF) (v2.5.1) - PDF generation library
* [EXIF.js](https://github.com/exif-js/exif-js) - EXIF metadata extraction library
* [Google Fonts (Courier Prime)](https://fonts.google.com/specimen/Courier+Prime)

## Getting Started
Because this is a standalone single-file application, you do not need to install any complex build tools or run a local server.

1. Download or clone the `index.html` file to your computer.
2. Double-click the file to open it directly in any modern web browser (Chrome, Firefox, Safari, Edge).

## Usage
1. Open `index.html` in your web browser.
2. Enter a **Document Title** (required) and an optional description.
3. Select your preferred **Paper Size** (A4 Landscape or US Letter Landscape).
4. Click **Select JPG/JPEG Images** and choose up to 36 valid `.jpg` or `.jpeg` files.
5. Click **Generate Your PDF** to process the images, extract EXIF data, and automatically download your completed photo zine.
