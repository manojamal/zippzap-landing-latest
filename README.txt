ZippZap home page (zippzap.app) – version 2.1
============================================

Open index.html in any browser. It works offline – keep the assets folder next to it.

Files
  index.html   The whole page: layout, styles and the small script are inside this one file
  assets/      logo.svg (ZippZap logo) · logo-mark.svg (browser icon) · avatar.png (sample photo in the phone and TV)
               og-image.png (1200 x 630 picture shown when the link is shared on WhatsApp, Facebook, X)
               fonts/ (Plus Jakarta Sans)
               icons/ (15 occasion icons, WebP, transparent background, 256 x 256)

What changed in version 2.1 (30 October 2026)
  - Occasions now use the new ZippZap 3D icons: 15 occasions plus an "Any day worth marking" card
    (Birthdays, Weddings, Anniversaries, New baby, Baby & bridal showers, Graduations, Congratulations & surprises,
    Farewells, Moving abroad & bon voyage, Retirements, Work anniversaries & promotions, Get well soon,
    Thank you & ministry appreciation, Christmas & New Year, In loving memory)
  - The icons' white backgrounds were removed, edges cleaned, and each was resized to a small WebP file (about 15 KB)
  - On phones the first 8 occasions show, with a "See all 16 occasions" button for the rest
  - To change an icon: replace the file in assets/icons/ with the same name (256 x 256, transparent background)

What changed in version 2
  - Tighter first screen: on a laptop the headline, the picture and the start of "How it works" show together
  - The hero shows the finished film on a TV next to the phone collecting wishes
  - One short opening animation (wishes appear, the progress bar fills) – no endless motion;
    nothing moves for visitors who turn motion off
  - Shorter text; steps on one line; six wish types without boxes; eight occasion cards with icons
  - Pricing: Freemium (free, 1 celebration) + Starter $4.99 + Plus $9.99 + Premium $19.99, and the payment methods
  - QR code in the closing band so people on a computer can get the Android app on their phone
  - On phones and tablets a "Get the app" bar appears at the bottom after the hero
  - The header gets smaller on scroll and highlights the section being read
  - Link-preview picture and tags, plus app details for Google search (schema.org MobileApplication)

Checked at 320, 360, 390, 768, 1024, 1440 and 1920 px: no sideways scrolling, every button at least 44 px tall,
menu, download bar and section highlight all work, no errors.

To check before going live
  - Google Play link and QR code use the app id app.zippzap.celebration – confirm it is the published listing.
  - Links /affiliates, /contact, /privacy and /terms – point them at the real pages.
  - The page expects to live at https://zippzap.app/ (canonical link and link-preview picture address).
    Change those two addresses in index.html if the site lives elsewhere.
  - Plans, group sizes and payment methods – adjust in index.html if they change.
  - "iPhone coming soon" – remove when the iOS app is live.
  - Example names (Tolu, Mum, Dayo …) and the sample photo can be replaced with real ones later.
  - Reviews were not added. Send 2–3 real customer quotes to add a reviews section.

Colours, type and tone follow the ZippZap B2C Brand Guidelines v1.0.
Prepared by Manoj – RADFINKORP Solutions · 30 October 2026
