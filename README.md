# Download Marathon Photos

A simple Chrome helper for saving the images already shown on your marathonphotos.live results page.

## What It Does

- Finds Marathon Photos image links after you paste copied page code.
- Saves the photos it finds in a batch.
- Skips repeated links automatically.
- Saves files with their original photo-code filenames, such as `ZUKD1853.jpeg`.
- Lets Chrome save to a chosen folder when your browser supports it.

## How To Use

1. Open your Marathon Photos Live result page.
2. Wait until the photos on the current page are visible.
3. Open Chrome's three-dot menu and choose **More Tools > Developer Tools**.
4. In Chrome DevTools, find the `<body>` element.
5. Right-click `<body>` and choose **Copy > Copy element**.
6. Paste the copied page code into the tool.
7. Choose a folder if desired, then run **Download Photos**.
8. Repeat for each additional Marathon Photos results page.

## Notes

- This tool only downloads image files that are already present in the copied page code.
- It does not bypass login, checkout, paywalls, or access controls.
- Marathon Photos preview images may include watermarks. Only download and use photos you have the rights or permission to access.
- For licensed use, purchase the official photo pack or use originals provided by Marathon Photos.
- Downloads run with up to 5 photos at a time and rename same-name files automatically.

## Browser Support

- Best: Google Chrome on desktop.
- Folder selection requires Chrome 86+.
- Mobile browsers are not supported for bulk downloads.

## License

MIT
