# villainy-of-zezzak

## File Structure and Deployment

The "docs" directory is published to a "Github Pages" website whenever you publish changes on the main branch.

Live URL: https://cookiebrains.github.io/villainy-of-zezzak/

## Converting and Optimizing Images

Requires Imagemagick to be installed first. To install on Windows, open an elevated terminal and run:

```
winget install imagemagick
```

Example command to convert from `png` to `webp` (first navigate to directory with image):

```
magick input.png output.webp
```

Example converting`webp` to `png`:

```
magick input.webp output.png
```
