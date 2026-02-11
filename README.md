# Internet Use for Pregnancy-Related Information — Mogadishu, Somalia

## Background and Objective

Somalia faces persistent maternal health gaps alongside expanding digital connectivity. This dataset accompanies the study *"Internet use for pregnancy-related information and its correlates among women attending antenatal care in Mogadishu, Somalia,"* which assessed the prevalence, patterns, and sociodemographic correlates of internet use for pregnancy-related information among antenatal clinic attendees.

## Dataset Description

| Item | Detail |
|---|---|
| **Setting** | Six antenatal clinics (public and private), Banaadir region, Mogadishu, Somalia |
| **Period** | February – May 2025 |
| **Design** | Analytical cross-sectional study |
| **Sample size** | 422 pregnant women (18–49 years, literate, attending ANC) |
| **Data collection** | Structured, self-administered questionnaire |

## Outcome Variable

The primary outcome is **internet use for pregnancy-related information during the current pregnancy** (`internet`: Yes/No). Among the 422 participants, 78.2 % reported using the internet for this purpose, predominantly via social media, with daily use being the most common frequency.

## Variables Overview

The dataset contains 34 variables covering:

- **Sociodemographics** — age, education, employment, income, state of origin
- **Obstetric characteristics** — gravida, number of living children, trimester, reported fetal gender
- **Information sources** — internet, healthcare providers, family, friends, books/magazines, television
- **Educational activity** — participation and venue
- **Internet-use patterns** (among users) — frequency, access method, purpose, topic searched
- **Self-reported health problems** — anemia, gestational diabetes, heartburn, low back pain, morning sickness, vomiting, others

See [`data_dictionary.csv`](data_dictionary.csv) for a complete variable-level description.

## File Structure

```
├── data/
│   └── internet use data.csv   # De-identified dataset (N = 422)
├── data_dictionary.csv          # Variable names, descriptions, and types
├── LICENSE                      # MIT license with data-use note
├── .gitignore
└── README.md
```

## Ethical Approval and Privacy

- **IRB approval:** SIMAD University, Mogadishu (Ref. 2025/SU-IRB/FMHS/P007; 30 January 2025).
- **Informed consent:** Written informed consent was obtained from all participants.
- **De-identification:** The dataset contains no direct identifiers. 
- **Declaration of Helsinki:** All procedures adhered to recognized ethical principles.

## Citation

If you use this dataset, please cite:

> Ahmed, M. M., Ibrahim, L. M., Elmi, R. A., Othman, Z. K., Branda, F., Okesanya, O. J., Adebayo, U. O., Musa, S. S., Elmi, A. H., Ali, A. S., & Lucero-Prisno, D. E. III. Internet use for pregnancy-related information and its correlates among women attending antenatal care in Mogadishu, Somalia. *[Journal Name]*, *[Year]*. https://doi.org/[DOI]

## License

This repository is released under the [MIT License](LICENSE). The dataset is provided for research and academic use; please cite the original study.

## Contact

Mohamed Mustaf Ahmed — momustafahmed@simad.edu.so
