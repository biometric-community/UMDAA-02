# UMDAA-02

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FUMDAA--02-181717?logo=github)](https://github.com/biometric-community/UMDAA-02)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](https://www.umiacs.umd.edu/)

**UMDAA-02** — tbiom catalog packaging for `umdaa` (behavioral; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/UMDAA-02
- **Upstream source**: https://www.umiacs.umd.edu/
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `umdaa` |
| Category | `behavioral` |
| Access | `register` |
| Upstream homepage | https://www.umiacs.umd.edu/ |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: UMDAA smartphone active authentication; request from UMD authors.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/UMDAA-02.git
cd UMDAA-02
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_umdaa.sh
```

Place licensed archives under `projects/datasets/umdaa/` (gitignored).

## Dataset structure

```text
UMDAA-02/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: https://www.umiacs.umd.edu/
- Packaging: https://github.com/biometric-community/UMDAA-02/issues
