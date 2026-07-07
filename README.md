# Available .LLC One-Word Domains (11,379)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C379%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .llc one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,379 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,379 domains · **Median ask:** $192.74 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-07
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

- `llc.csv`, public CSV extract (1,000 rows)
- `llc.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/llc-oneword-domains/main/llc.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar         |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------- |
| hum.llc          | available | $19.99    | —             | high           | low    | 3      | name.com          |
| searchengine.llc | resell    | $19.99    | —             | high           | low    | 13     | GoDaddy.com, LLC  |
| Ava.llc          | premium   | $625      | —             | high           | medium | 3      | name.com          |
| ive.llc          | available | $19.99    | —             | medium         | low    | 3      | name.com          |
| trap.llc         | resell    | —         | —             | medium         | low    | 4      | Dynadot Inc       |
| cap.llc          | premium   | $625      | —             | high           | low    | 3      | name.com          |
| xvi.llc          | available | $19.99    | $54.99        | medium         | low    | 3      | name.com          |
| drone.llc        | resell    | —         | —             | high           | medium | 5      | Sav.com, LLC - 45 |
| des.llc          | premium   | $1,875    | —             | high           | low    | 3      | name.com          |
| base.llc         | available | $19.99    | —             | medium         | medium | 4      | name.com          |
| ideal.llc        | resell    | —         | —             | high           | low    | 5      | Sav.com, LLC - 49 |
| dot.llc          | premium   | $3,125    | —             | high           | medium | 3      | name.com          |
| bump.llc         | available | $19.99    | —             | medium         | low    | 4      | name.com          |
| radar.llc        | resell    | —         | —             | medium         | low    | 5      | Dynadot Inc       |
| ear.llc          | premium   | $302.50   | $302.50       | high           | low    | 3      | namesilo          |
| comp.llc         | available | $19.99    | $54.99        | medium         | low    | 4      | name.com          |
| short.llc        | resell    | —         | —             | high           | low    | 5      | GoDaddy.com, LLC  |
| end.llc          | premium   | $1,107    | $1,107        | high           | low    | 3      | namesilo          |
| died.llc         | available | $19.99    | —             | medium         | low    | 4      | name.com          |
| sweet.llc        | resell    | —         | —             | high           | low    | 5      | Sav.com, LLC - 29 |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,379 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/llc?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_llc_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/llc?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_llc_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_llc_oneword_domains&utm_content=related_pricing)

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

This set covers 11,379 one-word .LLC domain names, each a single dictionary or coined word paired with the .LLC extension. The median ask across the set sits near $193, putting most entries within reach for a quick pickup or a first-look comparison. Names range from everyday words like forces.llc and girls.llc to compact phrases such as letitbe.llc and hangon.llc, giving founders a shortlist of ownable, easy-to-say options and giving investors a wide, single-extension pool to price-check for spread and coverage.

- 11,379 one-word .LLC domain names in this set
- Median ask near $193 across the full list
- One-word format: short, spoken-friendly, easy to spell
- Updated daily to reflect current listings

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .LLC One-Word Domains*. Version 2026-07-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LLC page](https://unique.domains/domains/tld/llc?utm_source=github&utm_medium=referral&utm_campaign=repo_llc_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_llc_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_llc_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_llc_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
