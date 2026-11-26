# hw4-Financial-Econometrics

> ⚠️ **Rework before submission:** fill in the `TODO`s, check that the file names and the "How to run" steps still match, and remove this note.

MATH 60231 – Financial Econometrics, HEC Montréal (Prof. Anthony Sanford)
**Homework #4** – due Monday, November 30, 2026

**Group:** Mathis Huot, Nathan Madore, Isabelle Tanara

## Contents

| Path | Description |
| --- | --- |
| `Homework #4 - Mathis Huot, Nathan Madore, Isabelle Tanara.ipynb` | All code: setup, Problems 1–2 (Problem 3 needs no code and is answered in the write-up) |
| `Data/` | Input data (see below) |
| `Output/` | Every table and figure, saved as PNG by the notebook |
| `Sources/hwk4_ver2026.pdf` | Assignment statement |

The write-up (PDF) is submitted separately. TODO: name of the final PDF.

## Data

| File | Used in | Notes |
| --- | --- | --- |
| TODO | Problems 1–2 | Monthly Fama-French 5 factors (2x3), momentum factor and 17 industry portfolios, Jan 1980 – Dec 2021, from [Ken French's Data Library](https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html). All series are excess returns (net of RF) |

## How to run

Requires Python ≥ 3.14 and [uv](https://docs.astral.sh/uv/).

```bash
uv sync
```

Then open the notebook, select the `.venv` kernel and **Run All**. The notebook runs from start to finish and writes all tables and figures to `Output/`.

TODO: approximate run time.

## Notes

- The table formatting functions are reused from our Case Study 1 notebook (as in Homework 3).
- External sources are cited in the notebook (markdown cells) and in the write-up bibliography. TODO: list any extra sources here.
