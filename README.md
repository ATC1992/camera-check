# Camera Check

A one-page tool that shows what a phone's cameras and browser can do.

Open the page on a phone, tap **Check my phone** and allow the camera. Then send the result file to whoever shared the link.

What it reads:

- **Each camera:** autofocus or fixed focus, closest focus distance, largest video and still-photo size, zoom range, torch, frames per second, and how long it takes to open.
- **The phone and browser:** model where the browser reports it, system and browser version, processor cores and memory, and graphics chip.
- **A short speed test:** one core compared with several cores at once.
- **Browser features:** which ones the browser supports.
- **An optional close-up test:** how sharp a wallet card looks through each back camera when it fills the same box on screen.

## Privacy

The page is a single `index.html` with no outside scripts, fonts or images. It sends nothing on its own. Its Content-Security-Policy (`connect-src 'none'`) blocks every network request.

The result is a small text file that the person shares or saves themselves. It contains no photos, no location and no camera IDs; the camera previews never leave the page.
