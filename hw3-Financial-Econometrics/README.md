# hw3-Financial-Econometrics

> ⚠️ **Rework before submission:** fill in the `TODO`s, check that the file names and the "How to run" steps still match, and remove this note.

MATH 60231 – Financial Econometrics, HEC Montréal (Prof. Anthony Sanford)
**Homework #3** – due Monday, November 23, 2026

**Group:** Mathis Huot, Nathan Madore, Isabelle Tanara

## Contents

| Path | Description |
| --- | --- |
| `Homework #3 - Mathis Huot, Nathan Madore, Isabelle Tanara.ipynb` | All code: setup, Problems 1–2 (Problem 3 is answered in the write-up) |
| `Data/` | Input data (see below) |
| `Output/` | Every table and figure, saved as PNG by the notebook |
| `Sources/hwk3_ver2026.pdf` | Assignment statement |

The write-up (PDF) is submitted separately. TODO: name of the final PDF.

## Data

| File | Used in | Notes |
| --- | --- | --- |
| `Data/PJM.csv` | Problem 1 | Hourly Zonal COMED price; last 8,760 hours (2018). Daily averages only for the HW2 AR(6) comparison in 1e |
| `Data/UK_bonds.parquet` | Problem 2 (a)–(e) | Daily UK gilt yields, 15 maturities (9M–40Yr) |
| `Data/S&P 500 Historical Data.csv` | Problem 2 (d), (f) | Daily S&P 500 index (log of `Price`) |

## How to run

Requires Python ≥ 3.14 and [uv](https://docs.astral.sh/uv/).

```bash
uv sync
```

Then open the notebook, select the `.venv` kernel and **Run All**. The notebook runs from start to finish and writes all tables and figures to `Output/`.

TODO: approximate run time (the bootstrap and rolling-window parts may be slow).

## Notes

- Q1e reuses `Q2_RollForecast`, `Q2_Realised` and `Q2_DM` from Homework 2, copied unchanged.
- Random draws use a seeded NumPy BitGenerator so results are reproducible. TODO: seed used.
- External sources are cited in the notebook (markdown cells) and in the write-up bibliography. TODO: list any extra sources here.
