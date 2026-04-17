---
name: geo-platform-optimizer
description: Platform-specific AI search optimization — audit and optimize for the top 10 AI platforms: Google AI Overviews, ChatGPT, Perplexity, Gemini, Bing Copilot, Claude, Meta AI, Grok (xAI), DeepSeek, and Apple Intelligence
version: 2.0.0
author: geo-seo-claude
tags: [geo, ai-search, platform-optimization, chatgpt, perplexity, gemini, aio, claude, meta-ai, grok, deepseek, apple-intelligence]
allowed-tools: Read, Grep, Glob, Bash, WebFetch, Write
---

# GEO Platform Optimizer

## Core Insight

Only **11% of domains** are cited by BOTH ChatGPT and Google AI Overviews for the same query. Each AI search platform uses different indexes, ranking logic, and source preferences. A page optimized for Google AI Overviews may be invisible to ChatGPT, and vice versa. Platform-specific optimization is not optional — it is the foundation of any serious GEO strategy. This skill now audits the **top 10 globally used AI platforms**, ensuring comprehensive AI search visibility.

## How to Use This Skill

1. Collect the target URL and the site's primary topic/industry
2. Run each platform checklist below against the site
3. Score each platform on the 0-100 rubric
4. Generate GEO-PLATFORM-OPTIMIZATION.md with per-platform scores, gaps, and action items

---

## Platform 1: Google AI Overviews (AIO)

### How AIO Selects Sources
- 92% of AIO citations come from pages already ranking in the **top 10 organic results** — traditional SEO is the gateway
- However, 47% of citations come from pages ranking **below position 5** — AIO has its own selection logic favoring clarity and directness over raw rank
- AIO strongly favors pages with **clean structure, direct answers, and scannable formatting**
- Featured snippet optimization has ~70% overlap with AIO optimization
- AIO prefers **concise, factual, unambiguous answers** — hedging and filler reduce citation probability

### Optimization Checklist

1. **Question-Based Headings**: Use H2/H3 headings phrased as questions matching real user queries. Check Google's "People Also Ask" for the target topic and mirror those exact phrasings.
2. **Direct Answer in First Paragraph**: After each question heading, provide a clear 1-2 sentence answer immediately. Then expand with supporting detail. The first sentence should be a standalone citation candidate.
3. **Tables and Structured Comparisons**: AIO heavily cites tables. Convert any comparison, pricing, specification, or feature data into HTML tables. Use clear column headers.
4. **Ordered and Unordered Lists**: Step-by-step processes should use ordered lists. Feature lists should use unordered lists. AIO extracts these directly.
5. **FAQ Sections**: Add a dedicated FAQ section with 5-10 real questions. Use proper H3 headings for each question. While FAQPage schema rich results are restricted to govt/health sites since Aug 2023, the content pattern still helps AIO extraction.
6. **Definitions and Glossary Boxes**: For any industry-specific term, provide a clear definition. Format: "**[Term]** is [concise definition]." AIO frequently cites definitions.
7. **Statistics with Sources**: Include specific numbers with attribution. "According to [Source], [statistic]." AIO prefers citeable, specific claims over vague assertions.
8. **Publication Date**: Include a visible publication date and last-updated date. AIO deprioritizes undated content for time-sensitive queries.
9. **Author Byline**: Display author name with credentials. Link to an author page with bio, credentials, and sameAs links.
10. **Page Depth**: Keep target pages within 3 clicks of homepage. AIO rarely cites deep, orphaned content.

### Scoring Rubric (0-100)

| Criterion | Points | How to Score |
|---|---|---|
| Ranks in top 10 for target queries | 20 | 20 if yes, 10 if top 20, 0 if beyond |
| Question-based headings present | 10 | 2 points per question heading, max 10 |
| Direct answers after headings | 15 | 3 points per direct answer, max 15 |
| Tables present for comparison data | 10 | 10 if tables used appropriately, 5 if partial, 0 if absent |
| Lists for processes/features | 10 | 10 if present, 5 if partial |
| FAQ section with 5+ questions | 10 | 10 if 5+, 5 if 1-4, 0 if none |
| Statistics with citations | 10 | 2 points per cited stat, max 10 |
| Publication/updated date visible | 5 | 5 if both dates, 3 if one, 0 if none |
| Author byline with credentials | 5 | 5 if full byline, 3 if name only, 0 if none |
| Clean URL + heading hierarchy | 5 | 5 if H1>H2>H3 clean, 3 if minor issues, 0 if broken |

