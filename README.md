# Photo_Spectrum

A responsive, static photography portfolio website. It is designed to work on desktop and mobile, can be hosted publicly on Netlify, and can also be previewed locally with PHP's built-in development server.

## Run locally with PHP

1. Install PHP if it is not already installed.
2. Open a terminal in this folder (`photo_spectrum_site`).
3. Run:

   ```bash
   php -S localhost:8000
   ```

4. Open <http://localhost:8000> in your browser.

No database, login, Composer, or PHP framework is required. The site is static HTML/CSS/JavaScript, so PHP's local server simply serves it. This also means it works on Netlify, which hosts the static site (Netlify does not execute ordinary PHP files).

## Publish with GitHub + Netlify

1. Create a new GitHub repository named `photo-spectrum`.
2. Upload the contents of this folder (the `index.html`, `styles.css`, `script.js`, `assets/`, and this README) to the repository root.
3. In Netlify, choose **Add new site → Import an existing project** and connect that GitHub repository.
4. Choose the main branch. Leave **Build command** blank and set **Publish directory** to `.`.
5. Deploy. Netlify will provide a public `https://...netlify.app` link. Anyone with the link can open the website without logging in.

## Before going live

- The Instagram link is set to `https://www.instagram.com/photo_spectrum1/` and the direct message link to `https://ig.me/m/photo_spectrum1`.
- The TikTok link is currently set to `https://www.tiktok.com/@photo_spectrum1`, based on the username visible in the supplied QR/profile image. Please verify the handle before publishing.
- The gallery uses crops from the wedding-photo screenshots you supplied. Replace the files in `assets/` with original, full-resolution photos for the best quality. Keep the filenames the same, or update the image paths in `index.html`.
- No copyrighted commercial song is bundled. If you have permission/licensing to use a track such as “Dilruba” or “Varoon Varoon”, add the audio file and a user-controlled music player; browsers generally block autoplay with sound until the visitor interacts with the page.
