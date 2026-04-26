# Available .VISION One-Word Domains (11,104)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C104%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .vision one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,104 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,104 domains

**Last updated:** 2026-04-26  
**Canonical page:** `https://unique.domains/domains/tld/vision`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/vision?utm_source=github&utm_medium=referral&utm_campaign=repo_vision_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./vision.csv">CSV</a> / <a href="./vision.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_vision_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_vision_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .VISION search](https://unique.domains/domains/tld/vision?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_vision_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .VISION search](https://unique.domains/domains/tld/vision?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_vision_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_vision_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .VISION one-word domain catalog.

### Files

- `vision.csv` — public CSV extract (1,000 rows)
- `vision.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/vision-oneword-domains/main/vision.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar         |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------- |
| WiFi.vision     | available | $59.98    | —             | 83             | 37     | 5      | namecheap         |
| web.vision      | resell    | —         | —             | 72             | 61     | 3      | Porkbun LLC       |
| Ryan.vision     | premium   | $138.60   | $138.60       | 60             | 44     | 4      | namecheap         |
| letsgo.vision   | available | $9.99     | —             | 57             | 31     | 7      | name.com          |
| coins.vision    | resell    | —         | —             | 56             | 41     | 5      | Dynadot Inc       |
| partners.vision | premium   | $123.75   | —             | 61             | 32     | 8      | name.com          |
| maps.vision     | available | $9.99     | —             | 56             | 31     | 4      | name.com          |
| tokens.vision   | resell    | —         | —             | 51             | 36     | 6      | Dynadot Inc       |
| William.vision  | premium   | $92.40    | $92.40        | 74             | 31     | 7      | namecheap         |
| quotes.vision   | available | $9.99     | —             | 58             | 29     | 6      | name.com          |
| audio.vision    | resell    | —         | —             | 76             | 35     | 5      | Porkbun LLC       |
| systems.vision  | premium   | $123.75   | —             | 46             | 27     | 7      | name.com          |
| dogs.vision     | available | $9.99     | —             | 76             | 28     | 4      | name.com          |
| brands.vision   | resell    | —         | —             | 62             | 28     | 6      | Sav.com, LLC - 20 |
| toys.vision     | premium   | $78.54    | $78.54        | 60             | 24     | 4      | namesilo          |
| backyard.vision | available | $9.99     | —             | 80             | 27     | 9      | name.com          |
| triangle.vision | resell    | —         | —             | 66             | 26     | 8      | Sav.com, LLC - 6  |
| products.vision | premium   | $123.75   | —             | 60             | 23     | 8      | name.com          |
| doctors.vision  | available | $9.99     | —             | 56             | 26     | 7      | name.com          |
| flights.vision  | premium   | $118.80   | $118.80       | 61             | 22     | 7      | namesilo          |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 1,000-row public sample | 11,104 live domains                              |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/vision?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_vision_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/vision?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_vision_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_vision_oneword_domains&utm_content=related_pricing)

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

> Unique Domains. *Available .VISION One-Word Domains*. Version 2026-04-26. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .VISION page](https://unique.domains/domains/tld/vision?utm_source=github&utm_medium=referral&utm_campaign=repo_vision_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_vision_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_vision_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_vision_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
