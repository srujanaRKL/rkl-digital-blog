# RKL Digital Blog — Writer Spec (read before writing any post)

You are producing **standalone, self-contained HTML blog files** for RKL Digital, an AI-first
digital marketing agency. Goal: every post should be **citeable by AI engines** (ChatGPT,
Perplexity, Google AI Overviews) AND **convert small-business readers into Free Strategy Calls**.

## Gold-standard template
**Read `what-is-ai-seo-small-business.html` in this folder and copy its exact structure, CSS link,
header, footer, schema blocks, CTA blocks, and class names.** Only change the content. Do not
restyle. The stylesheet is `assets/rkl-blog.css` (link it exactly as the template does:
`<link rel="stylesheet" href="assets/rkl-blog.css">`).

## Brand facts (use verbatim — never invent contact info)
- Name: **RKL Digital** — "Your AI-First Marketing Agency"
- Site: https://www.rkldigital.com  · Blog hub link: `index.html`
- Phone: **(262) 402-3322** (tel:+12624023322) and (469) 426-5631 (tel:+14694265631)
- Email: **Info@rkldigital.com**
- Location: **Brookfield, WI** · Serving: **US startups, SMBs & growing businesses**
- Trust line: **2,000+ clients served since 2020**
- Primary CTA everywhere: **"Book a Free Strategy Call"** → https://www.rkldigital.com/contact
- Service page links to use in nav/footer/body where relevant:
  /ai-seo-services · /geo-optimization · /seo-services · /web-design ·
  /marketing-automation · /saas-marketing · /voice-search-optimization (all under https://www.rkldigital.com)

## Required structure for EVERY post (match the template)
1. `<head>`: unique `<title>` (≤60 chars, end with " | RKL Digital"), meta description (≤155 chars),
   meta keywords, author, robots, canonical (`https://www.rkldigital.com/blog/SLUG`), OG tags,
   `<link>` to assets/rkl-blog.css.
2. **Two JSON-LD blocks**: `Article` (datePublished/dateModified 2026-06-17) and `FAQPage` whose
   questions EXACTLY match the on-page FAQ section.
3. Sticky topbar nav + breadcrumb (copy from template).
4. `<article>`: category `.rkl-tag`, `<h1>`, `.rkl-meta` byline ("By the RKL Digital Team · Last
   updated June 17, 2026 · N min read").
5. **`.rkl-answer` Quick Answer box** — bold, 2-4 sentences that directly answer the title question
   (this is what AI lifts; make it self-contained and quotable).
6. Intro (2 short paras), a **`.rkl-stats`** box with 3 real-ish stats, **H2/H3 sections**, at least
   **one `.rkl-table-wrap` comparison table**, one `.rkl-callout` insight, bulleted/numbered lists.
7. **One mid-article `.rkl-cta`** and **one closing `.rkl-cta`** (copy block from template, tweak headline).
8. **`.rkl-faq`** section: 4–6 `<details>` Q&As (mirror the FAQPage schema exactly).
9. **`.rkl-related`** block: 4–5 internal links to sibling posts (see linking rules).
10. Footer (copy from template verbatim).

## Internal linking rules (critical for SEO + AI authority)
- Link naturally **3–6 times inside the body** to OTHER posts in the slug list below, using
  descriptive anchor text. Prefer same-cluster siblings + 1-2 cross-cluster links.
- Every post links at least once to a relevant **service page** (e.g. AI-SEO posts → /ai-seo-services).
- `.rkl-related` lists 4–5 sibling slugs.
- Use the exact filenames from the slug list (e.g. `local-seo-near-me.html`). Never link to a slug
  that isn't on the list.

## Tone & quality
- Plain, confident, helpful. Write for a busy small-business owner in the US.
- Be genuinely useful and specific (numbers, steps, examples) — that's what gets cited.
- 1,200–1,800 words. No fluff, no fake client names, no invented awards.
- American spelling. Avoid hype like "revolutionary"; show value through specifics.

## Full slug list (all 40 — link only to these)
1. what-is-ai-seo-small-business.html  *(done — the template)*
2. geo-vs-seo-small-business.html
3. how-to-get-recommended-by-chatgpt.html
4. how-to-rank-on-perplexity.html
5. how-to-appear-in-google-ai-overviews.html
6. generative-engine-optimization-playbook.html
7. answer-engine-optimization-aeo.html
8. how-ai-search-is-changing-marketing.html
9. best-ai-seo-agency-small-business.html
10. schema-markup-for-ai-search.html
11. small-business-seo-guide.html
12. local-seo-near-me.html
13. keyword-research-small-business.html
14. on-page-seo-checklist.html
15. technical-seo-basics.html
16. how-long-does-seo-take.html
17. google-business-profile-optimization.html
18. why-website-not-getting-traffic.html
19. seo-vs-ppc.html
20. blog-content-that-ranks.html
21. small-business-website-cost.html
22. signs-website-needs-redesign.html
23. conversion-rate-optimization.html
24. landing-page-best-practices.html
25. wordpress-vs-webflow-vs-shopify.html
26. web-design-trends-2026.html
27. marketing-automation-starter-guide.html
28. email-marketing-small-business.html
29. sms-text-marketing-small-business.html
30. lead-nurturing-funnel.html
31. crm-for-small-business.html
32. digital-marketing-strategy-guide.html
33. how-much-to-spend-on-marketing.html
34. in-house-vs-agency-vs-freelancer.html
35. signs-you-need-marketing-agency.html
36. how-to-measure-marketing-roi.html
37. digital-marketing-small-budget.html
38. social-media-marketing-small-business.html
39. content-marketing-playbook.html
40. saas-marketing-first-100-customers.html
