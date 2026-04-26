# Available .PARTNERS One-Word Domains (11,167)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C167%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .partners one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,167 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,167 domains

**Last updated:** 2026-04-26  
**Canonical page:** `https://unique.domains/domains/tld/partners`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/partners?utm_source=github&utm_medium=referral&utm_campaign=repo_partners_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./partners.csv">CSV</a> / <a href="./partners.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_partners_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_partners_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .PARTNERS search](https://unique.domains/domains/tld/partners?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_partners_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .PARTNERS search](https://unique.domains/domains/tld/partners?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_partners_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_partners_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .PARTNERS one-word domain catalog.

### Files

- `partners.csv` — public CSV extract (1,000 rows)
- `partners.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/partners-oneword-domains/main/partners.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain               | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| -------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| coins.partners       | available | $13.99    | —             | 56             | 41     | 5      | name.com        |
| online.partners      | resell    | —         | —             | 70             | 62     | 7      | Spaceship, Inc. |
| homes.partners       | premium   | $250      | —             | 86             | 34     | 5      | name.com        |
| etc.partners         | available | $13.99    | —             | 58             | 34     | 3      | name.com        |
| quest.partners       | resell    | —         | —             | 74             | 45     | 5      | Porkbun LLC     |
| tips.partners        | premium   | $123.75   | —             | 80             | 26     | 4      | name.com        |
| William.partners     | available | $88.98    | —             | 74             | 31     | 7      | namecheap       |
| property.partners    | resell    | —         | —             | 76             | 39     | 8      | Porkbun LLC     |
| has.partners         | premium   | $123.75   | —             | 60             | 26     | 3      | name.com        |
| letsgo.partners      | available | $13.99    | —             | 57             | 31     | 7      | name.com        |
| designers.partners   | resell    | —         | —             | 72             | 15     | 9      | IONOS SE        |
| boats.partners       | premium   | $123.75   | —             | 52             | 24     | 5      | name.com        |
| spaces.partners      | available | $13.99    | —             | 54             | 30     | 6      | name.com        |
| flights.partners     | premium   | $78.54    | $78.54        | 61             | 22     | 7      | namesilo        |
| heroes.partners      | available | $13.99    | —             | 68             | 29     | 6      | name.com        |
| watches.partners     | premium   | $123.75   | —             | 84             | 19     | 7      | name.com        |
| gems.partners        | available | $13.99    | —             | 70             | 28     | 4      | name.com        |
| accountants.partners | premium   | $118.80   | $118.80       | 50             | 16     | 11     | namesilo        |
| pages.partners       | available | $13.99    | —             | 52             | 28     | 5      | name.com        |
| KFC.partners         | available | $88.98    | —             | 74             | 27     | 3      | namecheap       |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 1,000-row public sample | 11,167 live domains                              |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/partners?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_partners_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/partners?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_partners_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_partners_oneword_domains&utm_content=related_pricing)

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .PARTNERS One-Word Domains*. Version 2026-04-26. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .PARTNERS page](https://unique.domains/domains/tld/partners?utm_source=github&utm_medium=referral&utm_campaign=repo_partners_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_partners_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_partners_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_partners_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
