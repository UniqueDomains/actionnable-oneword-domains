# Actionable One-Word Domains (~2,510,000)

~2,510,000 names in this list today, refreshed every night.

Live page: [unique.domains/domains/actionable](https://unique.domains/domains/actionable?utm_source=github&utm_medium=referral&utm_campaign=repo_actionnable_oneword_domains&utm_content=top_page)

<img alt="updated: daily" src="https://img.shields.io/badge/updated-daily-0969da"> <img alt="extract: 1,000 rows" src="https://img.shields.io/badge/extract-1%2C000%20rows-8250df"> <img alt="formats: CSV | JSON" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b"> <img alt="licence: CC BY 4.0" src="https://img.shields.io/badge/licence-CC%20BY%204.0-2ea44f">

## Download

- [actionnable.csv](https://github.com/UniqueDomains/actionnable-oneword-domains/raw/main/actionnable.csv), 1,000 rows
- [actionnable.json](https://github.com/UniqueDomains/actionnable-oneword-domains/raw/main/actionnable.json), 1,000 rows

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/actionnable-oneword-domains/main/actionnable.csv")
print(df.head())
```

## Sample rows

The first 20 rows of the file, in the file's order.

| domain               | status    | purchase_price | renewal_price | attractiveness | demand | length |
| -------------------- | --------- | -------------- | ------------- | -------------- | ------ | ------ |
| ripen.click          | premium   | $72.65         | $103.70       | high           | low    | 5      |
| fandango.im          | available | $4.18          | $6.73         | high           | low    | 8      |
| souffle.win          | available | $4.48          | $5.55         | high           | low    | 7      |
| befit.win            | premium   | $448           | $53.92        | high           | low    | 5      |
| jawbone.supply       | available | $25.99         | $25.99        | high           | low    | 7      |
| tind.coach           | available | $10.55         | $62.30        | high           | low    | 4      |
| substantiate.recipes | available | $60.20         | $60.20        | high           | low    | 12     |
| handball.singles     | premium   | $33.50         | $34.36        | high           | low    | 8      |
| justify.wine         | available | $9.50          | $59.99        | high           | low    | 7      |
| bottleneck.vip       | premium   | $224           | $17.70        | medium         | low    | 10     |
| categorise.directory | available | $8.99          | $32.99        | high           | low    | 10     |
| alleviate.organic    | available | $17            | —             | high           | low    | 9      |
| willey.industries    | available | $45.99         | $45.99        | medium         | low    | 6      |
| lask.lease           | available | $58.98         | $73.98        | high           | low    | 4      |
| dingo.equipment      | available | $22.20         | $22.20        | high           | low    | 5      |
| rescale.forex        | available | $10.55         | $83           | high           | low    | 7      |
| neutralize.ac        | available | $25.88         | $46.58        | high           | low    | 10     |
| decrease.guitars     | available | $100.20        | $100.20       | medium         | low    | 8      |
| sheath.bar           | available | $3.49          | $54.99        | high           | low    | 6      |
| godfather.casa       | available | $1.54          | $10.81        | high           | low    | 9      |

## What is in the data

- `domain`: Fully qualified domain name.
- `status`: Current acquisition state for the domain in the public extract.
- `purchase_price`: Visible purchase price when available.
- `renewal_price`: Visible renewal price when available.
- `attractiveness`: Public composite naming band used as a decision-support signal.
- `demand`: Public buyer-pressure band when available.
- `length`: Character count without the TLD.
- `registrar`: Registrar name when known.
- `created_at`: Creation timestamp when known.
- `expires_at`: Expiry timestamp when known.

Types and formats: [DATA_DICTIONARY.md](./DATA_DICTIONARY.md).

## Methodology

- The files hold 1,000 rows of the ~2,510,000 names in the live list today.
- Every row is a one-word domain name.
- Status and prices are the last ones Unique Domains stored for each name, not a reading taken on the day of the rebuild.
- The live count marked with a tilde is estimated from a 2 percent page sample of the catalog and rounded to three significant digits; it moves between nights. The rows in the files are real rows.

More in [METHODOLOGY.md](./METHODOLOGY.md).

## Update policy

- The files are rebuilt every night from the same export.
- The snapshot is the day of the rebuild; each row's status is the last one stored, not a reading of that day.
- The files hold the public extract, not the whole live list.

## How to cite

> Unique Domains, Actionable One-Word Domains, https://unique.domains/domains/actionable, CC BY 4.0

Citation metadata: [CITATION.cff](./CITATION.cff). A DOI follows once Zenodo mints one.

## Related datasets

- [Every one-word domain](https://github.com/UniqueDomains/oneword-domains) (the hub)

One-word domains by ending:

- [.com](https://github.com/UniqueDomains/com-oneword-domains), [page](https://unique.domains/tld/com?utm_source=github&utm_medium=referral&utm_campaign=repo_actionnable_oneword_domains&utm_content=related_tld_page)
- [.ai](https://github.com/UniqueDomains/ai-oneword-domains), [page](https://unique.domains/tld/ai?utm_source=github&utm_medium=referral&utm_campaign=repo_actionnable_oneword_domains&utm_content=related_tld_page)
- [.io](https://github.com/UniqueDomains/io-oneword-domains), [page](https://unique.domains/tld/io?utm_source=github&utm_medium=referral&utm_campaign=repo_actionnable_oneword_domains&utm_content=related_tld_page)
- [.app](https://github.com/UniqueDomains/app-oneword-domains), [page](https://unique.domains/tld/app?utm_source=github&utm_medium=referral&utm_campaign=repo_actionnable_oneword_domains&utm_content=related_tld_page)
- [.co](https://github.com/UniqueDomains/co-oneword-domains), [page](https://unique.domains/tld/co?utm_source=github&utm_medium=referral&utm_campaign=repo_actionnable_oneword_domains&utm_content=related_tld_page)
- [.xyz](https://github.com/UniqueDomains/xyz-oneword-domains), [page](https://unique.domains/tld/xyz?utm_source=github&utm_medium=referral&utm_campaign=repo_actionnable_oneword_domains&utm_content=related_tld_page)

Lists:

- [Expired](https://github.com/UniqueDomains/expired-oneword-domains)
- [Expiring](https://github.com/UniqueDomains/expiring-oneword-domains)
- [Brandable](https://github.com/UniqueDomains/brandable-oneword-domains)
- [Short](https://github.com/UniqueDomains/short-oneword-domains)

Every ending Unique Domains tracks: [unique.domains/tld](https://unique.domains/tld?utm_source=github&utm_medium=referral&utm_campaign=repo_actionnable_oneword_domains&utm_content=related_hub).

## About Unique Domains

[Unique Domains](https://unique.domains/?utm_source=github&utm_medium=referral&utm_campaign=repo_actionnable_oneword_domains&utm_content=about) tracks one-word domain names across the endings people build on: which are free to register, what they cost to hold and what names of each ending sell for. The datasets in this organization are its public extracts, refreshed every night.

From code: the [Node.js SDK and CLI](https://github.com/UniqueDomains/nodejs) (`npm install @uniquedomains/sdk`), the [Python client](https://github.com/UniqueDomains/python) (`pip install uniquedomains`) and the [MCP server](https://github.com/UniqueDomains/mcp-server) for AI assistants, hosted at `https://mcp.unique.domains/mcp`.

Questions and corrections: `kai@unique.domains`
