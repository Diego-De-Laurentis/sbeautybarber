
s Beauty Barber — static site

Files
- index.html
- sbeauty-logo-sand.png (header/footer logo, sand color)
- sbeauty-logo.png (transparent original colors)

Deploy
1) Upload all files to a web root or static host (Netlify, Vercel, GitHub Pages, cPanel).
2) Ensure pretty URLs are served to index.html (SPA). For Netlify add a redirect:
   /_*  /index.html   200

Edit
- Change colors in :root CSS variables.
- Update address/phone in /contact view.
- Replace hero/gallery images if needed.
