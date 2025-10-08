Vicente & Jenny Wedding Website - Standalone Version
====================================================

This is a pure HTML/CSS/JavaScript version of the wedding website that can be used on any web hosting service.

FOLDER STRUCTURE:
----------------
standalone/
├── index.html          (Main HTML file)
├── css/
│   └── style.css      (All styles)
├── js/
│   └── script.js      (All JavaScript functionality)
├── images/
│   ├── hero-background.jpg
│   ├── gallery-1.jpg
│   ├── gallery-2.jpg
│   └── gallery-3.jpg
├── music/
│   └── enchanted.mp3  (Add your music file here)
└── README.txt         (This file)


SETUP INSTRUCTIONS:
-------------------

1. COPY IMAGE FILES:
   - Copy the images from ../src/assets/ to the images/ folder:
     * hero-background.jpg
     * gallery-1.jpg
     * gallery-2.jpg
     * gallery-3.jpg

2. ADD MUSIC FILE:
   - Create a "music" folder inside the standalone folder
   - Add your "enchanted.mp3" file to the music folder
   - Or use any other .mp3 file and update the filename in index.html (line 227)

3. ADD QR CODE (Optional):
   - Replace the QR code placeholder in the Love Gift section
   - Add your QR code image to the images folder
   - Update the HTML in index.html (around line 174)

4. UPLOAD TO WEB HOSTING:
   - Upload all files maintaining the folder structure
   - Most hosting services: just upload to public_html or www folder
   - The website will work immediately


CUSTOMIZATION:
--------------

To customize the website:

1. CHANGE TEXT:
   - Open index.html in any text editor
   - Find and replace the text you want to change

2. CHANGE COLORS:
   - Open css/style.css
   - Modify the color variables at the top (lines 11-18)

3. CHANGE FONTS:
   - Update the Google Fonts link in index.html (line 13)
   - Update the font-family in css/style.css

4. CHANGE IMAGES:
   - Replace the images in the images/ folder
   - Keep the same filenames or update the references in index.html


BROWSER COMPATIBILITY:
---------------------
This website works on all modern browsers:
- Chrome, Firefox, Safari, Edge
- Mobile browsers (iOS Safari, Chrome Mobile)
- Fully responsive for all screen sizes


HOSTING RECOMMENDATIONS:
-----------------------
This website can be hosted on:
- GitHub Pages (free)
- Netlify (free)
- Vercel (free)
- Any traditional web hosting service
- Your own server


SUPPORT:
--------
For questions or issues, contact: Vicente Badua S.


Enjoy your wedding website! 💙