---

## Platform 2: ChatGPT Web Search

### How ChatGPT Selects Sources
- Uses **Bing's search index** as its foundation (not Google)
- Top citation sources by domain share: **Wikipedia (47.9%)**, Reddit (11.3%), YouTube, major news outlets
- ChatGPT heavily weights **entity recognition** — if your brand exists as a structured entity (Wikipedia, Wikidata, Crunchbase), it is far more likely to be cited
- Prefers **authoritative, well-established sources** over new or niche sites
- Longer, more comprehensive articles get cited more often than short pieces
- ChatGPT tends to cite **the most canonical source** for a claim rather than the original

### Optimization Checklist

1. **Wikipedia Presence**: Check if the brand/person/product has a Wikipedia article. If not, assess notability criteria. If notable, create a draft. If an article exists, ensure it is accurate and current.
2. **Wikidata Entity**: Verify the entity exists on Wikidata (wikidata.org). If not, create a Wikidata item with key properties: instance of, official website, social media links, founding date, headquarters location.
3. **Bing Webmaster Tools**: Verify the site is registered in Bing Webmaster Tools. Submit sitemap. Check for crawl errors.
4. **Bing Index Coverage**: Use `site:domain.com` on Bing to verify key pages are indexed. Bing may have different indexed pages than Google.
5. **Reddit Authority**: Check for brand mentions on Reddit. Identify relevant subreddits. Assess whether the brand participates authentically in discussions.
6. **YouTube Presence**: Verify YouTube channel exists with relevant content. Video descriptions should contain full URLs and entity information.
7. **Authoritative Backlinks**: ChatGPT/Bing weight .edu, .gov, and major publication backlinks heavily. Audit backlink profile for these sources.
8. **Entity Consistency**: Brand name, founding date, leadership, and key facts must be consistent across Wikipedia, Crunchbase, LinkedIn, and the official website.
9. **Comprehensive Content**: Pages targeting ChatGPT citation should be **2000+ words** with thorough topic coverage. ChatGPT prefers single authoritative sources over combining multiple thin pages.
10. **Clear Attribution**: Include "About" sections, company descriptions, and founding stories. ChatGPT uses these for entity grounding.

### Scoring Rubric (0-100)

| Criterion | Points | How to Score |
|---|---|---|
| Wikipedia article exists and is accurate | 20 | 20 if exists, 10 if stub, 0 if none |
| Wikidata entity with 5+ properties | 10 | 10 if complete, 5 if basic, 0 if none |
| Bing index coverage of key pages | 10 | 10 if full, 5 if partial, 0 if poor |
| Reddit brand mentions (positive) | 10 | 10 if active discussions, 5 if mentions, 0 if none |
| YouTube channel with relevant content | 10 | 10 if active, 5 if present but sparse, 0 if none |
| Authoritative backlinks (.edu, .gov, press) | 15 | 3 points per authoritative backlink category, max 15 |
| Entity consistency across platforms | 10 | 10 if consistent, 5 if minor discrepancies, 0 if major |
| Content comprehensiveness (2000+ words) | 10 | 10 if thorough, 5 if adequate, 0 if thin |
| Bing Webmaster Tools configured | 5 | 5 if verified, 0 if not |

---

## Platform 3: Perplexity AI

### How Perplexity Selects Sources
- Top citation sources: **Reddit (46.7%)**, Wikipedia, YouTube, major publications
- Perplexity places the **heaviest emphasis on community validation** of all AI search platforms
- Strongly favors **discussion threads** where claims are debated, validated, or expanded by multiple participants
- Prefers recent content — publication date is a strong ranking signal
- Cites **multiple sources per answer** (typically 5-15), so there is more opportunity for mid-authority sites to appear
- Uses its own crawling infrastructure in addition to search APIs

### Optimization Checklist

