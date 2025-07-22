# CSST-IFS GEHONG Data Repository

This repository contains essential spectral templates and emission-line data files required by the [GEHONG](https://github.com/fengshuai0210/csst-ifs-gehong) simulation pipeline, designed for generating realistic CSST-IFS datacubes.

## 📁 Included Data Files

| File / Folder                     | Description                                                                 |
|----------------------------------|-----------------------------------------------------------------------------|
| `Starlib.XSL.fits`               | XSL-based empirical stellar spectra                                         |
| `Starlib.Munari2005.fits`        | Theoretical stellar library from Munari et al. (2005)                       |
| `EMILES/`                        | SSP templates from the EMILES library                                      |
| `fsps.nebular.fits`              | Emission line grid for H II regions generated with FSPS                    |
| `AGN.NLR.fits`                   | Narrow Line Region emission-line templates for AGN                         |
| `FeII.AGN.fits`                  | Fe II pseudo-continuum template for AGN                                    |
| `filter/`                        | Filter transmission curves for photometric synthesis                       |

All files are required to run GEHONG in physical mode (stellar populations, emission lines, AGN components, etc.).

## 📦 How to Use

Clone this repository to access the data files:

```bash
git clone https://github.com/fengshuai0210/csst-ifs-gehong-data.git

