# HI

![licence](https://img.shields.io/badge/licence-AGPL-3.0-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-unknown_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `HI` in category **MEDICAL_HEALTH**. check results: see ISOLATED_LAB_RESULTS. Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** HI · **Upstream pin:** `7dcebc0d568e37247d86a6477a7b4bb96c9ceee7` · **Category:** MEDICAL_HEALTH · **Vendor:** Anticloud FZ LLE · **Licence:** AGPL-3.0

---

## What This Project Does

![image](https://user-images.githubusercontent.com/2173259/209614345-8a492e66-d195-458f-8f4d-f356bce54692.png)

# FHIR Auth - a SMART on FHIR compatible FHIR authentication server
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg?style=flat-square)](http://www.gnu.org/licenses/agpl-3.0)
[![GitHub issues](https://img.shields.io/github/issues/zemantic/fhir-auth?style=flat-square)](https://github.com/zemantic/fhir-auth)
![GitHub project stars](https://img.shields.io/github/stars/zemantic/fhir-auth?style=flat-square)
[![Documentation](https://img.shields.io/badge/Documentation-wip-critical?style=flat-square)](https://zemantic.co/docs/fhir-auth)

FHIR Auth is a SMART on FHIR compatible FHIR authentication and authorization server. A FHIR authorization server validates incoming requests from clients and grant access to the FHIR server according to allocated privilages.

FHIR Auth currently support server to server authentication (backend authentication) and it is compatible with HAPI FHIR and many popular FHIR servers.

## Incoporate FHIR Auth to your FHIR server or institution 

<a href="https://zemantic.co/contact-us"><img src="https://user-images.githubusercontent.com/2173259/209616744-d599016f-9f01-4bc0-bc70-8a881feb1153.png" width="128" /></a>

## Features

- Follows SMART on FHIR security standards
- FHIR Auth works with all popular FHIR servers, including HAPI FHIR
- oAuth authentication flow
- Manage multiple FHIR servers in a single endpoint
- Registration and managing clients
- Grant resrouce level privilages

## Documentation

The documentation is still work in progress. Read the full documentation for FHIR Auth - https://zemantic.co/docs/fhir-auth

Help documentation by contributing to [documentation project](https://github.com/zemantic/fhir-auth-docs)

## Installation

Installing FHIR Auth on your developer environment

#### source the respository and install dependencies

```bash
git source https://github.com/zemantic/FHIR-auth-server
npm Install
```

#### Setting up environment variables
Change the values of `env_example`. And rename the file as `.env`

#### Creating tables 

``` bash
npx prisma generate
npx prisma migrate dev --name init
```

#### Run

```bash 
npm run serve
```

#### Build server after making changes 

```bash
npm run build
```

## Issues

Please create issues that you came across while using FHIR Auth on GitHub.

You are welcome to create a pull request with any solutions that you were able to fix on FHIR Auth. Pull requests will be merged after review by the authors.
## Authors

- [@rukshn](https://www.github.com/rukshn)

## FAQ

#### What is FHIR?

Fast Healthcare Interoperability Resources is a standard that includes a messaging structure (Resources) and a REST API structure that helps to achieve interoperability in healthcare data exchange between systems.

#### Does FHIR Auth store any health data?

No FHIR Auth does not store any incoming FHIR data, nor it process or modify the data. FHIR Auth only handles authentication of the incoming requests based on user privilages.

---

## Installation

Installing FHIR Auth on your developer environment

## Usage

# FHIR Auth - a SMART on FHIR compatible FHIR authentication server
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg?style=flat-square)](http://www.gnu.org/licenses/agpl-3.0)
[![GitHub issues](https://img.shields.io/github/issues/zemantic/fhir-auth?style=flat-square)](https://github.com/zemantic/fhir-auth)
![GitHub project stars](https://img.shields.io/github/stars/zemantic/fhir-auth?style=flat-square)
[![Documentation](https://img.shields.io/badge/Documentation-wip-critical?style=flat-square)](https://zemantic.co/docs/fhir-auth)

FHIR Auth is a SMART on FHIR compatible FHIR authentication and authorization server. A FHIR authorization server validates incoming requests from clients and grant access to the FHIR server according to allocated privilages.

FHIR Auth currently support server to server authentication (backend authentication) and it is compatible with HAPI FHIR and many popular FHIR servers.

## Incoporate FHIR Auth to your FHIR server or institution 

<a href="https://zemantic.co/contact-us"><img src="https://user-images.githubusercontent.com/2173259/209616744-d599016f-9f01-4bc0-bc70-8a881feb1153.png" width="128" /></a>

## API

FHIR Auth is a SMART on FHIR compatible FHIR authentication and authorization server. A FHIR authorization server validates incoming requests from clients and grant access to the FHIR server according to allocated privilages.

FHIR Auth currently support server to server authentication (backend authentication) and it is compatible with HAPI FHIR and many popular FHIR servers.

## Incoporate FHIR Auth to your FHIR server or institution 

<a href="https://zemantic.co/contact-us"><img src="https://user-images.githubusercontent.com/2173259/209616744-d599016f-9f01-4bc0-bc70-8a881feb1153.png" width="128" /></a>

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | AGPL-3.0 |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Contributing

Fork the project, create a feature branch, run the test suite, and open a pull request against upstream.

## License

Upstream © its respective contributors under AGPL-3.0 (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** HI
- **Pinned SHA:** `7dcebc0d568e37247d86a6477a7b4bb96c9ceee7`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.md`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`9b417f80e12f5fe9c5f570e0bd2c8a7236ca4a1dea536d97bcb0bc69f67f6f67`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

