# Devs Alive: Do the Five

A lightning talk presented at DevNQ: turns out that the water safety and
drowning prevention program _Kids Alive: Do the Five_ has actually be teaching
IT security all these years.

* View Online: <https://davidjb.github.io/2019-devnq-devs-alive/>
* Slides PDF: <https://github.com/davidjb/2019-devnq-devs-alive/raw/master/slides-web.pdf>

## Setup

```bash
yarn
yarn start
```

This starts the presentation server at <http://localhost:8080> and
automatically opens a browser.

## Creating a PDF

```bash
yarn pdf
```

Look for the `.pdf` file in the current directory.  To optimise the file for the web:

```bash
brew install ghostscript
yarn optimise-pdf
```

## Stack

* `yarn`
* `reveal.js`
* `live-server` (for serving/reloading on changes)
* `decktape` (for creating PDFs from the slides)
* `GhostScript` (for optimising the PDF output)
* Devs Alive logo created by  https://logojoy.com (click Share and extract SVG from page)
