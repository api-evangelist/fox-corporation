# Fox Corporation (fox-corporation)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Fox Corporation (NASDAQ: FOXA, FOX) is a US media company spun out of 21st Century Fox in 2019 when the rest of the business was sold to Disney. Per the company website, "Fox Corporation produces and distributes compelling news, sports, and entertainment content through its primary iconic domestic brands" — Fox News Media (Fox News Channel, Fox Business Network, Fox News Digital, Fox News Audio, Fox Weather), Fox Sports (FS1, FS2, Big Ten Network, Fox Deportes), Fox Entertainment, Fox Television Stations (29 owned-and-operated stations in 14 US markets), and the Tubi Media Group (Tubi free ad-supported streaming, Credible). In May 2024 Fox acquired Mexican sports-betting and casino operator Caliente.mx, extending its sports-and-wagering footprint into Latin America after the original Fox Bet US joint venture with Flutter was wound down in 2023.

Fox does not publish a public developer portal or REST API surface for the parent corporation. Programmatic distribution is delivered via per-brand RSS / Atom feeds (Fox News, Fox Business, Fox Sports, Fox Weather), the Tubi Media Group open source projects on GitHub (github.com/Tubitv, 53 public repositories), and direct B2B advertising and content-syndication relationships rather than self-serve API signup.

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=fox-corporation-api-evangelist&utm_content=repo)

## APIs

No public developer APIs are documented for Fox Corporation. The catalog focuses on the public RSS surface across Fox's brands and Tubi's open source.

## Public RSS Surface

### Fox News (Moxie / google-publisher CDN)

- [Latest](https://moxie.foxnews.com/google-publisher/latest.xml)
- [U.S.](https://moxie.foxnews.com/google-publisher/us.xml)
- [World](https://moxie.foxnews.com/google-publisher/world.xml)
- [Politics](https://moxie.foxnews.com/google-publisher/politics.xml)
- [Opinion](https://moxie.foxnews.com/google-publisher/opinion.xml)
- [Science](https://moxie.foxnews.com/google-publisher/science.xml)
- [Health](https://moxie.foxnews.com/google-publisher/health.xml)
- [Tech](https://moxie.foxnews.com/google-publisher/tech.xml)
- [Travel](https://moxie.foxnews.com/google-publisher/travel.xml)
- [Lifestyle](https://moxie.foxnews.com/google-publisher/lifestyle.xml)
- [Entertainment](https://moxie.foxnews.com/google-publisher/entertainment.xml)
- [Media](https://moxie.foxnews.com/google-publisher/media.xml)
- [Sports](https://moxie.foxnews.com/google-publisher/sports.xml)
- [Videos](https://moxie.foxnews.com/google-publisher/videos.xml)
- Public index: [foxnews.com RSS Feeds](https://www.foxnews.com/story/foxnews-com-rss-feeds)

### Fox Business

- [Latest](https://moxie.foxbusiness.com/google-publisher/latest.xml)
- [Markets](https://moxie.foxbusiness.com/google-publisher/markets.xml)
- [Economy](https://moxie.foxbusiness.com/google-publisher/economy.xml)
- [Personal Finance](https://moxie.foxbusiness.com/google-publisher/personal-finance.xml)
- [Lifestyle](https://moxie.foxbusiness.com/google-publisher/lifestyle.xml)
- [Technology](https://moxie.foxbusiness.com/google-publisher/technology.xml)
- [Videos](https://moxie.foxbusiness.com/google-publisher/videos.xml)

### Fox Weather

- [Latest](https://moxie.foxweather.com/google-publisher/latest.xml)

### Fox Sports (optimized-rss platform)

Fox Sports exposes 24 league/topic RSS feeds via a single `api.foxsports.com/v2/content/optimized-rss` endpoint scoped by a public `partnerKey` and a tag taxonomy (`fs/nfl`, `fs/mlb`, `soccer/epl/league/1`, etc.). Public index: [foxsports.com/rss-feeds](https://www.foxsports.com/rss-feeds). The catalog lists feeds for NFL, MLB, NBA, NHL, College Football, College Basketball, WNBA, Women's College Basketball, NASCAR, Motor Sports, UFC, WWE, Golf, Tennis, Soccer, FIFA World Cup, FIFA Women's World Cup, Olympics, Horseracing, Westminster Kennel Club, World Baseball Classic, UFL, and PressPass.

## Brands

| Brand | URL |
|---|---|
| Fox News Channel | https://www.foxnews.com/ |
| Fox Business Network | https://www.foxbusiness.com/ |
| Fox Sports | https://www.foxsports.com/ |
| Fox Weather | https://www.foxweather.com/ |
| Fox Entertainment | https://www.foxentertainment.com/ |
| Fox Television Stations | https://www.fox.com/ |
| Tubi Media Group | https://tubitv.com/ |
| Credible | https://www.credible.com/ |
| Caliente.mx | https://www.caliente.mx/ |
| Fox One | https://www.foxone.com/ |

## Properties

- [Website](https://www.foxcorporation.com/)
- [Investor Relations](https://investor.foxcorporation.com/)
- [SEC Filings](https://investor.foxcorporation.com/financials/sec-filings/)
- [Press Releases](https://www.foxcorporation.com/press-releases/)
- [Leadership](https://www.foxcorporation.com/leadership/)
- [Careers](https://careers.foxcorporation.com/)
- [LinkedIn](https://www.linkedin.com/company/fox-corporation)
- [Tubi GitHub Organization](https://github.com/Tubitv) — 53 public repositories
- [Tubi Engineering Blog](https://code.tubitv.com/)
- [Fox Ad Solutions](https://www.foxadsolutions.com/)
- [Fox News Newsletters](https://www.foxnews.com/newsletters)
- [Fox News Podcasts](https://www.foxnews.com/podcasts)

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23