1. **Active Reddit Presence**: The brand or its representatives should participate authentically in relevant subreddit discussions. Not promotional — helpful, specific, and community-oriented.
2. **Reddit AMAs and Threads**: Encourage or participate in AMAs, detailed discussion threads, and community Q&As. Perplexity treats these as high-signal content.
3. **Forum and Community Presence**: Beyond Reddit, check Hacker News, Stack Overflow, Quora, and niche industry forums. Perplexity indexes these heavily.
4. **Discussion-Friendly Content**: Publish content that invites discussion — opinion pieces, research findings, contrarian takes, original data. Content that gets shared and debated in communities ranks higher.
5. **Freshness Signals**: Publish content with clear dates. Update content regularly. Perplexity deprioritizes stale content more aggressively than other platforms.
6. **Multiple Source Validation**: Claims in your content should be supported by other sources. Perplexity cross-references and prefers claims it can verify from multiple origins.
7. **YouTube Video Content**: Create video content that Perplexity can reference. Ensure video titles, descriptions, and transcripts contain target information.
8. **Direct, Quotable Passages**: Write paragraphs that can stand alone as citations. Each paragraph should make one clear point with supporting evidence.
9. **Original Data and Research**: Publish original surveys, benchmarks, case studies, or datasets. Perplexity heavily favors primary sources.
10. **Perplexity Pages**: Check if Perplexity has created a "Page" about your topic/brand. These are curated summaries that influence future citations.

### Scoring Rubric (0-100)

| Criterion | Points | How to Score |
|---|---|---|
| Active Reddit presence in relevant subreddits | 20 | 20 if active contributor, 10 if mentioned, 0 if absent |
| Forum/community mentions (HN, SO, Quora) | 10 | 10 if multiple platforms, 5 if one, 0 if none |
| Content freshness (updated within 6 months) | 10 | 10 if recent, 5 if within year, 0 if older |
| Original research/data published | 15 | 15 if original research, 10 if case studies, 5 if some data, 0 if none |
| YouTube content with transcripts | 10 | 10 if active channel, 5 if some videos, 0 if none |
| Quotable, standalone paragraphs | 10 | 2 points per well-structured quotable paragraph, max 10 |
| Multi-source claim validation | 10 | 10 if claims well-sourced, 5 if some sourcing, 0 if none |
| Discussion-generating content | 10 | 10 if content gets shared/discussed, 5 if some engagement, 0 if none |
| Wikipedia/Wikidata presence | 5 | 5 if present, 0 if absent |

---

## Platform 4: Google Gemini

### How Gemini Selects Sources
- Uses **Google's search index** plus strong weighting toward **Google-owned properties**
- YouTube content is weighted significantly more heavily than in standard Google Search
- Google Business Profile data is directly accessible to Gemini
- Gemini uses Google's Knowledge Graph directly — entity presence in Knowledge Graph is a major advantage
- Structured data (Schema.org) is consumed directly by Gemini for entity understanding
- Gemini multi-modal: can reference images, videos, and text together

### Optimization Checklist

1. **Google Knowledge Panel**: Check if the brand has a Google Knowledge Panel. If not, claim it through Google Business Profile or structured data. Ensure all information is accurate.
2. **Google Business Profile**: Complete and optimize GBP with all fields: hours, services, photos, posts, Q&A. Gemini pulls directly from GBP for local queries.
3. **YouTube Strategy**: Create YouTube content for every key topic. Optimize titles, descriptions, timestamps, and closed captions. Gemini cites YouTube more than any other AI platform.
4. **YouTube Chapters and Timestamps**: Use chapters (timestamps in description) so Gemini can reference specific segments of videos.
5. **Google Merchant Center**: For e-commerce, ensure products are in Google Merchant Center. Gemini references product data directly.
6. **Structured Data (Schema.org)**: Implement comprehensive Schema.org markup. Gemini uses this for entity understanding more aggressively than other platforms.
7. **Google Sites Ecosystem**: Ensure presence across Google ecosystem: Google Scholar (for research), Google News (for publishers), Google Maps (for local).
8. **Image Optimization**: Gemini is multi-modal. Use descriptive alt text, structured image filenames, and high-quality images. Include relevant images with every piece of content.
9. **Google E-E-A-T Signals**: All standard Google E-E-A-T signals apply with extra weight. Author pages, about pages, editorial policies, and expertise demonstrations.
10. **Chrome Web Store / Google Workspace Marketplace**: For software companies, presence on Google platforms adds entity signals.

### Scoring Rubric (0-100)

| Criterion | Points | How to Score |
|---|---|---|
| Google Knowledge Panel exists | 15 | 15 if complete, 10 if partial, 0 if none |
| Google Business Profile complete | 10 | 10 if fully optimized, 5 if basic, 0 if none |
| YouTube channel with topic-relevant content | 20 | 20 if active with chapters, 10 if present, 0 if none |
| Schema.org structured data implemented | 15 | 15 if comprehensive, 10 if basic, 5 if minimal, 0 if none |
| Google ecosystem presence (Scholar, News, Maps) | 10 | 10 if 3+, 5 if 1-2, 0 if none |
| Image optimization (alt text, filenames) | 10 | 10 if all images optimized, 5 if partial, 0 if none |
| E-E-A-T signals (author pages, about, editorial) | 10 | 10 if strong, 5 if partial, 0 if weak |
| Google Merchant Center (if e-commerce) | 5 | 5 if applicable and active, N/A otherwise |
| Multi-modal content (text + images + video) | 5 | 5 if rich multi-modal, 3 if some, 0 if text-only |

