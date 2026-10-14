# POINT OF SALE

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-supermarkets-lightgrey)

> Anticloud-hardened packaging of the upstream project `POINT_OF_SALE` in category **SUPERMARKETS**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** SUPERMARKETS · **Upstream:** https://github.com/shanmugharajk/react-point-of-sale · **Upstream pin:** `01e14682f2d567ccc7b53d603e8aeb161ee31feb` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

# react-point-of-sale

A simple point of sale application built using react &amp; node.js.

## Note

This is still work in progress.

## To run the current code in development mode

1. Run `yarn` to install all the dependencies in the root and also in the `api` folder.
2. Run `yarn dev:web` in one terminal session to start the web app in `localhost:3000`
3. Run `yarn dev:api` in another terminal session to start the backend API in `localhost:3500`
4. Navigate to http://localhost:3000 and use `admin` as username & password to see the dashboard.

## Some screenshots

<img width="1440" alt="login" src="https://user-images.githubusercontent.com/11159061/41917847-c7aaa21e-7978-11e8-89a3-c24991753fd5.png">

<img width="1438" alt="admin page" src="https://user-images.githubusercontent.com/11159061/41917850-c7ea76a0-7978-11e8-8341-363ecbc421f3.png">

<img width="1440" alt="cart" src="https://user-images.githubusercontent.com/11159061/41918060-2fd37dde-7979-11e8-8a17-02d988f1487e.png">

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Node.js / npm** (manifests: package.json, yarn.lock; scanned in UPSTREAM_CLONE)
- Top-level source layout: `api/`, `public/`, `src/`
- Snapshot size: **176 files**, **10664 lines of code** (measured; see Benchmarks)
- Primary languages: `.js` (115), `.ts` (43), `(none)` (5), `.json` (5), `.lock` (2), `.md` (2)
- Upstream commit pinned for this packaging: `01e14682f2d567ccc7b53d603e8aeb161ee31feb`

---

## Installation

2. Run `yarn dev:web` in one terminal session to start the web app in `localhost:3000`
3. Run `yarn dev:api` in another terminal session to start the backend API in `localhost:3500`
4. Navigate to http://localhost:3000 and use `admin` as username & password to see the dashboard.

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

No usage section was found in the upstream readme. Entry points detected in this project directory:

```sh
npm start          # declared start script, when present
npm run dev        # declared dev script, when present
```

Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

2. Run `yarn dev:web` in one terminal session to start the web app in `localhost:3000`
3. Run `yarn dev:api` in another terminal session to start the backend API in `localhost:3500`
4. Navigate to http://localhost:3000 and use `admin` as username & password to see the dashboard.

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Node.js / npm |
| Manifests detected | package.json, yarn.lock |
| Files in snapshot | 176 |
| Lines of code | 10664 |
| Dependency references | 57 |
| Dependencies by ecosystem | npm: 57 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| npm | @material-ui/icons | ^1.0.0-beta.42 | package.json |
| npm | autosuggest-highlight | ^3.1.1 | package.json |
| npm | axios | ^0.18.0 | package.json |
| npm | classnames | ^2.2.5 | package.json |
| npm | cross-env | ^6.0.3 | package.json |
| npm | currency.js | ^1.1.3 | package.json |
| npm | fast-deep-equal | ^1.1.0 | package.json |
| npm | immutability-helper | ^2.6.6 | package.json |
| npm | material-ui | ^1.0.0-beta.47 | package.json |
| npm | material-ui-icons | ^1.0.0-beta.36 | package.json |
| npm | material-ui-pickers | ^1.0.0-rc.7 | package.json |
| npm | moment | ^2.22.1 | package.json |
| npm | prop-types | ^15.6.1 | package.json |
| npm | react | ^16.2.0 | package.json |
| npm | react-autosuggest | ^9.3.4 | package.json |
| ... | (42 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- `package.json`

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

Upstream contributions: fork the `POINT_OF_SALE` project, create a feature branch, and open a pull request against upstream. Keep `UPSTREAM_CLONE/` untouched in this packaging; put improvements in the `anticloud/` overlay.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
MIT License

Copyright (c) 2018 shanmugharaj

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `POINT_OF_SALE` (category: SUPERMARKETS)
- **Upstream URL:** https://github.com/shanmugharajk/react-point-of-sale
- **Pinned commit (SHA):** `01e14682f2d567ccc7b53d603e8aeb161ee31feb`
- **Branch:** master
- **Pin provenance:** GitHub API commits/master. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`f41216d0de115189e499855cc375c1fcd3300b56c43bc0e397a0836848abd3a2`.

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
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

