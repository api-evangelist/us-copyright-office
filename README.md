# US Copyright Office (us-copyright-office)

The US Copyright Office is a government agency responsible for administering and enforcing copyright laws in the United States. The office registers and documents copyright claims, maintains the Copyright Public Records System with 22 million registration records, provides bulk data downloads for research, and administers licensing and DMCA programs. The Copyright Office is modernizing its systems through the Enterprise Copyright System (ECS) program.

**URL:** [https://www.copyright.gov/](https://www.copyright.gov/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Copyright, Federal Government, Intellectual Property, Open Data

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-03

## APIs

### Copyright Public Records System

The Copyright Public Records System (CPRS) provides access to U.S. copyright registration and recordation data with advanced search capabilities and improved interfaces. Replaced the Online Public Catalog in June 2025 and contains records from 1978 onward.

**Human URL:** [https://publicrecords.copyright.gov/](https://publicrecords.copyright.gov/)

#### Tags:

 - Copyright, Public Records, Federal Government

#### Properties

- [Documentation](https://publicrecords.copyright.gov/)
- [Getting Started](https://www.copyright.gov/public-records/)
- [JSONSchema - Copyright Registration Schema](json-schema/us-copyright-office-registration-schema.json)
- [JSONSchema - Copyright Recordation Schema](json-schema/us-copyright-office-recordation-schema.json)

### Copyright Bulk Datasets

Bulk download of approximately 22 million U.S. copyright registration records from January 1, 1978 to June 27, 2025. Available in raw unparsed MARC, parsed CSV, and tabular CSV formats.

**Human URL:** [https://www.copyright.gov/economic-research/usco-datasets/](https://www.copyright.gov/economic-research/usco-datasets/)

#### Tags:

 - Copyright, Bulk Data, Federal Government, Open Data

#### Properties

- [Documentation](https://www.copyright.gov/economic-research/usco-datasets/)
- [DataAPI - Bulk Data Download Portal](https://data.copyright.gov)

### Licensing Documents Search

Searchable database of compulsory license statements of account and royalty payment records filed with the Copyright Office.

**Human URL:** [https://licensing.copyright.gov/lds/](https://licensing.copyright.gov/lds/)

#### Tags:

 - Copyright, Licensing, Federal Government

#### Properties

- [Documentation](https://licensing.copyright.gov/lds/)

### DMCA Designated Agent Directory

Searchable directory of Online Service Providers (OSPs) that have registered DMCA designated agents with the U.S. Copyright Office per Section 512 of the Digital Millennium Copyright Act.

**Human URL:** [https://www.copyright.gov/dmca-directory/](https://www.copyright.gov/dmca-directory/)

#### Tags:

 - Copyright, DMCA, Federal Government

#### Properties

- [Documentation](https://www.copyright.gov/dmca-directory/)
- [JSONSchema - DMCA Designated Agent Schema](json-schema/us-copyright-office-dmca-agent-schema.json)

## Common Properties

- [Website](https://www.copyright.gov/)
- [Documentation - Search Copyright Records](https://www.copyright.gov/public-records/)
- [DataAPI - Bulk Data Downloads](https://data.copyright.gov)
- [Getting Started - Register Your Work](https://www.copyright.gov/registration/)
- [FAQ](https://www.copyright.gov/eco/faq.html)
- [Terms of Service](https://www.copyright.gov/en/about/policies/)
- [Contact the Copyright Office](https://www.copyright.gov/about/contact/)
- [Vocabulary](vocabulary/us-copyright-office-vocabulary.yml)
- [JSON-LD Context](json-ld/us-copyright-office-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Copyright Registration Bulk Data | Approximately 22 million copyright registration records from 1978 to present available for bulk download in MARC, parsed CSV, and tabular CSV formats. |
| Copyright Public Records System (CPRS) | Advanced search system for copyright registration and recordation data, replacing the Online Public Catalog in June 2025. |
| Online Registration (eCO) | Electronic Copyright Office registration system for submitting new copyright registration applications online. |
| Licensing Documents Search | Searchable database of compulsory license statements of account and royalty payments filed with the Copyright Office. |
| DMCA Designated Agent Directory | Directory of online service providers that have registered DMCA designated agents per Section 512 of the DMCA. |
| Enterprise Copyright System Modernization | Ongoing modernization of all Copyright Office IT systems into a unified, interconnected digital infrastructure. |

## Use Cases

| Name | Description |
|------|-------------|
| Copyright Research and Due Diligence | Searching copyright records to determine ownership, registration status, and rights information for works before licensing or use. |
| Bulk Data Analysis and Research | Downloading bulk copyright registration datasets for academic research, legal analysis, or statistical studies. |
| DMCA Compliance | Looking up DMCA designated agents for online service providers to send takedown notices per Section 512 requirements. |
| Licensing Compliance Verification | Searching licensing documents to verify statutory license compliance and royalty payment records. |
| Orphan Works Identification | Using copyright records to research ownership of works when rights holders cannot be identified. |

## Integrations

| Name | Description |
|------|-------------|
| Library of Congress | Copyright Office is a department of the Library of Congress; data integrates with LC catalog systems and MARC format records. |
| U.S. Patent and Trademark Office | Collaborates with USPTO on intellectual property policy, including joint AI and copyright/patent studies. |

## Artifacts

Machine-readable data specifications organized by format.

### JSON Schema

- [Copyright Registration Schema](json-schema/us-copyright-office-registration-schema.json)
- [Copyright Recordation Schema](json-schema/us-copyright-office-recordation-schema.json)
- [DMCA Designated Agent Schema](json-schema/us-copyright-office-dmca-agent-schema.json)

### JSON Structure

- [Copyright Registration Structure](json-structure/us-copyright-office-registration-structure.json)
- [Copyright Recordation Structure](json-structure/us-copyright-office-recordation-structure.json)
- [DMCA Designated Agent Structure](json-structure/us-copyright-office-dmca-agent-structure.json)

### JSON-LD

- [US Copyright Office Context](json-ld/us-copyright-office-context.jsonld)

### Examples

- [Copyright Registration Example](examples/us-copyright-office-registration-example.json)
- [Copyright Recordation Example](examples/us-copyright-office-recordation-example.json)
- [DMCA Designated Agent Example](examples/us-copyright-office-dmca-agent-example.json)

## Vocabulary

- [US Copyright Office Vocabulary](vocabulary/us-copyright-office-vocabulary.yml) — Unified taxonomy mapping 4 resources, 4 actions, 0 workflows, and 4 personas across copyright registration, recordation, DMCA, and bulk data dimensions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
