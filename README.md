# Tom Clive website

A static single-page website for **tomclive.co.uk**, ready for GitHub Pages.

## Publishing

1. Create a public GitHub repository (e.g. `tomclive-site`).
2. Upload `index.html` and `CNAME` to the repository root.
3. In **Settings → Pages**, select **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Under Pages **Custom domain**, set `tomclive.co.uk` if not already populated from `CNAME`.
5. At the DNS provider for `tomclive.co.uk`, configure GitHub Pages apex A records:
   - `185.199.108.153`
   - `185.199.109.153`
   - `185.199.110.153`
   - `185.199.111.153`
   Check GitHub's current docs before changing DNS.
6. Once DNS propagates and certificate provisioning finishes, enable **Enforce HTTPS**.

If Squarespace currently manages DNS, edit its DNS records rather than transferring the domain. Preserve any MX/TXT records used for email. Avoid changing the domain's nameservers unnecessarily.

## Editing

Everything lives in `index.html`, including styles. To change the contact email, search for `tom@tomlikesrobots.com` (there is one instance).
