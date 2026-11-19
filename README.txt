HASAM PURE NATURALS WEBSITE
===========================

HOW TO OPEN
Double-click index.html. Keep all folders exactly as they are.

FOLDER LAYOUT (already linked, so nothing to connect)
  index.html        Home
  products.html     Products (filters, sizes, order basket)
  wholesale.html    Bulk and wholesale (quote form)
  learn.html        Learn and grow (wellness tips)
  gallery.html      Gallery (click a picture to enlarge)
  about.html        About us
  contact.html      Contact (form, details, map)
  css/style.css     All colours, fonts and layout
  js/config.js      YOUR SETTINGS: phone, WhatsApp, email, address, products, prices
  js/main.js        Menu, footer, order basket, forms (no need to edit)
  images/           Logo, your photos, and the illustrations

EVERY HTML PAGE LOADS, IN THIS ORDER
  css/style.css  (in the head)
  js/config.js   then   js/main.js   (at the bottom)

DO THESE FIRST (all in js/config.js)
  1. whatsapp      your number like 233271234567 (no plus, no spaces)
  2. phoneDisplay, email, address, hours
  3. PRODUCTS      change names, sizes and prices
  4. social        add Facebook, Instagram, TikTok links
  5. momo          your Mobile Money number and name
  6. mapEmbedUrl   Google Maps embed link
  7. TESTIMONIALS  add real customer reviews (hidden while empty)

USE YOUR OWN PHOTOS
Put the picture in images/, then change "img" for that product in config.js.
Set photo: true for photographs and photo: false for illustrations.

PUTTING IT ONLINE
Upload the whole folder to any web host (Netlify, GitHub Pages, cPanel hosting).
The internet is needed for the fonts (Google Fonts).
