Spiral Gallery - Local Version
=============================

This is a local copy of https://lab.amoura.design/projects/spiral-gallery
Powered by Three.js + React + Tailwind CSS.

HOW TO USE
----------
1. Open this folder in a terminal
2. Run: npx serve .
3. Open http://localhost:3000 in your browser

HOW TO REPLACE IMAGES
---------------------
Images are in the `images/` folder. The gallery uses 6 images defined
in `assets/index-DeRxF80t.js`. Search for "images/" in that file to find
the image array. Each entry has:

  id, imageUrl, thumbnailUrl, title, description, tags

Current images:
  0: fa8bf3ea0c91ea3bd142797f4f9ede80.jpg  - Mist (Texture)
  1: 7cf83c3a829a003229f8acfa96102b60.jpg  - Night Bloom (Backgrounds)
  2: 365b595fa89b515853dc446a86e52a96.jpg  - Viet Nam (Art & Design)
  3: b566357fbd361a289a200cd3d6f8b6ad.jpg  - Anthon Edwards (Typography)
  4: e80efee07ad721c604a467879b09a275.jpg  - Trust the universe (Cosmic)
  5: f32f3fda003d591bb4a65dd7f88b2d3b.jpg  - Starglow (Celestial)

To replace:
  1. Put your new images in the `images/` folder (use any filename)
  2. Open `assets/index-DeRxF80t.js` in a text editor
  3. Search for `images/` to find the data array
  4. Update `imageUrl` and `thumbnailUrl` to your new filenames
  5. Optionally update title, description, tags for each image
  6. Save and refresh the browser

TIPS
----
- Keep image file sizes reasonable (under 200KB each) for fast loading
- The 3D spiral effect works best with landscape-oriented images
- You can add more images by extending the array (increase id counter)
- To change the number of visible items, search for `uF=30` in the JS file
