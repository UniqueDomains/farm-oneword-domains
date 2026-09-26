# Available .FARM One-Word Domains (20,675)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-20%2C675%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .farm one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **20,675 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 20,675 domains · **Median ask:** $11.23 · **High-demand under $2,500:** 3

**Last updated:** 2026-09-26
**Canonical page:** `https://unique.domains/domains/tld/farm`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/farm?utm_source=github&utm_medium=referral&utm_campaign=repo_farm_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./farm.csv">CSV</a> / <a href="./farm.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_farm_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_farm_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .FARM search](https://unique.domains/domains/tld/farm?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_farm_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .FARM search](https://unique.domains/domains/tld/farm?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_farm_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_farm_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .FARM one-word domain catalog.

### Files

- `farm.csv`, public CSV extract (1,000 rows)
- `farm.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/farm-oneword-domains/main/farm.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain       | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                 |
| ------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------------- |
| ado.farm     | available | $15.99    | $38.99        | high           | low    | 3      | namesilo                                                  |
| trip.farm    | resell    | $49.98    | —             | high           | low    | 4      | Spaceship, Inc.                                           |
| git.farm     | premium   | $118.80   | $118.80       | high           | medium | 3      | namesilo                                                  |
| alp.farm     | available | $15.99    | $38.99        | high           | low    | 3      | namesilo                                                  |
| advance.farm | resell    | $13.99    | $50.99        | high           | low    | 7      | Spaceship, Inc.                                           |
| dads.farm    | premium   | $118.80   | $118.80       | high           | low    | 4      | namesilo                                                  |
| azo.farm     | available | $4.98     | $49.98        | high           | low    | 3      | namecheap                                                 |
| student.farm | resell    | $49.98    | —             | high           | low    | 7      | Spaceship, Inc.                                           |
| irving.farm  | premium   | $118.80   | $118.80       | medium         | low    | 6      | namesilo                                                  |
| bai.farm     | available | $4.98     | $49.98        | high           | low    | 3      | namecheap                                                 |
| trinity.farm | resell    | $13.99    | $50.99        | high           | medium | 7      | Spaceship, Inc.                                           |
| wooden.farm  | premium   | $242      | $242          | high           | low    | 6      | namesilo                                                  |
| bpi.farm     | available | $15.99    | $38.99        | high           | low    | 3      | namesilo                                                  |
| gay.farm     | resell    | —         | —             | high           | medium | 3      | Dynadot Inc                                               |
| chicago.farm | premium   | $118.80   | $118.80       | high           | low    | 7      | namesilo                                                  |
| dis.farm     | available | $15.99    | $38.99        | high           | low    | 3      | namesilo                                                  |
| beer.farm    | resell    | —         | —             | high           | low    | 4      | Porkbun LLC                                               |
| detroit.farm | premium   | $118.80   | $118.80       | high           | low    | 7      | namesilo                                                  |
| dye.farm     | available | $13.99    | —             | high           | low    | 3      | name.com                                                  |
| care.farm    | resell    | —         | —             | high           | medium | 4      | Global Domains International, Inc. DBA DomainCostClub.com |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 20,675 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 3 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/farm?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_farm_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/farm?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_farm_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_farm_oneword_domains&utm_content=related_pricing)

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
- `status_verified_at`, When status was last established against the registry. Null means never checked.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

These are one-word domain names using the .farm extension, spanning everyday words like out.farm, half.farm, and beauty.farm. With a median asking price near $16.50 across 11,272 names, this set favors short, memorable words over premium status. The .farm extension carries an agricultural, homegrown connotation that suits food, lifestyle, and community-driven brands, making it worth comparing against more common extensions before you commit.

- 11,272 one-word .farm domains in this set
- Median asking price near $16.50
- Short, brandable names like half.farm and quiet.farm
- Farm-themed extension fits food and lifestyle brands

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The snapshot date above is when this file was written, not when each row was checked. Read `status_verified_at` for that: a name whose status was last established months ago is exported with its real date rather than the snapshot's.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .FARM One-Word Domains*. Version 2026-09-26. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .FARM page](https://unique.domains/domains/tld/farm?utm_source=github&utm_medium=referral&utm_campaign=repo_farm_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_farm_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_farm_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_farm_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