---

## Platform 5: Bing Copilot

### How Copilot Selects Sources
- Uses **Bing's search index** (shared infrastructure with ChatGPT but different ranking/selection)
- Supports **IndexNow protocol** for near-instant indexing of new and updated content
- Copilot tends to cite **fewer sources per answer** (typically 3-5) but gives more prominent attribution
- Microsoft ecosystem integration: LinkedIn, GitHub, Microsoft Learn content is weighted
- Copilot prefers pages with clear, structured markup and fast load times

### Optimization Checklist

1. **Bing Webmaster Tools**: Register and verify site. Submit XML sitemap. Review and fix any crawl issues.
2. **IndexNow Implementation**: Implement the IndexNow protocol to notify Bing of content changes in real-time. Submit a key file at `/.well-known/indexnow-key.txt` and ping the IndexNow API on content publish/update.
3. **LinkedIn Company Page**: Ensure the company LinkedIn page is complete with accurate description, employee connections, and regular posts. Copilot indexes LinkedIn content.
4. **GitHub Presence**: For tech companies, maintain an active GitHub presence. Copilot references GitHub repos, documentation, and README files.
5. **Microsoft Learn / Documentation**: If relevant, contribute to Microsoft Learn or ensure documentation is compatible with Microsoft's documentation standards.
6. **Bing Places for Business**: Equivalent to Google Business Profile. Complete all fields for local search visibility in Copilot.
7. **Clear Meta Descriptions**: Bing/Copilot weights meta descriptions more heavily than Google does. Write compelling, keyword-rich meta descriptions for every page.
8. **Social Signals**: Bing has historically weighted social signals (shares, likes, engagement) more than Google. Maintain active social media presence.
9. **Exact-Match Keywords**: Bing's algorithm is more literal about keyword matching than Google. Include exact target phrases in titles, headings, and body content.
10. **Fast Page Load**: Copilot deprioritizes slow pages. Target sub-2-second load time. Optimize images, enable compression, minimize render-blocking resources.

### Scoring Rubric (0-100)

| Criterion | Points | How to Score |
|---|---|---|
| Bing Webmaster Tools verified + sitemap | 15 | 15 if verified, 5 if partial, 0 if not |
| IndexNow protocol implemented | 15 | 15 if active, 0 if not |
| Bing index coverage of key pages | 10 | 10 if full, 5 if partial, 0 if poor |
| LinkedIn company page (complete) | 10 | 10 if complete, 5 if basic, 0 if none |
| GitHub presence (if applicable) | 5 | 5 if active, N/A if not applicable |
| Meta descriptions optimized | 10 | 10 if all key pages, 5 if partial, 0 if missing |
| Social media engagement signals | 10 | 10 if active engagement, 5 if present, 0 if none |
| Exact-match keywords in titles/headings | 10 | 10 if well-optimized, 5 if partial, 0 if not |
| Page load speed < 2 seconds | 10 | 10 if < 2s, 5 if < 4s, 0 if > 4s |
| Bing Places configured (if local) | 5 | 5 if complete, N/A if not local |

---

---

## Platform 6: Claude (Anthropic)

### How Claude Selects Sources
- Claude's web search (claude.ai) uses ClaudeBot to fetch pages and favors **authoritative, factual, well-cited content**
- Claude's Constitutional AI principles mean it **deprioritizes promotional, biased, or unsubstantiated claims**
- Strongly weights **author credentials and explicit expertise signals**
- Prefers content that directly answers questions in the first paragraph — passage extraction model
- Claude has limited JavaScript rendering; content must be server-rendered to be indexed
- Growing user base (100M+ users as of 2025); significant citation opportunity for authoritative brands

### Optimization Checklist

