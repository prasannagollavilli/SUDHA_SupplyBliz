
# SUPPLYBLIZ Website

Multi-page static website (inspired by NextPoint Consulting layout) for SUPPLYBLIZ.

## Pages
- `index.html` — Home (hero + features)
- `about.html` — About the firm
- `services.html` — Services grid
- `contact.html` — Contact details + working form (via FormSubmit)
- `thank-you.html` — Redirect after form submission

## Contact Form
The form posts to **FormSubmit** and sends submissions to `info.hr@supplybliz.com` without server code. To customize behavior, see https://formsubmit.co/ .

## GitHub Pages
1. Push these files to a **public** repo.
2. In **Settings → Pages**, choose **Deploy from a branch**, `main`, and **/ (root)**.
3. (Optional) Add a `CNAME` file with your domain (e.g., `www.supplybliz.com`) and configure DNS as per GitHub Pages docs.

## Customization
- Update colors in `:root` in `style.css`.
- Replace text in each HTML page.
- Swap `assets/logo.png` with your brand asset.
