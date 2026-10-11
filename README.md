# Global Bridges Project website

A responsive static website starter for the Global Bridges Project.

## Files
- `index.html` — page content and sections
- `styles.css` — responsive layout, colors, typography, and animations
- `script.js` — mobile navigation, year display, and animated statistic counters
- `assets/gb-mark.svg` — temporary vector mark inspired by the project's blue/red identity

## Preview locally
Open `index.html` in a browser. The page uses Google Fonts when an internet connection is available and falls back to system fonts otherwise.

## Publish on Cloudflare Pages
This is a static HTML/CSS/JS site; it does not need a build command.

Recommended Cloudflare Pages settings:
- Framework preset: None
- Build command: leave blank
- Build output directory: `/` or `.` depending on the setup screen
- Root directory: `/`

Important: if Cloudflare has created a **Worker** project configured with `npx wrangler deploy`, that is not the right deployment flow for this static website. Create a **Pages** project and import this GitHub repository, or use the Pages workflow shown in Cloudflare.

## Before launch
1. Replace the temporary `assets/gb-mark.svg` with the official Global Bridges Project logo, if desired. Keep the filename `gb-mark.svg` or update references in the HTML.
2. Confirm all project statistics. Current counters are starter values based on the project guest list and are not live analytics.
3. Review the country count and university affiliations; affiliations do not mean formal partnerships.
4. Replace the email and WhatsApp placeholders in `index.html` with public contact details you want to publish.
5. Add real interview thumbnails, video links, and guest cards after verifying which interviews are ready to publish.
6. Test on mobile and desktop before connecting your custom domain.

## Privacy
Do not put passwords, private phone numbers, or other information you do not want public in this repository. This repository is public, so anyone can view its source.


## Updated website content
- Includes 19 published interview post links provided by the project founder.
- Includes three introductory Instagram videos.
- Adds an ambassador information section and contact links.
- University names in the marquee refer to guest affiliations and do not imply formal partnerships.