1. **Author Expertise Pages**: Create dedicated author profile pages linking to credentials, publications, or professional profiles. Claude heavily weights explicit expertise signals.
2. **Balanced, Non-Promotional Tone**: Rewrite heavily promotional copy to be objective and evidence-based. Claude scores down content that reads as advertising.
3. **Explicit Source Attribution**: After any factual claim, link or name the source. "According to [specific study/source]" patterns are highly citeable by Claude.
4. **ClaudeBot robots.txt Access**: Verify ClaudeBot is not blocked in robots.txt. Check for wildcard Disallow rules that may inadvertently block it.
5. **Server-Side Rendering (SSR)**: Ensure all key content is rendered in the initial HTML response. JavaScript-only content is invisible to ClaudeBot.
6. **Concise Answer Blocks**: After each heading, write a 40-80 word direct answer that works as a standalone citation. This is Claude's preferred extraction pattern.
7. **FAQ and Q&A Sections**: Structure key information as question-and-answer blocks. Claude frequently lifts these verbatim when answering user queries.
8. **Trustworthiness Signals**: Display trust indicators — security badges, industry certifications, third-party reviews, and editorial policies. Claude's safety training makes it trust transparent, verified sources.
9. **Avoid Clickbait Headlines**: Headings that overpromise or sensationalize reduce Claude's citation probability. Use clear, factual headings.
10. **Internal Knowledge Graph**: Link between related pages on your site to help Claude understand the breadth of your topical expertise.

### Scoring Rubric (0-100)

| Criterion | Points | How to Score |
|---|---|---|
| ClaudeBot allowed in robots.txt | 15 | 15 if allowed, 0 if blocked or ambiguous |
| Key content server-rendered (no JS dependency) | 15 | 15 if full SSR, 8 if partial, 0 if SPA-only |
| Author pages with explicit credentials | 15 | 15 if full author pages, 8 if byline only, 0 if none |
| Explicit source attribution on factual claims | 15 | 3 per cited source pattern, max 15 |
| Concise direct answer blocks after headings | 15 | 3 per qualifying block, max 15 |
| Non-promotional, balanced content tone | 10 | 10 if objective, 5 if mixed, 0 if promotional |
| FAQ / Q&A sections present | 10 | 10 if 5+ Q&As, 5 if 1-4, 0 if none |
| Trust signals (certifications, reviews, editorial policy) | 5 | 5 if multiple signals, 2 if one, 0 if none |

---

## Platform 7: Meta AI

### How Meta AI Selects Sources
- Meta AI is embedded in Facebook, Instagram, WhatsApp, and Messenger — reaching **3B+ daily active users**
- Relies on Meta's social graph: content with high Facebook/Instagram engagement is surfaced more often
- Uses **Llama models** and FacebookBot/Meta-ExternalAgent to crawl the web
- **Open Graph (og:) tags** are critical — Meta AI uses them to understand and represent pages
- Strongly favors brands with active, high-engagement social presence on Meta platforms
- Local businesses benefit from complete Facebook Business Profile data

### Optimization Checklist

1. **Open Graph Tags**: Implement complete og:title, og:description, og:image, og:url, og:type on every page. Meta AI parses these first when understanding a page's context.
2. **Facebook Business Page**: Create/optimize a Facebook Business Page with complete info: category, description, phone, address, hours, website link. This is Meta AI's primary data source for local/business queries.
3. **Instagram Business Profile**: Ensure Instagram is a Business or Creator account with bio link, contact info, and consistent visual branding.
4. **FacebookBot Access**: Verify FacebookBot and Meta-ExternalAgent are not blocked in robots.txt.
5. **High-Engagement Content Strategy**: Publish content on Facebook/Instagram designed to generate shares and comments. Engagement is a direct authority signal for Meta AI.
6. **Facebook Reviews**: Accumulate and respond to Facebook reviews. Meta AI surfaces review sentiment for local and product queries.
7. **WhatsApp Business**: Set up WhatsApp Business with a catalog and automated responses if applicable. Meta AI can reference WhatsApp Business data.
8. **Social Proof on Website**: Embed Facebook reviews, Instagram feeds, or social share counts on your site to reinforce Meta-verified credibility signals.
9. **Consistent NAP Across Meta**: Business name, address, and phone must be identical across Facebook, Instagram, and the website. Meta AI cross-references these for entity confidence.
10. **Meta Business Suite Verification**: Verify your business through Meta Business Suite for maximum trust signals across the Meta ecosystem.

### Scoring Rubric (0-100)

