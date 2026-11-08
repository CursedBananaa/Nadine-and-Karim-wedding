# Karim & Nadine â€” Wedding Celebration Website

An interactive, responsive digital wedding invitation and celebration website recreated from [ChungDoi](https://chungdoi.com/i/karim-nadine-wedding).

---

## Features

- **Royal Navy Opening Envelope**:
  - Ambient falling flower petals and gentle drifting particles.
  - Heartbeat-pulsing royal wax seal with heart glyph.
  - Elegant typography for **Karim & Nadine** and "Cordially Invites".
  - Glowing **Open** button with light sweep animation.
  - Interactive seal-breaking transition and smooth reveal.
- **Background Music Player**:
  - Floating circular vinyl / floral player button at the bottom-right.
  - Acoustic piano romantic melody synthesized natively via the Web Audio API (Pachelbel's Canon in D progression) so it works offline and across all browsers without external dependencies.
  - Also supports playing an MP3 file placed at `assets/wedding-music.mp3`.
  - Toggle play/pause anytime with spinning disc animation and equalizing soundwaves.
- **Hero & Announcement Sections**:
  - Royal crest ornaments, vintage chateau castle illustration, and drifting clouds.
  - Large framed couple hero photo.
  - Elegant typography in *Viaoda Libre*, *EB Garamond*, *Alex Brush*, and *Cormorant Garamond*.
- **Interactive 3D Coverflow Photo Gallery**:
  - 6 couple celebration photos rendered in an interactive 3D perspective deck.
  - Click any side photo to rotate it into focus, or use the prev/next arrow buttons.
  - Supports mobile touch swipe gestures and keyboard arrow navigation.
  - Dot pagination indicators.
  - **Fullscreen Lightbox Modal**: Click the active photo to view in high resolution with counter (e.g. `1 / 6`), navigation arrows, and a thumbnail strip.
- **Event Date, Countdown & Framed Calendar**:
  - Scheduled for **Thursday, December 10, 2026 at 6:00 PM** (Cairo time).
  - Real-time countdown timer tracking Days, Hours, Minutes, and Seconds.
  - Framed vintage December 2026 calendar highlighting the 10th with a heart marker.
  - **Add to Calendar**: Instant link for Google Calendar and one-click `.ics` download for Apple Calendar and Outlook.
- **RSVP Form & Confetti**:
  - "CONFIRM ATTENDANCE" modal popup.
  - Collects guest name, attendance status ("Joyfully Accept" or "Regretfully Decline"), guest count, and personalized wishes.
  - Colorful celebratory confetti burst on submission.
  - Saves RSVPs locally in `localStorage` (`karim_nadine_rsvps`).
- **Venue & Google Maps Integration**:
  - Venue: **QASR RAS ELTEEN** (Ras El Tin Palace, Alexandria, Egypt).
  - Direct link to Google Maps for navigation.
- **Thank You & Couple Signature**:
  - Flying doves illustration, message of gratitude, and couple signature.

---

## How to View the Website

1. Simply open `index.html` in any web browser (Chrome, Safari, Edge, Firefox).
2. To skip the envelope animation directly, add `?open=1` to the URL:
   `index.html?open=1`

---

## File Structure

```text
wedding invition/
â”œâ”€â”€ index.html       # Main HTML markup
â”œâ”€â”€ styles.css       # Complete responsive styling & animations
â”œâ”€â”€ app.js           # Interactive logic, audio synthesis, 3D gallery, RSVP
â”œâ”€â”€ README.md        # Documentation
â”œâ”€â”€ assets/          # High-resolution couple photos & theme ornaments
â”‚   â”œâ”€â”€ 71ac7da4-bfab-46c8-b735-6299f2063942.jpg   (Hero Photo)
â”‚   â”œâ”€â”€ 2203105e-a478-4233-a74a-60728a914501.jpg   (Gallery 1)
â”‚   â”œâ”€â”€ f7035f6f-09ef-4eea-adf7-b2facce74c14.jpg   (Gallery 2)
â”‚   â”œâ”€â”€ f3162e99-21ec-442c-bae9-89a48a77f560.jpg   (Gallery 3)
â”‚   â”œâ”€â”€ 3154940c-3a69-429b-a6e3-6750443bf052.jpg   (Gallery 4)
â”‚   â”œâ”€â”€ 9eb3476b-d6e8-4845-aeb9-32adc261e8d4.jpg   (Gallery 5)
â”‚   â”œâ”€â”€ f109479f-acb3-4fc0-9141-f8ba7d074c91.jpg   (Gallery 6)
â”‚   â””â”€â”€ theme/       # Vintage castle, floral dividers, doves, clouds, frames
â”‚       â”œâ”€â”€ asset-1.webp
â”‚       â”œâ”€â”€ asset-2.webp
â”‚       â”œâ”€â”€ ban-tiec.webp
â”‚       â”œâ”€â”€ chim.webp
â”‚       â”œâ”€â”€ cloud-1.webp
â”‚       â”œâ”€â”€ cloud-2.webp
â”‚       â”œâ”€â”€ cloud-3.webp
â”‚       â”œâ”€â”€ frame-lich.webp
â”‚       â”œâ”€â”€ hoa-ngang.webp
â”‚       â”œâ”€â”€ hoa.webp
â”‚       â””â”€â”€ home.webp
â””â”€â”€ source_data/     # Original scraped data & backups
```
