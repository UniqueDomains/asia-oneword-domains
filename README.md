# Available .ASIA One-Word Domains (9,888)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-9%2C888%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .asia one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **9,888 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 9,888 domains · **Median ask:** $3.81 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-07  
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

- `asia.csv` — public CSV extract (1,000 rows)
- `asia.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/asia-oneword-domains/main/asia.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                 |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------------------------------- |
| keepthechange.asia | available | $2.99     | —             | 46             | 59     | 15     | name.com                                  |
| matcha.asia        | resell    | —         | —             | 86             | 39     | 6      | GoDaddy.com, LLC                          |
| forms.asia         | available | $2.99     | —             | 54             | 28     | 5      | name.com                                  |
| bar.asia           | resell    | —         | —             | 76             | 35     | 3      | Realtime Register B.V.                    |
| pops.asia          | available | $2.19     | $13.49        | 74             | 24     | 4      | namesilo                                  |
| partners.asia      | resell    | —         | —             | 61             | 32     | 8      | Spaceship, Inc.                           |
| pls.asia           | available | $2.99     | —             | 60             | 23     | 3      | name.com                                  |
| dogs.asia          | resell    | —         | —             | 76             | 28     | 4      | Spaceship, Inc.                           |
| signs.asia         | available | $2.99     | —             | 64             | 22     | 5      | name.com                                  |
| bricks.asia        | resell    | —         | —             | 56             | 28     | 6      | Spaceship, Inc.                           |
| oceans.asia        | available | $2.99     | —             | 64             | 22     | 6      | name.com                                  |
| trades.asia        | resell    | —         | —             | 71             | 26     | 6      | Spaceship, Inc.                           |
| bubbles.asia       | available | $2.99     | —             | 72             | 21     | 7      | name.com                                  |
| sites.asia         | resell    | —         | —             | 53             | 26     | 5      | Dreamscape Networks International Pte Ltd |
| Mikey.asia         | available | $18.98    | —             | 70             | 21     | 5      | namecheap                                 |
| comics.asia        | resell    | —         | —             | 68             | 24     | 6      | GoDaddy.com, LLC                          |
| VHS.asia           | available | $18.98    | —             | 71             | 20     | 3      | namecheap                                 |
| products.asia      | resell    | —         | —             | 60             | 23     | 8      | GoDaddy.com, LLC                          |
| generations.asia   | available | $2.99     | —             | 56             | 20     | 11     | name.com                                  |
| results.asia       | resell    | —         | —             | 59             | 22     | 7      | GoDaddy.com, LLC                          |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 9,888 live domains                         |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/asia?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_asia_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/asia?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_asia_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_asia_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection is entirely made up of .asia domains. The set includes concise dictionary-style words like chore.asia, dear.asia, unit.asia, and annual.asia, alongside longer or more expressive names such as headoverheels.asia and youknowit.asia. For founders, the clearest candidates are the short, familiar words that are easy to say and remember. For investors, the key distinction is breadth of buyer appeal: generic words usually have wider resale potential than niche, abstract, or longer phrase-based names. Median ask pricing is around 3.81, so the main evaluation work is less about headline price and more about clarity, commercial relevance, and possible trademark friction.

- All names in this selection use the .asia extension
- Includes 9,887 domains updated daily
- Median ask pricing is around 3.81
- Short generic words usually merit the closest review

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .ASIA One-Word Domains*. Version 2026-05-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .ASIA page](https://unique.domains/domains/tld/asia?utm_source=github&utm_medium=referral&utm_campaign=repo_asia_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_asia_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_asia_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_asia_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
