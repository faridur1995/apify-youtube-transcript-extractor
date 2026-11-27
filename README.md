# YouTube Transcript Extractor: An Apify Actor (In Development)

> Building in public: our first AI agent for the Apify Store.

Project notes for the first Apify Actor built by our small team from Chattogram, Bangladesh. It is part of a wider plan to build and sell AI agents and automation bots on global AI marketplaces (Apify, Swarms and Neura Market).

## Honest status

- The Actor is **not live on the Apify Store yet**
- We have **not earned anything yet**; this is day one of the journey
- This repository holds project notes only. The source code and any credentials are not included

## What it does

Pulls the full transcript of any public YouTube video from a link or a video ID.

| Input | Output |
| --- | --- |
| Video link or video ID | Clean JSON transcript |
| Language of your choice | Transcript in that language |
| Optional timestamps | Text with or without time markers |

## Who it is for

- AI and RAG developers who need clean text from videos
- Content creators repurposing videos into blogs, newsletters and posts
- SEO and research teams analysing video content at scale
- Anyone building video-to-text or summarisation workflows

## What was tested

- Bangla (Bengali) videos
- Videos with captions turned off
- Invalid links
- Duplicate URLs

## What we learned

YouTube sometimes blocks requests that come from cloud servers, so smart retries and proxies matter a lot. We are improving reliability before publishing.

## Next steps

1. Reliability fixes
2. Pay-per-result pricing
3. Publishing on the Apify Store

## Author

Faridur Rahman. Portfolio and project updates: [sites.google.com/view/faridur-rahman-research](https://sites.google.com/view/faridur-rahman-research)

Prepared by Faridur Rahman
