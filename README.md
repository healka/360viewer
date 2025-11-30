# 360° Viewer for Squarespace

This repository hosts 360° panoramic viewers built with [Pannellum](https://pannellum.org/), designed to be embedded into Squarespace websites via iframes.

## Live Links

- **Viewer 1:** [https://healka.github.io/360viewer/viewer-001.html](https://healka.github.io/360viewer/viewer-001.html)
- **Viewer 2:** [https://healka.github.io/360viewer/viewer-002.html](https://healka.github.io/360viewer/viewer-002.html)

## How to Embed in Squarespace

Use a **Code Block** or **Embed Block** and paste the following code. Change the `src` URL to match the specific viewer you want to display.

```html
<iframe 
    src="https://healka.github.io/360viewer/viewer-001.html" 
    width="100%" 
    height="600" 
    frameborder="0" 
    allowfullscreen 
    scrolling="no">
</iframe>
```

## Features
- **Lazy Loading:** The viewer only loads the heavy 360° image when the user scrolls it into view.
- **Auto-Rotate:** Slowly rotates the view automatically.
- **Mobile Friendly:** Responsive width and touch controls.

## Adding New Renders
1. Upload your equirectangular image to the `assets/` folder.
2. Duplicate one of the `viewer-XXX.html` files.
3. Update the `imageUrl` variable in the new HTML file to point to your new image.
4. Push changes to GitHub.

