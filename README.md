# Takelitos Website

A one-page website for Takelitos, 5217 Santa Ana Dr, Orlando, FL 32837.
No build tools, no frameworks, no third-party scripts. Just plain HTML.

## What's in this folder

```
index.html        The whole website (styles and script included)
images/
  logo.png        Logo (also used as the browser tab icon)
  pastelitos.jpg  Gallery photo
  rolls-de-jamon.jpg  Gallery photo
  tequenos.jpg    Gallery photo
README.md         This file
```

## Put it online

Upload the **contents** of this folder so that `index.html` sits in the site's main (root) folder and `images/` sits beside it. The file must be named exactly `index.html`, all lowercase.

- **Netlify Drop (easiest):** go to app.netlify.com/drop and drag this whole folder onto the page.
- **GitHub Pages:** put the files in a repository, then turn on Pages in Settings.
- **Traditional hosting (GoDaddy, Bluehost, cPanel):** open File Manager, go to `public_html`, and upload everything there.
- **Website builders (Wix, Squarespace, WordPress):** these usually don't accept a full HTML page. Use a plain-HTML host above, and point your domain at it.

Test by opening `index.html` in a browser first. Double-clicking it works.

## Edit common things

Open `index.html` in any text editor and search (Ctrl/Cmd + F) for:

| To change | Search for |
|---|---|
| Phone number | `433-2174` (appears in several places; also `+14074332174`) |
| Hours | `class="hours"` (also update the open/closed logic in the `<script>` near the bottom) |
| Menu prices | `class="price"` and `class="each"` |
| Reviews | `id="love"` |
| Address | `Santa Ana` |
| Instagram | `takelitos.llc` |
| Photos | replace the files in `images/`, keeping the same names |
| Policies | `id="legal"` |

When replacing photos, keep them under about 200 KB each so the page loads quickly on phones. Update the `alt="..."` text to describe the new photo.

## Check before launch

The policies are drafts, not legal advice. Please confirm or change:

1. **Refund terms:** same-day remake or refund; 24 hours for large or frozen orders.
2. **Sales tax:** the site says tax is added at pickup. Change this if menu prices already include tax.
3. **Data requests:** promised response within 30 days via phone, in person, or Instagram. Add an email if you have one.
4. **Legal name:** policies say "Takelitos." Add the full legal business name if needed.
5. **Allergens:** the list (wheat, milk, eggs, pork) should match your real recipes.
6. **Prices and flavors:** copied from an older Instagram menu. Verify they're current.
7. **Policy date:** "Last updated" is October 9, 2026 in the Policies section. Update it when you edit the policies.
8. Have a local attorney review the policy text.

## Privacy and tracking

The site sets no cookies, loads no third-party fonts or scripts, and has no forms. The cookie banner only stores the visitor's answer in their own browser. If you add analytics later, run it only after a visitor presses Accept, and update the Privacy and Cookie policies.

## Troubleshooting

- **Blank page or raw code showing:** the file isn't named `index.html`, or it's saved as `.txt`.
- **Logo and photos missing:** the `images` folder wasn't uploaded, or it isn't beside `index.html`.
- **No styling:** the page was pasted into a builder that strips `<style>` tags. Use a plain-HTML host.
