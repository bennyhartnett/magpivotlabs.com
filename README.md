# magpivotlabs.com

`magpivotlabs.com` permanently redirects to `https://bennyhartnett.com`.

The production redirect is a Cloudflare Single Redirect configured as follows:

- Match: all incoming requests
- Target: `concat("https://bennyhartnett.com", http.request.uri.path)`
- Status: `301 Permanent Redirect`
- Query strings: preserved

`index.html` and `404.html` provide canonical, instant meta-refresh, JavaScript, and crawlable-link fallbacks for direct GitHub Pages access. The Cloudflare edge redirect is the authoritative SEO signal.
