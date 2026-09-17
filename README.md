# Cleaning Code LLC — Website

A 6-page static site: Home, Services, Pricing, Service Areas, About, Contact.

## Deploying to GitHub Pages (free)

1. Create a new repository on GitHub (e.g. `cleaning-code-website`).
2. Upload all files in this folder to the repo, keeping the same structure:
   ```
   index.html
   about.html
   services.html
   pricing.html
   service-areas.html
   contact.html
   css/style.css
   images/
   ```
3. In the repo, go to **Settings → Pages**.
4. Under "Source," choose **Deploy from a branch**, select the **main** branch and **/ (root)** folder, then click **Save**.
5. GitHub will give you a live URL, usually `https://<your-username>.github.io/<repo-name>/`, within a minute or two.

## Adding a custom domain (optional, still free hosting)

1. Buy a domain from any registrar (Namecheap, Google Domains, etc. — typically $10-15/year).
2. In the registrar's DNS settings, add a CNAME record pointing to `<your-username>.github.io`.
3. In your repo's **Settings → Pages**, enter the custom domain and save.

## Notes

- The contact form currently has no backend — form submissions don't go anywhere yet. To make it functional for free, consider a service like Formspree or Web3Forms (both have free tiers that work with static sites).
- Replace the abstract green "sweep" visuals with real photos once available — swap the `.sweep-art` divs for `<img>` tags pointing to files in the `images/` folder.
- Fonts (Fraunces + Inter) load from Google Fonts via the `<link>` tags in each page's `<head>`.
