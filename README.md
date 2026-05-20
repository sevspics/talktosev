# Talk To Sev

Marketing & Claude advisory practice for service businesses. Hosted on Vercel, deployed at talktosev.com.

Three pages:
- `index.html` — branching landing with interactive quiz (Marketing workshop vs. Claude With Me)
- `claude.html` — Claude With Me 60-min intro session ($385)
- `learning.html` — Learning Hub (videos + articles, placeholder content)

The Marketing workshop ($2,500 + GST) does not have a landing page on this site — every "Marketing" link points out to the apply page at `https://enquire.talktosev.com/apply`.

Vanilla HTML + CSS + a tiny bit of JS, no build step. Open `index.html` directly in a browser to preview.

## TODOs before launch

- Replace `#book-claude` href on `claude.html` with the Stripe / Calendly / GHL booking link for Claude With Me (search for `TODO` in that file)
- Drop in real workshop "in the room" photos for Claude page (placeholders are gradient blocks with `data-label` captions)
- Real video thumbnails + embeds for the Learning Hub items
- Wire Microsoft Clarity (or your heatmap of choice) for hero quiz tracking
