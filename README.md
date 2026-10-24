# Fanatik99 — Portal Informasi Gaming

Static website package ready for Vercel.

## Files
- `index.html` — responsive landing page, SEO metadata, canonical URL, Open Graph metadata, WebSite structured data, FAQ, and transparent external-link disclosure.
- `robots.txt` — allows crawling and points to the sitemap.
- `sitemap.xml` — sitemap for the canonical homepage.
- `favicon.svg` — simple site icon.

## Deploy to Vercel
1. Upload these files to the root of a Git repository, or place them in a folder.
2. Import the repository in Vercel. For a static HTML site, no build command is needed; set the output directory to `.` if requested.
3. Deploy, then verify the live URLs:
   - `https://fanatik99.vercel.app/`
   - `https://fanatik99.vercel.app/robots.txt`
   - `https://fanatik99.vercel.app/sitemap.xml`

## Important before publishing
- Confirm you control `fanatik99.vercel.app`. If using a custom domain, update every canonical, sitemap, Open Graph, JSON-LD, and robots URL to the final domain.
- The external button currently opens `https://fantik99.com/akzg`, in a new tab. Change that URL in `index.html` if needed.
- Review the page's disclosure and FAQ to ensure they match the destination website and your actual relationship with it.
- This is an informational landing page. Do not describe unbuilt features as available. Add genuinely useful, original articles before expecting strong organic search performance.
- Search indexing is not guaranteed. Submit the sitemap in Google Search Console, test the live URL, and request indexing after deployment.
