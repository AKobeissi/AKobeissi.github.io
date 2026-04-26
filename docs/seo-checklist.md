# Google indexing checklist

This repository is configured for crawlability and indexing, but Google indexing also requires Search Console setup.

## 1) Verify ownership in Google Search Console

1. Open Google Search Console and add the property: `https://akobeissi.github.io/`
2. Choose **HTML tag** verification.
3. Copy the `google-site-verification` token.
4. Paste it into `_config.yml`:
   - `google_site_verification: <your-token>`
   - `enable_google_verification: true`
5. Commit and deploy.

## 2) Submit sitemap

In Search Console, submit:

- `https://akobeissi.github.io/sitemap.xml`

## 3) Request indexing

Use URL Inspection and request indexing for:

- `https://akobeissi.github.io/`
- `https://akobeissi.github.io/publications/`
- `https://akobeissi.github.io/projects/`
- `https://akobeissi.github.io/cv/`

## 4) Keep pages indexable

- Avoid `noindex` directives.
- Keep canonical URLs on your own domain.
- Add internal links to key pages from the home page.
