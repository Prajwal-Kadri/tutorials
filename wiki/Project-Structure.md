# Project Structure

Repository root: `/home/runner/work/tutorials/tutorials`

## Top-level files

- `index.html` - Home page with slider and top navigation
- `about.html` - About page
- `picture.html` - Gallery page with prettyPhoto lightbox
- `contact.html` - Contact page with embedded map and form
- `README.md` - Minimal project note

## Directories

- `css/`
  - `style.css` - Core layout and component styling
  - `prettyPhoto.css` - Lightbox styles
- `js/`
  - `jquery.js` - jQuery library
  - `easySlider1.7.js` - Slider plugin
  - `jquery.prettyPhoto.js` - Lightbox plugin
- `images/`
  - `fullscreen/` - Full-resolution gallery images
  - `thumbnails/` - Gallery thumbnail images
  - `prettyPhoto/` - prettyPhoto skin assets
  - Additional standalone images (for logo/hero/slider usage)

## Navigation model

Each page includes a shared top navigation linking:

- HOME (`index.html`)
- ABOUT (`about.html`)
- PICTURES (`picture.html`)
- CONTACT (`contact.html`)
