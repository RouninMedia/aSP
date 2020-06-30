# aSP
An **aSP** is an _ashiva Single-file Progressive-web-app_.

_____

Usually even a very simple web page will have a number of file dependencies.

Most HTML documents will be accompanied by:

 - an associated CSS Stylesheet, containing the styles (`.css`)
 - an associated JS Scriptsheet, containing the scripts (`.js`)
 - a `favicon`

Usually an HTML document will refer to:

 - images (`.jpg`, `.gif`, `.png`, `.webp`)

Additionally, it may refer to:

 - videos (`.mp4`, `avi`)
 
Sometimes, it may even refer to:

 - audio files, music or sound effects (`.mp3`)
 
 Finally, if the HTML document is a _Progressive Web App_ (PWA), it will also be accompanied by:

- a `manifest.webmanifest`
- a service worker (`.js`)

_____

_**This means**, if we take a PWA web page with a single image and no music or sound effects, **we are looking at no fewer than 7 separate files**_:

 1. HTML Document
 2. Image
 3. CSS Stylesheet
 4. JS Script
 5. Favicon
 6. Web Manifest
 7. Service Worker
 
 An **aSP** reduces this set of seven files (or more) to **one file**.
 
