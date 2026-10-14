# Camera Check

A one-page tool that shows what a phone's cameras and browser can do. It helps a trading-card scanner pick the right camera and settings on phones it hasn't seen before.

Open the page on a phone, tap **Check my phone**, allow the camera, then copy the result and send it to whoever shared the link.

What it reads:

- **Each camera:** autofocus or fixed focus, closest focus distance, largest video and still-photo size, zoom range, torch, frames per second, and how long it takes to open.
- **The phone and browser:** model where the browser reports it, system and browser version, processor cores and memory, and graphics chip.
- **A short speed test:** one core compared with several cores at once.
- **Browser features** the scanner could use.
- **An optional close-up test:** how sharp a card held about 10 cm away looks through each back camera.

## Privacy

The page is a single `index.html` with no outside scripts, fonts or images. It sends nothing anywhere. Its Content-Security-Policy (`connect-src 'none'`) blocks every network request, so it can't send data even by mistake.

The result is plain text that the person copies and shares themselves. It contains no photos, no location and no camera IDs; the small camera previews never leave the page.
