PairPerfection — website files
================================

WHAT'S HERE
  index.html   the page content
  style.css    all the styling (colors, fonts, layout)
  script.js    small bits of interactivity (mobile menu, footer year)
  img/         put your own photos in here

TO PREVIEW
  Just double-click index.html to open it in your browser.

TO EDIT THE EASY STUFF
  Open index.html in any text editor and search for "EDIT:" — every spot
  marked that way is safe to change without breaking the layout:
    - Your real Instagram link (appears a few times)
    - The story paragraph about your shop
    - Product photos in the "This week's drop" section
    - A city / pop-up line in the footer, if you want one

TO ADD YOUR OWN PRODUCT PHOTOS
  Right now the 6 cards under "This week's drop" use colored placeholder
  swatches instead of real photos, so the site works before you add
  anything. To swap one in:
    1. Save your photo into the img/ folder, e.g. img/jeans.jpg
    2. In index.html find the card, e.g.:
         <div class="card-photo card-photo-1"></div>
    3. Change it to:
         <div class="card-photo" style="background-image:url('img/jeans.jpg')"></div>

TO PUT IT ONLINE
  Any free static host works — for example Netlify, GitHub Pages, or
  Vercel. Drag this whole folder onto Netlify's "Deploy" page and it's
  live in about a minute. If you'd like it on a custom domain like
  pairperfection.com, that's a separate step through whichever host you
  pick.

COLORS USED (if you want to tweak the palette)
  Kraft paper background : #F1E6CC
  Ink / text             : #241F18
  Rust (primary accent)  : #A8432B
  Olive (secondary)      : #5B6A44
  Mustard (tag accent)   : #D9A441
  These are set once at the top of style.css under :root, so changing a
  value there updates it everywhere.
