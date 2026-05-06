# Available .LLC One-Word Domains (11,375)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C375%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .llc one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,375 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,375 domains · **Median ask:** $108.92 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/llc`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/llc?utm_source=github&utm_medium=referral&utm_campaign=repo_llc_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./llc.csv">CSV</a> / <a href="./llc.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_llc_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_llc_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .LLC search](https://unique.domains/domains/tld/llc?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_llc_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .LLC search](https://unique.domains/domains/tld/llc?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_llc_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_llc_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .LLC one-word domain catalog.

### Files

- `llc.csv` — public CSV extract (1,000 rows)
- `llc.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/llc-oneword-domains/main/llc.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| barup.llc     | available | $19.99    | —             | 82             | 2      | 6      | name.com        |
| forces.llc    | available | $19.99    | —             | 82             | 12     | 6      | name.com        |
| geton.llc     | available | $19.99    | —             | 82             | 10     | 6      | name.com        |
| matcha.llc    | available | $19.99    | —             | 86             | 39     | 6      | name.com        |
| dogsit.llc    | available | $19.99    | —             | 96             | 2      | 6      | name.com        |
| playon.llc    | available | $19.99    | —             | 80             | 14     | 7      | name.com        |
| QandA.llc     | available | $54.98    | —             | 80             | 10     | 7      | namecheap       |
| hangon.llc    | available | $19.99    | —             | 82             | 6      | 7      | name.com        |
| pierogi.llc   | available | $19.99    | —             | 82             | 7      | 7      | name.com        |
| stirup.llc    | available | $19.99    | —             | 82             | 3      | 7      | name.com        |
| getlife.llc   | available | $19.99    | —             | 80             | 5      | 8      | name.com        |
| Snickers.llc  | available | $54.98    | —             | 80             | 10     | 8      | namecheap       |
| shortcuts.llc | available | $19.99    | —             | 48             | 41     | 10     | name.com        |
| wallet.llc    | resell    | —         | —             | 74             | 55     | 6      | Dynadot Inc     |
| regions.llc   | premium   | $2,500    | —             | 64             | 59     | 7      | name.com        |
| robots.llc    | resell    | —         | —             | 62             | 47     | 6      | Spaceship, Inc. |
| cars.llc      | premium   | $1,250    | —             | 66             | 47     | 4      | name.com        |
| sites.llc     | available | $19.99    | —             | 53             | 26     | 5      | name.com        |
| stories.llc   | resell    | —         | —             | 58             | 36     | 7      | Dynadot Inc     |
| Ryan.llc      | premium   | $700      | $700          | 60             | 44     | 4      | namecheap       |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,375 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/llc?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_llc_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/llc?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_llc_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_llc_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .llc domains. The set includes direct generics such as tips.llc and finals.llc, action-oriented words like getup.llc, and more distinctive terms such as matcha.llc. For founders, the main question is whether the word is easy to remember, easy to say, and specific enough to support a business identity. For investors, the focus is whether the term has clear commercial meaning and a sensible entry price. With a median ask of $108.92, price discipline matters less than name quality, but renewal economics and trademark exposure still deserve a close look before choosing.

- One-word .llc names with broad commercial positioning
- Median ask is $108.92 across 11,375 domains
- Favor words that are clear, memorable, and easy to say
- Check trademark risk before buying category terms

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .LLC One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LLC page](https://unique.domains/domains/tld/llc?utm_source=github&utm_medium=referral&utm_campaign=repo_llc_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_llc_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_llc_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_llc_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
