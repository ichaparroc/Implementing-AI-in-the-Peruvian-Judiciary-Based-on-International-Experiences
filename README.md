# Judicial AI Initiatives: Comparative Coding Dataset

This repository contains the dataset supporting the article *A Roadmap for Implementing Artificial Intelligence in the Peruvian Judiciary Based on International Experiences* (under review).

It records the coding of thirteen judicial artificial intelligence initiatives: four in Peru and nine in Spain, France, Argentina, Colombia, Brazil and Singapore. All data were derived from official documents of judicial bodies and regulatory authorities and from academic publications available in the public domain. Documents were consulted up to October 24, 2026.

## Files

| File | Content |
|---|---|
| `judicial_ai_initiatives_dataset.xlsx` | Workbook with three sheets: `initiatives`, `functional_coding` and `codebook`. |
| `csv/initiatives.csv` | One row per initiative: country, institution, documented function, source date, status, scope, type of evidence and source keys. |
| `csv/functional_coding.csv` | Matrix of initiatives by function (eight categories). |
| `csv/codebook.csv` | Definition of every variable and its permitted values. |

The CSV files are UTF-8 encoded and contain the same data as the workbook.

## Coding rules

- The unit of analysis is the judicial initiative. The French pseudonymisation engine and its review through LABEL are treated as one initiative, as are the translation and summarisation services of Singapore's Small Claims Tribunals. Athos and STJ Logos are kept separate.
- Functional categories are not mutually exclusive. Document classification and the legal assessment of claims are coded separately.
- A function not mentioned in the selected sources is coded as `Insufficient information`, not as absent.
- A source date is not interpreted as the creation date of a system unless the source states it, and a past deployment is not taken as evidence of continued operation.
- The `source_keys` column matches the citation keys in the article's reference list, where full bibliographic details and URLs are given.

## License

This dataset is released under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

## Citation

Citation details will be added once the article is published.
