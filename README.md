# CSST-IFS GEHONG Data Repository

This repository contains essential spectral templates and emission-line data files required by the [GEHONG](https://github.com/fengshuai0210/csst-ifs-gehong) simulation pipeline, designed for generating realistic CSST-IFS datacubes.

## 📁 Included Data Files

| File / Folder              | Description                                                               |
|---------------------------|---------------------------------------------------------------------------|
| `Starlib.XSL.fits`        | XSL-based empirical stellar spectra                                        |
| `Starlib.Munari2005.fits` | Theoretical stellar library from Munari et al. (2005)                      |
| `EMILES/`                 | SSP templates from the EMILES library                                     |
| `fsps.nebular.fits`       | Emission-line grid for H II regions generated with FSPS                   |
| `AGN.NLR.fits`            | Narrow Line Region emission-line templates for AGNs                       |
| `FeII.AGN.fits`           | Fe II pseudo-continuum template for AGNs                                  |
| `filter/`                 | Filter transmission curves for photometric synthesis                      |

These files are required to run GEHONG in physical mode (stellar populations, emission lines, AGN components, etc.).

## 📦 How to Use

Clone this repository to access the data files:

```bash
git clone https://github.com/fengshuai0210/csst-ifs-gehong-data.git
```

Then set the path to this folder in your GEHONG configuration or scripts as needed.

---

## 📜 Version History

### v3.1.0 — 2025-07-21

* First official release of GEHONG data under GitHub version control
* Migrated from previously managed private/drive-based storage

---

## 📌 Notes

* * This repository only contains static input data. Simulation logic is maintained in the [GEHONG](https://github.com/fengshuai0210/csst-ifs-gehong).

## 📄 License

Unless otherwise stated, all contents are released under the same license as the GEHONG codebase.