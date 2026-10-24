# Self-Operated Business Systems — Marketing Site v0.1

**Owner:** Highest Degree Priorities (HDP)

Static, accessible SEO-oriented educational and marketing website for `selfoperatedbusinesssystems.com`. Canonical product exploration lives at `https://sob.highestdegreepriorities.com`. Source is deliberately separate from the private BOS registry, production services, secrets and customer data.

## Brand language

- **SOB** stands for **Self-Operated Business Systems** on this site.
- **Self-operating** describes bounded automation that progresses routine work under owner-defined controls.
- Use the distinction as an educational topic, not as a claim of unsupervised full-business autonomy.

## What is included

- Responsive homepage with practical workflow finder (entirely client-side, no data collection)
- Five substantial editorial pages (how it works, terminology, lead follow-up, back-office automation, service operations)
- Search-friendly semantic HTML, metadata, canonical URLs, original SVG social card, JSON-LD, sitemap, robots.txt
- GitHub Pages-ready static layout, accessible navigation, reduced-motion support
- Referral URLs to SOB using UTM campaign parameters

## Publishing / DNS

The repository already contains the user's `CNAME` file specifying `selfoperatedbusinesssystems.com`; it must remain intact. In GitHub Settings → Pages, confirm source is Deploy from branch / `main` / `/(root)` (or compatible authorized workflow). Set apex A/ALIAS/ANAME and optional `www` CNAME according to GitHub's current Pages docs. Verify DNS, custom domain and HTTPS before publishing or submitting sitemap.

**Second owned domain:** `selfoperatingbusinesssystems.com` should *not* be pointed at the same repo as a second GitHub Pages custom domain. Prefer a permanent domain-level redirect to the canonical `https://selfoperatedbusinesssystems.com/`, preserving paths where feasible. If someday it hosts a distinct site, require substantial unique user value, not a mirrored doorway.

## Post-publish checks

1. Test desktop/mobile menu, workflow finder, all editorial pages and keyboard navigation.
2. Confirm canonical URLs and HTTPS 200s at `selfoperatedbusinesssystems.com`.
3. Confirm internal links are crawlable and `sitemap.xml` contains six pages.
4. Submit sitemap to Google Search Console once stable.
5. Validate SOB destination loads before promoting high-traffic CTAs; `sob.highestdegreepriorities.com` may still be awaiting IIS/WACS deployment.
6. Connect analytics *only with appropriate consent and configuration*. UTM parameters alone do not send analytics or verify conversions.
7. Measure legitimate visitor interest, guide engagement and handoff outcomes. No fake metrics, testimonials, customer outcomes or guaranteed claims.

## Architecture

Only static public content. No tokens, bridge credentials, live internal ports, dashboards, customer data, or mutations. Any future forms should use a protected backend, consent and validated submission before being deployed.
