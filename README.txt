MARINA & PETER — GITHUB PAGES VERSION
=====================================

This folder is ready for GitHub Pages.

FILES
- index.html
- marina-peter-1.jpeg
- marina-peter-2.jpeg
- wedding-song.mp3
- .nojekyll

PUBLISHING
1. Create a PUBLIC GitHub repository, e.g. marina-and-peter-wedding.
2. Upload ALL files in this folder to the repository root.
3. Open repository Settings > Pages.
4. Under Build and deployment:
   Source: Deploy from a branch
   Branch: main
   Folder: /(root)
5. Save. GitHub will publish the site.

RSVP IMPORTANT
GitHub Pages is static hosting, so it does not store form submissions itself.
This package is prepared to use FormSubmit (free) for RSVP email delivery.

To activate RSVP:
1. Open index.html.
2. Find:
   https://formsubmit.co/REPLACE_WITH_EMAIL
3. Replace REPLACE_WITH_EMAIL with the email address that should receive RSVPs.
4. Commit the updated index.html.
5. Submit one test RSVP.
6. FormSubmit will send a confirmation email to that address.
7. Confirm it once; future RSVPs will be delivered there.

The current package safely blocks the RSVP button until the email is configured.
