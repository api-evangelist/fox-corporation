# Fox Corporation (fox-corporation)

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
