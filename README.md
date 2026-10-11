# Portfolio — Uzair Ali (Freelance SEO Specialist in Pakistan)

Live site: https://uzairali-18.github.io/Portfolio/

## AI Receptionist — Live Voice Call

A **call button blended in** connects visitors to Uzair's Retell AI receptionist for
an instant voice conversation.

**Entry points:** floating call button (bottom-right) · hero CTA · Contact section card ·
FAQ answer button. Closing the window (✕ / Escape / click-outside) ends the call and
releases the microphone. "Open in a new tab" fallback included.

## SEO Implementation (Oct 2026)

Keyword research basis: "seo specialist", "freelance seo specialist", "seo specialist
pakistan", "seo expert in lahore", "uzair ali seo", long-tail hiring/pricing queries
(PAA), and competitor analysis (uzairalii.com, junaidtariq.com, saadraza.com, raxseo.pk).

### On-page SEO
- Keyword-optimized `<title>` (63 chars) & meta description (150 chars) — "Uzair Ali",
  "SEO Specialist in Pakistan", "On-Page SEO", "Keyword Research"
- Keyword-rich H1/H2/H3 hierarchy (single H1)
- LSI/long-tail coverage: keyword research, on-page SEO, content optimization, local SEO,
  technical SEO, small business SEO, freelance SEO, SEO audit, Lahore/Pakistan geo terms
- SEO-optimized image: descriptive alt with name + keywords, width/height (CLS), fetchpriority
- Keyword-rich internal anchor links (hero → #how-i-help/#skills, footer → sections)
- New **FAQ section** targeting People-Also-Ask queries (cost, timeline, tools, guarantees)

### Technical SEO
- Valid semantic HTML5 — fixed 2 structural bugs (stray `</main>`, mismatched tags)
- Single `<main>` landmark, proper heading hierarchy, no duplicate IDs
- Canonical URL, robots meta with `max-image-preview:large` / `max-snippet:-1`
- Geo meta tags (Lahore, Punjab, PK) for local SEO
- Open Graph (profile) + Twitter Card `summary_large_image`
- Static JSON-LD `@graph`: **Person + WebSite + ProfessionalService + FAQPage**
  (replaces JS-injected schema for reliable crawling; FAQ schema matches visible text)
- XML sitemap with image sitemap entry + fresh `lastmod`; valid `robots.txt`
- Performance: `preconnect` to call-widget origin, async image decoding

### Deliberately avoided (black-hat penalty risk)
Cloaking, hidden text/links, keyword stuffing, fake review schema, link schemes,
doorway pages, PBNs. These cause Google penalties — sustainable rankings come from
white-hat + clean grey-area tactics only (exact-match internal anchors, PAA targeting,
keyword-rich alt/anchors are all within guidelines).

## Files

| File | Purpose |
|------|---------|
| `index.html` | Portfolio page + AI call widget + full SEO |
| `Profile.jpg` | Hero profile photo (OG/Twitter image) |
| `favicon.png` | Favicon / touch icon |
| `robots.txt` | Crawl rules + sitemap pointer |
| `sitemap.xml` | XML sitemap + image sitemap |
| `googlebb0ab1f2bdb5f579.html` | Google Search Console verification |

## Deploy

Push all files to the `main` branch of `uzairali-18/Portfolio` — GitHub Pages serves the
site over HTTPS (required for the microphone). Then submit `sitemap.xml` in Google Search
Console and request indexing for the updated homepage.
