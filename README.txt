HANDY HEAVENS — SEO & AI CRAWLER FILES
======================================

Included:
1. robots.txt       — upload to the website document root
2. sitemap.xml      — upload to the website document root
3. llms.txt         — upload to the website document root
4. index_seo.html   — your uploaded homepage HTML with canonical/robots meta and JSON-LD Schema added

UPLOAD STEPS
1. Make a backup of your current index.html first.
2. Upload robots.txt, sitemap.xml and llms.txt into the same root folder as index.html (usually public_html).
3. Review index_seo.html, then use it to replace the live index.html only after confirming it contains the latest design and code.
4. Confirm these URLs open publicly:
   https://handyheavens.com/robots.txt
   https://handyheavens.com/sitemap.xml
   https://handyheavens.com/llms.txt
5. Submit https://handyheavens.com/sitemap.xml in Google Search Console and Bing Webmaster Tools.
6. Keep the non-www URL as canonical. Configure a server-level 301 redirect from https://www.handyheavens.com/ to https://handyheavens.com/ (and HTTP to HTTPS).

IMPORTANT NOTES
- Sitemap currently includes only the homepage because the uploaded file proves it is the main page; locality page links exist in the HTML, but their live status was not verified. Add each real, working, indexable URL to the sitemap after verifying it exists.
- Schema intentionally omits street address, business hours, price range, review rating and geo-coordinates because these details were not verified.
- Schema is included in index_seo.html; there is no need to upload a separate schema.json file.
- robots.txt Allow rules do not guarantee crawling or indexing; crawlers and search engines decide independently.
- Google-Extended is a crawler control token for some Google AI uses, not a general Google Search crawling rule.
