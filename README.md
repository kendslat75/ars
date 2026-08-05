# Antique Radio Salvage Website

A static, responsive website for Antique Radio Salvage, prepared for GitHub Pages.

## Pages

- `index.html` — Home
- `selling.html` — Sell Your Tubes
- `testing.html` — Tube Testing
- `about.html` — About
- `contact.html` — Contact form

## Important: activate the contact form

GitHub Pages serves static files and cannot run PHP. The contact page is prepared for Formspree.

1. Create a free account at Formspree.
2. Create a new form and set the target email to `ken@antiqueradiosalvage.com`.
3. Formspree will provide an endpoint similar to:

   `https://formspree.io/f/abcdwxyz`

4. Open `contact.html` in GitHub's editor.
5. Find:

   `https://formspree.io/f/REPLACE_WITH_FORM_ID`

6. Replace it with your actual Formspree endpoint and commit the change.

## Publish with GitHub Pages

1. Create a new public GitHub repository. A good name is `antique-radio-salvage`.
2. Upload all files and the `assets` folder from this package. Do not upload the ZIP itself.
3. Open the repository's **Settings**.
4. In the left menu, select **Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and the `/ (root)` folder.
7. Click **Save**.
8. Wait a few minutes. GitHub will display the public site address in the Pages section.

The address will normally look like:

`https://YOUR-GITHUB-USERNAME.github.io/antique-radio-salvage/`

## Connect antiqueradiosalvage.com later

In **Settings → Pages**, enter `antiqueradiosalvage.com` under **Custom domain** and save. GitHub will provide the DNS records that must be added at your domain registrar. Enable **Enforce HTTPS** after the domain is verified.

`CNAME.example` is included only as a reference. Do not rename it to `CNAME` until you are ready to connect the domain.

## Update the site

Use GitHub's web editor to change text, or upload replacement files. GitHub Pages automatically republishes after each committed change.
