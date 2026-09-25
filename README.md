# scrutineer-site

Marketing and legal site for Scrutineer, served by GitHub Pages at usescrutineer.com.

Currently a placeholder. The real site (marketing pages plus privacy policy and terms) is built separately.

## How it is served

- GitHub Pages, deploy from branch `main`, folder `/` (root).
- `CNAME` holds the custom domain. Do not delete it; Pages rewrites it from the repo settings.
- `.nojekyll` stops GitHub running Jekyll over the files, so plain HTML is served as written.
- DNS is at Cloudflare: four A and four AAAA records on the apex pointing at GitHub Pages, and `www` as a CNAME to `scrutineer-ai-car-eval.github.io`.

## Rules this site inherits from the product

- No fake urgency, scarcity or social proof, ever. That includes user counts and testimonials that do not exist.
- Nothing implies a seller is dishonest.
- The listing optimiser stays out of all marketing.
- No analytics in v1, so no cookie banner.

## Note

The placeholder carries `noindex`. Remove that meta tag when the real site goes up.
