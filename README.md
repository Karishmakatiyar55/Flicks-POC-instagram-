# Flicks on Instagram · POC

Interactive proof of concept by Flam: Flicks (swappable, interactive videos) on Instagram. One phone, six formats:

1. **Stories playable ad** (Gucci)
2. **Creator reel → link in bio** (Necklace Swap)
3. **Story link sticker**, "Which fit tonight?" (Gap)
4. **Partnership ad, Shop now** (Nike)
5. **Content Flick: Get Ready With Me reel**
6. **Content Flick: MicroDrama between reels**, with an ad label and install button

On a laptop, pick a format from the list, or use the arrow keys or the scroll wheel. On a phone, each format is full screen; move between them with ‹ ›.

## Hosting on Vercel
Import this repository in Vercel (Add New → Project), framework preset **Other**, no build command, root directory unchanged. Every push to `main` redeploys.

## Notes
- `index.html` is self-contained: scripts, fonts and photos are inlined.
- The Flicks, the Gap Flick and the reel pages load live from their own sites, so present online.
- Audio stays muted until the viewer taps into a Flick, and stops when they leave it.
