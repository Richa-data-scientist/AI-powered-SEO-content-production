# AI-Powered SEO Content Production — Research Project

**Researcher:** Dashiell Hanson Picardo  
**Role:** Freelance Digital Marketing Executive  
**Date:** June 10, 2026  
**Topic Selected:** AI-Powered SEO Content Production

---

## What This Repository Contains

This repository is a research project on AI-powered SEO content production, built as part of the 100 Hires program. It collects original content — LinkedIn posts, YouTube transcripts, newsletters, and conference material — from 10 practitioners who actively run experiments in this space.

The goal is to build a source base strong enough to support a real playbook later. Everything here is primary material, not summaries of summaries.

---

## Repository Structure

```
/research
  /sources.md                  — All 10 experts with links, follower counts, annotations, and why they made the cut
  /linkedin-posts/             — Posts organized by author
  /youtube-transcripts/        — Transcripts organized by video
  /other/                      — Newsletters, Substack articles, conference talks, additional materials
```

---

## The 10 Experts

| # | Name | Role / Affiliation | Primary Channels | LinkedIn Followers |
|---|------|--------------------|------------------|--------------------|
| 1 | Kevin Indig | Growth Advisor · ex-Shopify, Atlassian · Growth Memo | Newsletter, LinkedIn, Podcast | 61,286 |
| 2 | Lily Ray | VP SEO & AI Search, Amsive · Founder, Algorythmic | Substack, LinkedIn, Conferences | 54,382 |
| 3 | Jake Ward | Founder, Byword (AI SEO content platform) | LinkedIn, X/Twitter | 194,778 |
| 4 | Aleyda Solis | International SEO Consultant · SEOFOMO Newsletter | Newsletter, YouTube (Crawling Mondays), LinkedIn | 116,626 |
| 5 | Ross Simmonds | CEO, Foundation Marketing · Founder, Distribution.ai | LinkedIn, YouTube, Podcast | 59,761 |
| 6 | Nathan Gotch | Founder, GotchSEO Academy · Founder, Rankability | YouTube, LinkedIn, Academy | 75,919 |
| 7 | Kyle Roof | Co-founder, High Voltage SEO · Inventor, Page Optimizer Pro (US Patent) | LinkedIn, Conferences | 18,780 |
| 8 | Brendan Hufford | Founder, Growth Sprints · SaaS Content & AEO Strategist | LinkedIn, Newsletter | 52,231 |
| 9 | Lazarina Stoy | SEO + Data Science Consultant · Founder, MLforSEO Academy | LinkedIn, Search Engine Land | 9,528 |
| 10 | Milosz Krasinski | Founder, Chilli Fruit Web Consulting · SEO for SaaS & Fortune 500 | LinkedIn, Blog | 6,597 |

---

## Why These Experts

The selection criteria were simple: practitioners over pundits, data over advice, builders over bloggers.

Each person on this list either runs original research studies with real datasets, has built a product that embodies their methodology, works with named clients and publishes transparent results, or operates at the technical intersection of AI and SEO — not just content strategy. Several do all four.

Specifically excluded: anyone whose primary output is "top X tools" listicles, conference speakers who recycle Google's official guidance, and generalist marketing voices who added "AI" to their bio in 2024.

**Signal quality by expert:**

- **Kevin Indig** — Runs original clickstream research (846k sessions, Feb–Mar 2026). His distinction between AI Mode and AI Overview search behaviour is backed by data, not inference.
- **Lily Ray** — Tracks AI citations at scale. Founded Algorythmic to run live client experiments. Critically examines GEO hype while being constructively specific.
- **Jake Ward** — Built Byword, helped Causal.app reach 1M monthly visitors using AI content. His 'World's Largest AI SEO Case Study' post is rooted in production data.
- **Aleyda Solis** — Building LearningAIsearch.com alongside active client work. June 2025 research comparing AI prompts vs. Google queries across page types (with SimilarWeb data) is original, not aggregated.
- **Ross Simmonds** — Founded Distribution.ai as a product built on his thesis that distribution beats creation. Used GEO tracking tools at SEO Week 2025 to show how Reddit threads influence LLMs.
- **Nathan Gotch** — Built two products (GotchSEO Academy + Rankability) and teaches directly from client results. Clear-headed on where AI accelerates SEO vs. where it amplifies mistakes.
- **Kyle Roof** — Holds a US patent on SEO testing methodology. His 'Lorem Ipsum' experiment proved SEO is mathematical. 400+ controlled ranking experiments, not opinion.
- **Brendan Hufford** — Tracks 100+ AEO prompts per client engagement and publishes the data gaps between what Google says and what the data shows. Inc 5000 fastest-growing businesses 2025.
- **Lazarina Stoy** — Wrote for Search Engine Land on GPT-4 vs. Google Cloud APIs for SEO automation — actual API benchmarking, not marketing. Trains B2B/SaaS teams on ML-enabled workflows.
- **Milosz Krasinski** — Works with SurferSEO, Brand24, UserPilot. Openly publishes which AI-era tactics moved the needle and which failed.

---

## Data Collection — Technical Notes

Four collection methods were attempted. Results were honest:

| Method | Status | Notes |
|--------|--------|-------|
| Web search | ✓ Effective | Used to triangulate expert credibility, verify claims, find LinkedIn posts and conference talks. Returned real 2025–26 content. |
| Web fetch | ~ Partial | Fetched LinkedIn post content, Substack articles, and conference transcripts where publicly indexed. |
| YouTube transcripts (Supadata API) | ~ Feasible | API exists and is production-ready (100 free req/month). Requires API key signup. YouTube.com blocked direct fetch (429). |
| LinkedIn scraping | ~ Limited | LinkedIn blocks unauthenticated scraping. Post snippets surfaced via Google indexing — adequate for sampling themes. Manual collection is the reliable path for full post text. |

---

## Commit Approach

Commits are incremental — one expert or one collection batch at a time. No single giant commit at the end.

---

## Status

- [x] Expert selection and annotation complete
- [x] Sources documented in `/research/sources.md`
- [ ] LinkedIn posts collected per author
- [ ] YouTube transcripts collected per video
- [ ] Additional materials (newsletters, Substack, conference talks) organised
