# REDMIX Archival Cards

**Metadata schemas for archival description developed within the ERC CoG 2023 Project REDMIX – *Unpacking Mixedness for an Inclusive History of the Red Sea, 1800s–2000s***

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

## Overview

This repository contains the metadata schemas and controlled vocabularies developed for the REDMIX digital archive. The schemas are designed to describe five core entities within the archival domain: archival levels, archival resources, creators, holding institutions, and persons. They are grounded in international standards (ISAD(G), ISAAR(CPF), ISDIAH) and tailored to the specific research needs of the REDMIX project, which investigates mixed-ancestry communities in the Red Sea region between the 1800s and 2000s.

## Repository Structure

```
REDMIX_Archival-Cards/
│
├── Archival cards/
│   └── archival_cards.csv                      # Machine-readable metadata schemas for all five cards (CSV format)
│
├── Vocabularies/
│   └── [vocabulary_files].csv                   # Controlled vocabularies for specific fields (CSV format)
│
├── LICENSE.md                                    # CC-BY-4.0 license
└── README.md                                     # This file
```

## The Five Archival Cards

The REDMIX metadata schema is built upon five distinct cataloguing cards:  

| Card | Acronym | Description |
|------|---------|-------------|
| **Archival Levels** | AL | Describes higher-level archival units such as fonds, sub-fonds, series, and sub-series |
| **Archival Resource** | AR | Describes the smallest archival units: files, items, or portions of items |
| **Creator** | CR | Describes the entity (person, family, or organisation) that created the archival materials |
| **Holding Institution** | HO | Describes the entity (person, family, or organisation) holding the archival materials |
| **Person** | PE | Describes individuals, including genealogical information, ethnicity, and other biographical details |

## Standards Reference

The schemas are aligned with the following international standards:

- **ISAD(G)** – General International Standard Archival Description (for AL and AR cards)
- **ISAAR(CPF)** – International Standard Archival Authority Records for Corporate Bodies, Persons and Families (for CR and PE cards)
- **ISDIAH** – International Standard for Describing Institutions with Archival Holdings (for HO cards)
- **British Museum Material Culture Ethnography Metadata Schema** – for ethnographic description (PE card)

## File Formats

### CSV Files (Machine-readable)
The `archival_cards.csv` file and vocabulary files are provided in CSV format for easy integration with databases, parsing scripts, and data processing workflows. Each field is defined according to the parameters described in the REDMIX project publications.

### XLSX Files (Human-readable)
For enhanced readability with color coding and formatting, human-readable versions of the metadata schemas are available at the following links:
- `AL Card – Archival Levels*`: [Link](https://docs.google.com/spreadsheets/d/1THmn-YyWimjLt3A9GzDrDqkLnrtT3Ljb/edit?usp=sharing&ouid=112165026692624440677&rtpof=true&sd=true)
- `AR Card – Archival Resource*`: [Link](https://docs.google.com/spreadsheets/d/1DGmvUvNPbsgTtOwzQE0zhMSWtVZmzS4h/edit?usp=sharing&ouid=112165026692624440677&rtpof=true&sd=true)
- `CR Card – Creator*`: [Link](https://docs.google.com/spreadsheets/d/1FAh5tOIz33ZfG5tF_lLbzfRkWc8r_yX_/edit?usp=sharing&ouid=112165026692624440677&rtpof=true&sd=true) 
- `HO Card – Holding Institution*`: [Link](https://docs.google.com/spreadsheets/d/1wR569MAAmBR8Ibpn1a4yEceNgxt4bplo/edit?usp=sharing&ouid=112165026692624440677&rtpof=true&sd=true)
- `PE Card – Person*`: [Link](https://docs.google.com/spreadsheets/d/1kKZYwFCLb4pHj-W6alU9JrVE6IH-Extg/edit?usp=sharing&ouid=112165026692624440677&rtpof=true&sd=true)
These files maintain the same structure as the CSV versions but offer improved visual navigation for cataloguers and researchers.

## Vocabularies

The `Vocabularies/` folder contains controlled vocabularies developed for specific fields. Vocabularies are identified by self-explanatory strings:
- `VOC_AL_*` – Vocabularies used exclusively in the AL card
- `VOC_AR_*` – Vocabularies used exclusively in the AR card
- `VOC_CR_*` – Vocabularies used exclusively in the CR card
- `VOC_HO_*` – Vocabularies used exclusively in the HO card 
- `VOC_PE_*` – Vocabularies used exclusively in the PE card
- Shared vocabularies (e.g., `VOC_LANGUAGE`) are used across multiple cards

## License

This work is licensed under a **Creative Commons Attribution 4.0 International License (CC BY 4.0)**. You are free to share and adapt the material for any purpose, provided that appropriate credit is given. See the [LICENSE.md](LICENSE.md) file for details.

## How to Cite

If you use these metadata schemas in your research, please cite:

> Pasciuto, Tiziana & Talamini, Stefano. (2026). REDMIX Archival Cards: Metadata Schemas for the REDMIX Digital Archive (Version 1.0) [Data set]. GitHub. https://github.com/TizianaPascuito/REDMIX_Archival-Cards

## Contact

For questions, feedback, or collaboration inquiries:

- **Tiziana Pasciuto**: tiziana.pasciuto@unito.it  
- **Stefano Talamini**: stefano.talamini@unito.it  

University of Turin  
ERC CoG 2023 Project REDMIX

## Funding

Funded by the European Union. Views and opinions expressed are however those of the author(s) only and do not necessarily reflect those of the European Union or the European Research Council Executive Agency. Neither the European Union nor the granting authority can be held responsible for them. This work is supported by ERC Grant REDMIX Agreement 101124725.

---

**Last updated:** July 2026
