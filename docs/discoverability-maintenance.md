# Academic discoverability maintenance

Published changes preserve the English and Chinese homepages independently.
No original CSS, JavaScript, navigation, PDFs, or publisher/repository destinations are changed.
Only one visible citation is corrected: Otic drug delivery systems, 44(9), 1395–1408.
Verified against https://api.crossref.org/works/10.1080/03639045.2018.1464022.

## Rollback baseline

Branch: backup/pre-discoverability-2026-10-17
Commit: 7d1c863aa3f7d7c86d4e2bd2678399b80748a539
Use a normal revert if necessary; do not force-reset a branch with subsequent user changes.

## What is intentionally not done

- No promises of search rankings, AI citations, or Scholar inclusion.
- Short original research summaries are not labeled as published abstracts.
  Google Scholar may require full author-written abstracts or accessible full text.
- No publisher PDF URLs are guessed. The existing Academic Perspectives PDF is
  linked from its two new records; its file and access policy are unchanged.
- No publication-title, author, journal, or DOI rewrites.
- No training crawler is newly blocked. robots.txt preserves the previous open policy.
- No experimental llms.txt or unsupported schema types.
- No changes to Google Scholar, ORCID, OpenAlex or Semantic Scholar accounts.
- No Search Console / Bing submissions without the account owner's session.
- Homepage appearance is unchanged. New publication records are exposed through
  sitemap.xml and homepage ItemList JSON-LD; existing title links still open the
  same DOI or ScholarWorks record. A visible details link can be added later
  if a small user-interface change is approved.

## Owner actions

1. Submit https://mingshuangli.github.io/sitemap.xml in Google Search Console
   and Bing Webmaster Tools; request inspection of key new publication pages.
2. Claim and correct OpenAlex author identities:
   - https://openalex.org/A5140891879 — correct ORCID, recent JASA EL papers.
   - https://openalex.org/A5035089546 — conflated profile, wrong ORCID
     0000-0002-4651-212X; do not merge unrelated works into your own profile.
   - https://openalex.org/A5124305333 — editorial identity to review.
   Your correct ORCID: https://orcid.org/0000-0001-6095-1228.
   Verify works individually before asking for splits/merges.
   Help: https://help.openalex.org/ (author profile correction).
3. Correct Google Scholar interest “Blingualism” to “Bilingualism”.
4. Review the Semantic Scholar author profile manually. Rate limiting in the
   audit is not evidence that a paper is missing.
5. Correct the 2018 volume/pages in the source CV next time it is exported;
   this release deliberately does not alter the PDF.

## When adding a paper

Keep exact published bibliographic text; verify DOI, authors, dates and journal
against the publisher or Crossref. Do not invent DOIs for repository-only work.
Add one independent English and Chinese record, reciprocal hreflang, one
canonical per page, Highwire citation tags, ScholarlyArticle JSON-LD, visible
citation and original research summary. Keep one shared article @id across
language wrappers. Update both homepage ItemLists, record directories, related
links, and sitemap. Never add a set of citation_title tags for multiple papers
to a homepage. Confirm all public full-text links are authorized and accessible.

Validate JSON-LD, sitemap XML, HTTP status codes and exact body/CSS preservation.
Check desktop and mobile whenever a change touches visual markup or styles.
