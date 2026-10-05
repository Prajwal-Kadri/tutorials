# Troubleshooting

## Slider images not showing on Home page

In `index.html`, slider image paths currently reference `iamges/` and `pics/` in places, while repository assets are under `images/`.

If the slider appears broken, fix image source paths to match existing files in `images/`.

## Gallery images not loading

Check that:

- `images/fullscreen/*` files exist
- `images/thumbnails/*` files exist
- `js/jquery.prettyPhoto.js` and `css/prettyPhoto.css` are correctly linked

## Styling not applied

Verify CSS links on each page:

- `css/style.css`
- `css/prettyPhoto.css` (for gallery page)

## JavaScript interactions not working

Check script includes and load order:

- `js/jquery.js` first
- Then plugin scripts (`easySlider1.7.js`, `jquery.prettyPhoto.js`)
- Then inline initialization scripts

## Map not rendering on Contact page

The page uses an embedded Google Maps iframe. If blocked locally, verify network access and browser privacy restrictions.