| Criterion | Points | How to Score |
|---|---|---|
| Complete Open Graph tags on all key pages | 20 | 20 if all pages complete, 10 if partial, 0 if missing |
| Facebook Business Page (complete) | 20 | 20 if fully optimized, 10 if basic, 0 if none |
| FacebookBot / Meta-ExternalAgent allowed | 10 | 10 if allowed, 0 if blocked |
| Instagram Business Profile (active) | 15 | 15 if active with regular posts, 8 if present but sparse, 0 if none |
| Facebook reviews (10+ with responses) | 10 | 10 if active reviews, 5 if few, 0 if none |
| Social engagement on brand content | 10 | 10 if high engagement, 5 if moderate, 0 if low |
| NAP consistency across Meta platforms | 10 | 10 if fully consistent, 5 if minor differences, 0 if inconsistent |
| WhatsApp Business (if applicable) | 5 | 5 if set up, N/A if not applicable |

---

## Platform 8: Grok (xAI / X)

### How Grok Selects Sources
- Grok is built into X (Twitter) and has **real-time access to all public X posts and threads**
- Grok-2 and Grok-3 are the current models; prioritizes **recency** over depth more than any other platform
- X presence is the dominant ranking signal — brands with zero X activity are nearly invisible to Grok
- Grok uses xAI's web crawler plus X's real-time data stream for web content
- Particularly strong for tech, finance, current events, and trending topics
- Verified X accounts (blue checkmark / organization badge) receive elevated authority

### Optimization Checklist

1. **Active X (Twitter) Account**: Create and maintain a brand X account. Post at minimum 3x per week. Grok's training data is heavily X-weighted and recency matters enormously.
2. **X Verification**: Obtain X verification (organization badge or blue checkmark). Verified accounts receive higher authority signals in Grok's ranking.
3. **Link Website Content in X Posts**: When publishing new content, post it on X with a link. This creates a direct connection between your X presence and your website content in Grok's index.
4. **Engage in Industry Conversations**: Reply to and join trending conversations in your industry. Grok surfaces brands that participate in relevant X discussions, not just brands that broadcast.
5. **X Spaces Participation**: Host or appear as a guest on X Spaces (live audio). Grok can reference and cite X Spaces content.
6. **Real-Time Content Updates**: Publish breaking news, rapid commentary, or timely data on your website with clear timestamps. Grok is used heavily for time-sensitive queries.
7. **Trending Hashtag Alignment**: Identify the top 5-10 hashtags in your industry and incorporate them into X posts when genuinely relevant.
8. **Thread-Form Content**: Create Twitter/X threads that expand on key topics from your website. Threads are highly indexed by Grok and can drive users back to the source content.
9. **Fast Page Load for Real-Time Events**: When you publish trending content, your site must load fast — Grok may surface your link during a viral moment when traffic spikes.
10. **Monitor X Mentions**: Track brand mentions on X and engage with them. High reply/repost engagement on brand mentions signals authority to Grok.

### Scoring Rubric (0-100)

| Criterion | Points | How to Score |
|---|---|---|
| Active X account (3+ posts/week) | 20 | 20 if active, 10 if occasional, 0 if absent |
| X verification status | 15 | 15 if verified, 0 if not |
| Follower count (relative to industry) | 15 | 15 if strong, 8 if moderate, 0 if minimal |
| Content linked from X to website | 10 | 10 if regularly linked, 5 if occasionally, 0 if never |
| X engagement rate (likes, reposts per post) | 15 | 15 if high, 8 if moderate, 0 if low |
| Industry conversation participation (replies/threads) | 10 | 10 if active, 5 if occasional, 0 if broadcast-only |
| Content freshness and recency signals on website | 10 | 10 if updated regularly with dates, 5 if partial, 0 if outdated |
| X Spaces participation | 5 | 5 if active, 0 if none |

---

## Platform 9: DeepSeek

### How DeepSeek Selects Sources
- DeepSeek (V3, R1) is a rapidly growing open-source Chinese AI with **global reach**, especially dominant in technical, scientific, and research queries
- Trained on large corpora of academic papers, code repositories, and technical documentation
- Strongly favors **primary sources**: original research, datasets, technical documentation, and peer-reviewed findings
- Developer community is massive — GitHub presence and code documentation are important authority signals
- DeepSeekBot crawls the web; accessible, server-rendered content is required
- Growing multilingual capability — Chinese and English content doubles reach across its user base

### Optimization Checklist

