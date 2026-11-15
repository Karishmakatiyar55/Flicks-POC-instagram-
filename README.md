# Flicks on Instagram · POC

Interactive proof of concept by Flam: Flicks (swappable, interactive videos) inside Instagram's own formats. One phone, three formats:

1. **Flicks in Stories**: two story ads that are Flicks (Gucci, then Necklace Swap)
2. **Flicks in Post**: a sponsored post whose media is the Nike Flick, swappable inside the post. Shop now goes to nike.com
3. **Flicks in Reels**: three sponsored reels, each one a Flick with a minimal Reels UI over it (Get Ready With Me, Puffer jacket swap, Necklace swap)

On a laptop, pick a format from the list beside the phone (the arrow keys also work). On a phone, each format is full screen: tap the draggable Formats button and pick a format; the button pulses a few seconds after each format opens. Scroll and swipe work inside Reels only, to move from one reel to the next; they never change the format.

## Hosting on Vercel
Import this repository in Vercel (Add New → Project), framework preset **Other**, no build command, root directory unchanged. Every push to `main` redeploys.

## Notes
- `index.html` is self-contained: scripts, fonts and photos are inlined.
- The Flicks load live from their own sites, so present online.
- Audio stays muted until the viewer taps into a Flick, and stops when they leave it.
