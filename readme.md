What schema is (plain English)

Schema markup (structured data) is a standardized way of labeling our content for search engines. It helps systems like Google/Bing (and increasingly AI-driven search experiences) understand:
	•	what a page represents (program page, article, FAQ, etc.)
	•	who/what the entities are (UAGC, programs, content topics)
	•	how pages relate (site hierarchy, lists, internal search)

It’s typically implemented as JSON-LD in the page code so it can be governed and maintained at scale.

⸻

What we have implemented on UAGC.edu today (overview by template/page type)

Here’s our current structured data footprint across the site, depending on the template:

Foundation (site/entity signals)
	•	Organization (UAGC as an entity)
	•	WebSite (site-level context)
	•	WebPage (base markup used broadly across page templates)

Navigation / hierarchy
	•	BreadcrumbList (Home → Section → Page relationships)

Content publishing (especially blog/editorial templates)
	•	Article / BlogPosting (content pages where the template is an article format)
	•	ImageObject (image/media descriptors used on content templates where applicable)
	•	VideoObject (where video is present and supported by the template)

Q&A content (when the page truly contains FAQs)
	•	FAQPage (eligible FAQ sections/pages)

Program / academic-related templates (where applicable)
	•	Course / Program-related structured data (used on program/course templates when content structure supports it)

Site experience / discovery (where applicable)
	•	ItemList / Collection-style markup (used on list/category templates where we present structured lists of items)
	•	SearchAction (used to help define internal site search behavior when enabled by the template)

Governance note: we apply schema only where the page content supports it. Schema is most effective (and safest) when it matches what a user can actually see on the page.

⸻

Why schema matters (even when it doesn’t “show”)

Schema helps with:
	•	Better search engine and AI understanding of our pages and entities
	•	Consistency at scale across templates (less ambiguity for machines)
	•	Eligibility for enhanced search displays (when guidelines + query intent support it)
	•	Cleaner site structure signals (breadcrumbs, lists, site context)

It’s not a ranking “hack,” and it doesn’t guarantee rich results — but it improves how clearly and consistently we’re interpreted.

⸻

Where expansion can create opportunity

If we invest here, the biggest opportunity is to scale and strengthen what we already have: expand consistent schema coverage across the templates/pages where it applies, improve completeness/quality so it validates cleanly and aligns tightly with on-page content, and prioritize the sections that matter most to enrollment journeys (typically program/admissions entry points). We can tie that work back to measurable impact in Search Console (coverage/validation, impressions, and CTR shifts where applicable).

⸻

How AI search affects this (why it matters more now)

AI-driven search experiences increasingly summarize, compare, and extract information rather than simply listing links. Schema supports that shift by improving:
	•	Entity clarity (UAGC + offerings are easier to interpret accurately)
	•	Extraction reliability (machines can pull the “right” info with fewer assumptions)
	•	Future-proofing (schema + well-structured content is increasingly important for machine-readable visibility)

Bottom line: schema is becoming as much about machine readability + trust as it is about rich snippets.

⸻

Keeping this efficient (so we don’t duplicate work)

To make the 15 minutes most productive, the key question is:
What outcome do you want investment to drive?
Examples: organic CTR, program/admissions visibility, qualified inquiry starts, or stronger AI-search representation.