1. **Deep Technical Documentation**: Publish thorough technical documentation, API references, or how-to guides. DeepSeek is trained heavily on technical content and prefers these as authoritative sources.
2. **Research and Data Publications**: Create or cite original research, case studies, benchmarks, or datasets. DeepSeek is more likely to cite primary sources than summaries.
3. **Academic Citation Style**: Use explicit, formal citations (author, year, publication). DeepSeek's training on academic papers means it recognizes and weights this citation style.
4. **GitHub Presence**: For technical brands, maintain an active GitHub organization with starred repositories and quality READMEs. DeepSeek heavily indexes developer platforms.
5. **DeepSeekBot Access**: Ensure DeepSeekBot (or the generic `*` wildcard) is not blocked in robots.txt. DeepSeek's crawler needs access to index your content.
6. **English + Chinese Content**: If feasible, publish key content in both English and Simplified Chinese. This doubles visibility across DeepSeek's primary user demographics.
7. **arXiv and Research Platform Presence**: For research-adjacent brands, publish or cite arXiv papers. DeepSeek's training data is weighted toward arXiv and academic repositories.
8. **Reproducible Methodologies**: When publishing research or case studies, include methodology details, sample sizes, and reproducible steps. DeepSeek values verifiable claims.
9. **Code Examples and Snippets**: Include working code examples on technical pages. DeepSeek trained on large code corpora and cites technical pages with concrete examples.
10. **No Geo-Restrictions**: Ensure the site is accessible from China and Asia without CAPTCHA gates or geo-blocks. DeepSeek's users are globally distributed with high concentration in Asia.

### Scoring Rubric (0-100)

| Criterion | Points | How to Score |
|---|---|---|
| Technical documentation / guides depth | 20 | 20 if comprehensive, 10 if moderate, 0 if absent |
| Original research or primary data published | 20 | 20 if original research, 10 if case studies/data, 0 if none |
| Formal citations and academic references | 15 | 3 per cited academic/primary source, max 15 |
| GitHub or developer platform presence | 10 | 10 if active, 5 if present, 0 if absent |
| DeepSeekBot accessible (robots.txt) | 10 | 10 if allowed, 0 if blocked |
| Content accessible from Asia (no geo-blocks) | 10 | 10 if globally accessible, 5 if partial, 0 if blocked |
| Code examples or technical snippets | 10 | 10 if present on technical pages, 5 if some, 0 if none |
| Chinese language content (if applicable) | 5 | 5 if bilingual, N/A if not applicable |

---

## Platform 10: Apple Intelligence

### How Apple Intelligence Selects Sources
- Apple Intelligence is integrated into **iOS 18+, macOS Sequoia+, and 2B+ Apple devices** via Siri, Writing Tools, and Smart Summarization
- Uses **Applebot-Extended** for training data collection; Applebot for live Siri queries
- Prioritizes **mobile-first, privacy-respecting, standards-compliant content**
- Safari rendering engine (WebKit) is used — Safari-incompatible sites are poorly parsed
- Siri Knowledge Graph is built from structured data, App Store metadata, and Apple Maps
- Apple Intelligence's summarization engine strongly prefers clean, semantic HTML5 content
- Voice search optimization (Siri queries are conversational and natural language) is key

### Optimization Checklist

