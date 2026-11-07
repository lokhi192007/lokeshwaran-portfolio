# Lokeshwaran A. | Portfolio

An animated, single-page portfolio for **Lokeshwaran A.**, a B.E. Electronics and Communication Engineering student (SKCET, Coimbatore, batch 2025-2029) building edge AI, embedded systems and software.

**Live site:** https://lokhi192007.github.io/

> The link works once you finish the steps below. It uses the repository name `lokhi192007.github.io`, which gives the shortest address. If you pick a different repository name, see [Choosing the repository name](#choosing-the-repository-name).

**GitHub:** https://github.com/lokhi192007
**LinkedIn:** https://www.linkedin.com/in/lokeshwaran-a-a02052380

---

## What is on the page

- Hero with a live oscilloscope strip showing an amplitude-modulated wave
- **PEC Hacks 4.0, Top 50 finalist** banner
- Projects: Sensorax (ISRO PS 26172 edge voice activator), EnerSense AI, EV fast charging paper, AI Fitness Advisor, RescueLink
- Interactive **AM Lab** with sliders for modulation index and frequencies
- Journey timeline, education, hackathon results and certificates
- Contact tiles with copy buttons for email and phone
- Dark neon design, scroll animations, tilt cards, mobile menu, reduced-motion support

It is plain HTML, CSS and JavaScript in one file. There is nothing to install or build.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole portfolio |
| `README.md` | This guide |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

---

## Publish on GitHub Pages (website steps)

1. Sign in at https://github.com and click **New** (or go to https://github.com/new).
2. Set **Repository name** to `lokhi192007.github.io`.
3. Choose **Public**. Leave "Add a README" unticked, then click **Create repository**.
4. On the new repository page, click **uploading an existing file**.
5. Drag in `index.html`, `README.md` and `.nojekyll` from this folder.
   - `.nojekyll` is a hidden file. If you cannot see it on your computer, skip it; the site works without it.
6. Scroll down, write a message such as `Add portfolio`, and click **Commit changes**.
7. Open the repository **Settings**, then **Pages** in the left menu.
8. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
9. Set **Branch** to `main` and the folder to `/ (root)`, then click **Save**.
10. Wait one to two minutes and refresh the Pages screen. A banner says "Your site is live at" with your link.
11. Open **https://lokhi192007.github.io/** to check it.

## Publish with Git (command line)

Create the empty `lokhi192007.github.io` repository on GitHub first (steps 1 to 3 above), then run this inside the folder that holds `index.html`:

```bash
git init
git add .
git commit -m "Add portfolio"
git branch -M main
git remote add origin https://github.com/lokhi192007/lokhi192007.github.io.git
git push -u origin main
```

Then do steps 7 to 11 above to switch on Pages.

## Choosing the repository name

| Repository name | Website address |
| --- | --- |
| `lokhi192007.github.io` (recommended) | https://lokhi192007.github.io/ |
| `lokeshwaran-portfolio` | https://lokhi192007.github.io/lokeshwaran-portfolio/ |

The website address always follows the pattern `https://<username>.github.io/<repository-name>/`. The special name `<username>.github.io` removes the repository part.

---

## Update the site later

- **Edit on GitHub:** open `index.html`, click the pencil icon, change the text, and click **Commit changes**. The site refreshes in about a minute.
- **Edit on your computer:** change the file, then run `git add . && git commit -m "Update" && git push`.

Things to check before sharing the link:

- [ ] Your phone number and email are correct, and you are happy for them to be public. Search for `data-copy` in `index.html` to change or remove them.
- [ ] Hackathon and certificate wording is up to date.
- [ ] Add project repository or demo links when they are ready.
- [ ] Optional: add a PDF résumé to the repository and link it from the hero buttons.

## Show the link on your profiles

1. **GitHub repository:** on the repository page, click the gear next to **About**, tick **Use your GitHub Pages website**, and save.
2. **GitHub profile:** Settings, Profile, and add the link in the **Website** field.
3. **LinkedIn:** Edit profile, **Contact info**, **Website**, and paste the link. You can also add it under **Featured**.

## Customise the colours

All colours sit at the top of the `<style>` block in `index.html`:

```css
:root{ --bg:#080b14; --cyan:#56e8ff; --violet:#9a7bff; --lime:#c4ff72; --pink:#ff76b9; --orange:#ffb86b; }
```

Change a value and save to restyle the whole page.

## Troubleshooting

- **404 on the site:** confirm the file is named exactly `index.html` and sits in the repository root, and that Pages is set to the `main` branch and `/ (root)`.
- **Old version still showing:** wait a minute, then hard refresh (Ctrl+Shift+R, or Cmd+Shift+R on Mac).
- **Fonts look different:** the page loads Manrope and DM Mono from Google Fonts. Offline, it falls back to system fonts.

---

© Lokeshwaran A.
