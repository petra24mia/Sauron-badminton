# Sauron-badminton

Static website for T.S.B.V. Sauron.

## Project structure

- `index.html` — main site file and homepage for static hosting
- `assets/` — add site images here, for example `hero.jpg` and `about.jpg`
- `netlify.toml` — Netlify deployment settings

## Edit locally in Cursor

1. Open this repository folder in Cursor.
2. Edit `index.html`.
3. Put any photos you want to use in `assets/`.
4. Save your changes.
5. Preview by opening `index.html` in your browser and refreshing after each save.

## Publish the site

### 1. Put the website on GitHub

1. Create a GitHub repository for the live site.
2. Upload or push these files to that repository:
   - `index.html`
   - `assets/...`
   - `netlify.toml`
3. Confirm the files are visible on GitHub.

### 2. Deploy on Netlify

1. Create a Netlify account.
2. Choose **Add new site** → **Import an existing project**.
3. Connect GitHub and pick your repository.
4. Netlify should detect the site as a static site.
5. Deploy the site.
6. Netlify will give you a temporary `*.netlify.app` URL.

### 3. Test the temporary Netlify URL

Check that:

- the homepage loads
- the About image loads, and the hero background still looks correct before or after you add `assets/hero.jpg`
- the buttons and links work
- the site looks correct on desktop and mobile

If something is wrong, edit locally, push the change to GitHub, and let Netlify redeploy.

### 4. Buy and connect your custom domain

1. Buy the domain you want from Namecheap.
2. In Netlify, open **Domain management** for the site.
3. Add your custom domain.
4. Netlify will show the DNS records that Namecheap needs.
5. In Namecheap, open the domain's DNS settings and add those records.
6. Wait for DNS propagation.
7. In Netlify, set your preferred primary domain (`yourdomain.com` or `www.yourdomain.com`).
8. Wait for Netlify to finish enabling HTTPS.

### 5. Make the site discoverable on Google

1. Open Google Search Console.
2. Add your live domain as a property.
3. Verify domain ownership.
4. Request indexing for the homepage with URL Inspection.
5. If you later add `robots.txt` and `sitemap.xml`, submit the sitemap there as well.

Google indexing is not instant, but this helps the site become searchable.

## Common content updates

- Update the hero description in `index.html` inside `<p class="lede">`.
- Update the About text in the three paragraphs under the `#about` section.
- Update the hero background by changing the `.hero-photo` CSS block.
- Update the About image by changing the `<img src="...">` inside the About section.
- Replace the `JOIN_FORM_URL` value at the bottom of `index.html` to enable the join button.
- Replace the placeholder email and Instagram text in the contact section.
