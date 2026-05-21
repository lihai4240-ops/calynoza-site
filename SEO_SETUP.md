# Calynoza SEO and Google Search Console Setup

## Current Site Signals

- Primary URL: https://calynoza.com/
- Canonical URL: https://calynoza.com/
- Sitemap: https://calynoza.com/sitemap.xml
- Robots: https://calynoza.com/robots.txt
- GitHub Pages custom domain: calynoza.com
- HTTPS: enforced

## Google Search Console

Use a Domain property for:

```text
calynoza.com
```

This covers `https://calynoza.com`, `https://www.calynoza.com`, and HTTP variants. Google will provide a DNS TXT verification record. Add that TXT record at the DNS provider, then click Verify in Search Console.

After verification, submit this sitemap:

```text
https://calynoza.com/sitemap.xml
```

## Optional URL-Prefix Verification

If you choose a URL-prefix property instead, use:

```text
https://calynoza.com/
```

Then send the Google verification meta tag or HTML verification file name/content, and add it to this repository before the next push.
