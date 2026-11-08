CAFE WEBSITE — HOW TO USE
=========================

VIEW IT
  Double-click index.html. It opens in your browser (Chrome, Edge, etc.).
  Internet is only needed for the fonts.

WHAT TO EDIT (open index.html in Notepad or VS Code)
  1. WhatsApp number
     Near the bottom, find:  const WHATSAPP_NUMBER = "60123456789";
     Replace with your number: country code + number, digits only (no + or spaces).

  2. Drink photos
     Put your photos in the "images" folder (next to index.html).
     In the DRINKS list near the bottom, fill in each photo, e.g.
       photo: "images/iced-latte.jpg"
     You can add, remove or rename drinks in that list too.
     cat must be one of: coffee, sparkling, matcha, choc

  3. Text placeholders
     Search for anything in [square brackets] and replace it:
       [Your Cafe], [Your address], [Opening hours],
       [Add your coffee list & prices], etc.

  4. Hero video (full-screen background at the top)
     Save your clip as videos/hero.mp4 (MP4, 10-20 sec, under 10 MB).
     No video yet? An animated matcha-green background shows instead.

  5. Menu panel photos
     Save images/coffee.jpg, sparkling.jpg, matcha.jpg, chocolate.jpg.
     They appear on the 4 menu panels automatically.

  6. City under the logo
     Near the bottom, change:  const CITY = "[Your City]";

FOLDER
  index.html           the website (animated style)
  index-classic.html   the first, simpler version (backup)
  images/              drink photos
  videos/              hero.mp4 goes here
  README.txt           this file

PUTTING IT ONLINE (optional)
  Drag this whole folder into Netlify Drop (app.netlify.com/drop)
  or upload it to GitHub Pages to get a free public link.
