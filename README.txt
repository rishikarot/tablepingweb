TABLEPING WEBSITE — HOSTING GUIDE

1. Extract this ZIP.
2. Upload index.html, style.css, app.js and host-welcome.png together to your website's public folder (often public_html).
3. Open your domain to view the website.

The index.html file must sit directly inside the hosting folder, not inside an extra ZIP folder. The files also work in a subfolder, with relative asset paths.

No build step, Node.js server, database or installation is required. You can preview by opening index.html in your browser.

FILES
index.html — Page content and FAQ structured data.
style.css — Responsive layout, colours and typography.
app.js — Interactive seating demo, table filters and reset action.
host-welcome.png — Custom hospitality illustration.

NOTES
This is a marketing website with a sample-data seating demo, not the production TablePing application. CTA buttons open the demo; replace them with your app or booking link when ready. Fonts load from Google Fonts when online, with system-font fallbacks. Static hosting does not carry over the private access restrictions of the original Sites page; access is controlled by your hosting provider.
