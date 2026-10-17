# Semantic website content handoff

This is a content specification for a separate website task, not authorization to edit or publish a website.

Include the article key, EN/ZH candidate versions and file hashes where applicable; titles; semantic descriptions; body structure; useful direct-answer passages; real FAQ/tables/ordered steps when present; sources; link intent and disclosure limits. Recommend concise semantic slugs only if requested. Locale routes, author fields, canonical values and translation mapping must follow actual supplied site conventions; absent conventions remain `TO BE RESOLVED`, not guessed.

Do not hardcode production domains, author identity, country-specific locales, framework fields or schema helpers. Missing authors, publication dates, slugs and canonical fields remain TO BE RESOLVED, never invented to complete the handoff. Preserve meaningful lists and tables in the intended representation. Website infrastructure owns routing, components, metadata rendering and structured data. Schema must correspond to actual visible content; do not duplicate website-owned JSON-LD in article text or fabricate dates, entities or relationships.

For referenced content, distinguish confirmed accessible destinations from unpublished, unavailable or unknown ones. Recommend plain text or omission rather than a visitor-facing dead link. Never change another item's publication state to make a link work. Existing published URL migrations require a separate decision.

Report the scope of checks honestly:

- `EDITORIAL / BILINGUAL REVIEW`: actual pass, gap or blocker.
- `SEO CONTENT INPUTS`: titles, descriptions and source/link inputs reviewed, with limitations.
- `GEO / RETRIEVAL CONTENT STRUCTURE`: human-useful clarity and structure, not a promise of AI citations.
- `WEBSITE / STRUCTURED DATA / DRAFT SAFETY`: `NOT CHECKED` unless an actual separate implementation was inspected.
- `PUBLICATION`: outside this skill's scope.

If preparing a preview specification, recommend unpublished/unindexable drafts under the site's own conventions. Do not claim build, rendered layout, sitemap, robots, canonical, locale or deployment checks passed from editorial files alone. Technical readiness is not evidence of ranking, traffic, indexation or business results.
