GREER FIRESTONE — FINAL STATIC WEBSITE
======================================

This folder is ready to upload to GitHub Pages.

FILES
-----
index.html
styles.css
script.js

images/
  greer-firestone.jpg
  edsel.jpg
  alexei-rasputin.jpg
  judy-garland.jpg
  gershwin.jpg
  capone.jpg

FINAL ITERATION CHANGES
-----------------------
- Refined the "Selected writing" section with a cleaner cool editorial background.
- Reduced some oversized vertical spacing in the section intro.
- Added "Buy the book" buttons to both books.
- Purchase buttons currently point to Amazon searches by ISBN:
    My Life as an Edsel: 9798989664528
    Alexei and the Mad Monk Rasputin — Second Edition: 9798989664535
  These are easy to replace later with direct product links.
- Added keyboard focus states.
- Added scroll-padding so sticky navigation does not cover anchored sections.
- Improved long contact-link wrapping on small screens.
- Slightly tightened project section height/padding for better desktop proportions.

IMAGE NOTES
-----------
All required images are included.

- greer-firestone.jpg
  Greer Firestone headshot.

- edsel.jpg
  Front-cover crop from the supplied full wraparound cover.

- alexei-rasputin.jpg
  Front-cover crop from the supplied full wraparound cover.

- judy-garland.jpg
  Supplied Judy Garland musical poster.

- gershwin.jpg
  Supplied Gershwin artwork.

- capone.jpg
  Supplied Al Capone artwork.

HOW TO PREVIEW LOCALLY
----------------------
Recommended:

    python3 -m http.server 8000

Then visit:

    http://localhost:8000

Or use VS Code Live Server.

GITHUB PAGES
------------
Upload ALL of these to the repository root:

    index.html
    styles.css
    script.js
    images/

No build step is required.

PURCHASE LINKS
--------------
To change a purchase link later, open index.html and search for:

    amazon.com/s?k=9798989664528
    amazon.com/s?k=9798989664535

Replace the href value with any retailer/product page you prefer.


FINAL V2 NOTES
--------------
- Selected writing intro changed to a deep blue/ink editorial section for clearer separation.
- Hero portrait increased to 148px on desktop and 108px on small screens.
- Buy buttons now use direct Amazon product URLs instead of ISBN search pages.
