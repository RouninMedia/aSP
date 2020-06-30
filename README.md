# aSP
An **aSP** is an _ashiva **Single-File** Progressive Web App_.

It's a _big deal_, because the _PWA_ consists of a _**single file**_.

## Ummm... isn't it pretty straightforward to make a _PWA_ from a single file, anyway?

No, it isn't. Even if you have a single HTML file, you're probably going to end up with almost twice as many files as the number of fingers you have on one hand.

## Eh?! _Almost_ eight files? (_Do you mean seven files?_) How so?

Ahem. Because. Usually even a very simple web page will have a number of **_file dependencies_**.

So much so, you can easily get to _**seven files**_ without trying. Still not convinced?

_**Keep count**_ as we go through the following list...:

Start with:

 - an HTML document (`.html`)

Then, most HTML documents will be accompanied by:

 - an associated CSS Stylesheet, containing the styles (`.css`)
 - an associated JS Scriptsheet, containing the scripts (`.js`)
 - a `favicon`

Additionally, an HTML document will usually refer to:

 - images (`.jpg`, `.gif`, `.png`, `.webp`)

_Additionally_, the HTML document may also refer to:

 - videos (`.mp4`, `avi`)
 
Sometimes, it may even refer to:

 - audio files, music or sound effects (`.mp3`)
 
 Finally, if the HTML document is a _Progressive Web App_ (PWA), it will also be accompanied by:

- a `manifest.webmanifest`
- a service worker (`.js`)

_____

_**This means**, if we take a PWA web page with a single image and no music or sound effects, **we're looking at no fewer than seven separate files**_:

 1. HTML Document
 2. Image
 3. CSS Stylesheet
 4. JS Script
 5. Favicon
 6. Web Manifest
 7. Service Worker
 
 An **aSP** uses a combination of standard techniques and it really does reduce this set of _**seven files**_ (or more) to **one single file**.
 