1. **Applebot-Extended Access**: Verify Applebot-Extended is explicitly allowed in robots.txt (or not blocked by wildcard rules). This is the direct signal for Apple Intelligence training inclusion.
2. **Safari/WebKit Compatibility**: Test all key pages in Safari on iPhone and Mac. Apple Intelligence uses WebKit for rendering; CSS Grid, Flexbox, and modern JS are well-supported; proprietary Chrome APIs are not.
3. **Fast Mobile Load Time**: Achieve LCP (Largest Contentful Paint) under 2.5s on mobile. Apple Intelligence and Siri prioritize fast-loading mobile pages for on-device processing.
4. **HTTPS with Valid Certificate**: Apple blocks mixed content and penalizes HTTP sites. Full HTTPS with a valid, modern TLS certificate is mandatory.
5. **Semantic HTML5**: Use proper HTML5 elements: `<article>`, `<section>`, `<nav>`, `<header>`, `<footer>`, `<aside>`. Apple's summarization engine uses these for content structure understanding.
6. **Siri-Optimized Q&A Content**: Write key content in natural language question-and-answer format. Siri queries are conversational ("What is the best way to...?" "How do I...?") — mirror this in headings and answers.
7. **Schema.org Organization / LocalBusiness**: Implement Organization or LocalBusiness schema with complete fields. Siri uses structured data for entity recognition and quick fact retrieval.
8. **App Store Presence (if applicable)**: For software/app companies, maintain a complete, keyword-optimized App Store listing. Apple Intelligence directly references App Store data for app queries.
9. **Privacy-Compliant Implementation**: Minimize third-party trackers (Safari's ITP blocks many). Sites with heavy tracking that Safari blocks may be poorly rendered by Apple Intelligence.
10. **iOS Universal Links**: Implement Apple Universal Links to allow Siri to deep-link into your app from web content if an app exists. This bridges web and app presence in Apple's ecosystem.

### Scoring Rubric (0-100)

| Criterion | Points | How to Score |
|---|---|---|
| Applebot-Extended allowed in robots.txt | 15 | 15 if allowed, 0 if blocked or unclear |
| Safari/WebKit rendering (no Safari-specific bugs) | 15 | 15 if fully compatible, 8 if minor issues, 0 if broken |
| Mobile LCP < 2.5s | 15 | 15 if < 2.5s, 8 if < 4s, 0 if > 4s |
| Semantic HTML5 elements used throughout | 10 | 10 if consistent, 5 if partial, 0 if div-soup |
| Schema.org Organization or LocalBusiness | 15 | 15 if comprehensive, 8 if basic, 0 if absent |
| Siri-optimized conversational Q&A content | 10 | 10 if present, 5 if some, 0 if none |
| HTTPS with valid certificate | 10 | 10 if full HTTPS, 0 if issues |
| App Store presence (if applicable) | 5 | 5 if optimized, N/A if no app |
| Privacy-compliant (minimal Safari-blocked trackers) | 5 | 5 if clean, 3 if some issues, 0 if heavy tracking |

---

## Cross-Platform Summary

### Universal Optimization Actions (help ALL 10 platforms)
1. Wikipedia/Wikidata entity presence
2. YouTube channel with relevant content
3. Comprehensive, well-structured content with clear headings
4. Schema.org structured data (especially Organization + sameAs)
5. Fast page load and clean HTML (SSR, not JS-only)
6. Author pages with credentials and sameAs links
7. Regular content updates with visible dates
8. Allow all major AI crawlers in robots.txt
9. HTTPS with valid TLS certificate
10. Direct answer blocks after question-based headings

### Platform-Specific Priorities
| Priority | Google AIO | ChatGPT | Perplexity | Gemini | Copilot | Claude | Meta AI | Grok | DeepSeek | Apple |
|---|---|---|---|---|---|---|---|---|---|---|
| #1 | Top-10 ranking | Wikipedia | Reddit presence | YouTube | IndexNow | Author credentials | Facebook page | X account | Technical docs | Applebot access |
| #2 | Q&A structure | Entity graph | Original research | Knowledge Panel | Bing WMT | Source attribution | Open Graph tags | X engagement | Primary research | Safari compat |
| #3 | Tables/lists | Bing SEO | Freshness | Schema.org | LinkedIn | ClaudeBot access | Social engagement | Real-time content | GitHub presence | Mobile speed |
| #4 | Featured snippets | Reddit | Community forums | GBP | Meta descriptions | Balanced tone | Reviews/ratings | Trending alignment | Academic citations | Schema.org |

---

## Output Format

Generate **GEO-PLATFORM-OPTIMIZATION.md** with the following structure:

```markdown
# GEO Platform Optimization Report — [Domain]
Date: [Date]

## Overall Platform Readiness
- Combined GEO Score: XX/100 (average of all 10 platform scores)

## Platform Scores
| Platform | Score | Status |
|---|---|---|
| Google AI Overviews | XX/100 | [Strong/Moderate/Weak] |
| ChatGPT Web Search | XX/100 | [Strong/Moderate/Weak] |
| Perplexity AI | XX/100 | [Strong/Moderate/Weak] |
| Google Gemini | XX/100 | [Strong/Moderate/Weak] |
| Bing Copilot | XX/100 | [Strong/Moderate/Weak] |
| Claude (Anthropic) | XX/100 | [Strong/Moderate/Weak] |
| Meta AI | XX/100 | [Strong/Moderate/Weak] |
| Grok (xAI / X) | XX/100 | [Strong/Moderate/Weak] |
| DeepSeek | XX/100 | [Strong/Moderate/Weak] |
| Apple Intelligence | XX/100 | [Strong/Moderate/Weak] |

Status thresholds: Strong = 70+, Moderate = 40-69, Weak = 0-39

## Platform Details
[Per-platform breakdown with score, gaps found, specific actions for all 10 platforms]

## Prioritized Action Plan
### Quick Wins (this week)
[Actions that improve multiple platform scores with minimal effort]

### Medium-Term (this month)
[Actions requiring content creation or technical changes]

### Strategic (this quarter)
[Actions requiring entity building, community development, or platform presence]
```
