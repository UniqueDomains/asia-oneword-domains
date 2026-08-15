# Available .ASIA One-Word Domains (13,109)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-13%2C109%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .asia one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **13,109 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 13,109 domains · **Median ask:** $2.62 · **High-demand under $2,500:** 4

**Last updated:** 2026-08-15
**Canonical page:** `https://unique.domains/domains/tld/asia`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/asia?utm_source=github&utm_medium=referral&utm_campaign=repo_asia_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./asia.csv">CSV</a> / <a href="./asia.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_asia_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_asia_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .ASIA search](https://unique.domains/domains/tld/asia?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_asia_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .ASIA search](https://unique.domains/domains/tld/asia?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_asia_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_asia_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .ASIA one-word domain catalog.

### Files

- `asia.csv`, public CSV extract (1,000 rows)
- `asia.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/asia-oneword-domains/main/asia.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                            |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------------------------------------------- |
| jesus.asia    | available | —         | —             | high           | medium | 5      | —                                                    |
| fancy.asia    | resell    | —         | —             | high           | low    | 5      | CSL Computer Service Langenbach GmbH d/b/a Joker.com |
| brief.asia    | resell    | —         | —             | high           | low    | 5      | DNSPod, Inc.                                         |
| cxv.asia      | available | $1.98     | $18.98        | low            | low    | 3      | namecheap                                            |
| ass.asia      | resell    | —         | —             | low            | low    | 3      | GoDaddy.com, LLC                                     |
| wicked.asia   | premium   | $2.99     | $20.99        | high           | low    | 6      | name.com                                             |
| dip.asia      | available | $2.99     | —             | high           | low    | 3      | name.com                                             |
| beg.asia      | resell    | —         | —             | medium         | low    | 3      | Porkbun LLC                                          |
| adaptive.asia | premium   | $2.19     | $13.49        | high           | low    | 8      | namesilo                                             |
| ugh.asia      | available | $2.59     | $13.49        | medium         | low    | 3      | namesilo                                             |
| jay.asia      | resell    | —         | —             | medium         | low    | 3      | DNSPod, Inc.                                         |
| intrigue.asia | premium   | $2.59     | $13.49        | high           | low    | 8      | namesilo                                             |
| UML.asia      | available | $2.59     | $13.49        | high           | low    | 3      | namesilo                                             |
| man.asia      | resell    | —         | —             | high           | low    | 3      | Chengdu West Dimension Digital Technology Co., Ltd.  |
| xii.asia      | available | $2.99     | $20.99        | medium         | low    | 3      | name.com                                             |
| may.asia      | resell    | —         | —             | high           | low    | 3      | CSL Computer Service Langenbach GmbH d/b/a Joker.com |
| yur.asia      | available | $2.59     | $13.49        | high           | low    | 3      | namesilo                                             |
| oak.asia      | resell    | —         | —             | medium         | low    | 3      | 1API GmbH                                            |
| aged.asia     | available | $2.99     | $20.99        | high           | low    | 4      | name.com                                             |
| pen.asia      | resell    | —         | —             | medium         | low    | 3      | 1API GmbH                                            |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 13,109 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 4 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/asia?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_asia_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/asia?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_asia_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_asia_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list includes 9,922 one-word .asia domain names, the large majority available now and priced under $500. Names range from simple everyday words like out.asia and just.asia to more distinct picks like Scotchtape.asia. Demand is concentrated in the lower range, with only a small share of names scoring in higher demand tiers, so pricing stays accessible across most of the set.

- 9,922 one-word .asia domains, 9,148 available now
- Median ask around $2.90 — most under $500
- Only 38 names show mid-to-top demand scores
- 6,008 names flagged as easy to spell

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .ASIA One-Word Domains*. Version 2026-08-15. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .ASIA page](https://unique.domains/domains/tld/asia?utm_source=github&utm_medium=referral&utm_campaign=repo_asia_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_asia_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_asia_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_asia_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
