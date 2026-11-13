# Flicks on Instagram · POC

Interactive proof of concept by Flam: Flicks (swappable, interactive videos) on Instagram. One phone, five formats:

1. **Instagram Stories**: two story ads that are Flicks (Gucci, then Necklace Swap)
2. **Partnership ad, Shop now** (Nike)
3. **Content Flick: Get Ready With Me reel**
4. **Content Flick: MicroDrama between reels**
5. **Creator profile → link in bio** (Necklace Swap)

On a laptop, pick a format from the list, or use the arrow keys or the scroll wheel. On a phone, each format is full screen; swipe up or down to move between them.

## Hosting on Vercel
Import this repository in Vercel (Add New → Project), framework preset **Other**, no build command, root directory unchanged. Every push to `main` redeploys.

## Notes
- `index.html` is self-contained: scripts, fonts and photos are inlined.
- The Flicks, the Gap Flick and the reel pages load live from their own sites, so present online.
- Audio stays muted until the viewer taps into a Flick, and stops when they leave it.
