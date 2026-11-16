# hcde-410-final

Term project for HCDE 410: investigating whether shelter outcomes for dogs and cats at Austin
Animal Center (euthanasia and length of stay) differ by the median household income of the ZIP
code tied to each animal's intake, using City of Austin open shelter data and U.S. Census ACS
income data.

See `A4.ipynb` for the full study plan (motivation, research questions, related work, data
exploration, and methodology).

## Data

The raw data is **not included** in this repository. I couldn't confirm that the City of
Austin's open data terms permit redistributing the files, so they are excluded via `.gitignore`.
To run the notebook, download these CSVs into a `data/` folder at the repo root:

| File name to save as | Source |
|---|---|
| `data/Austin_Animal_Center_Intakes.csv` | https://data.austintexas.gov/d/pyqf-r2dc |
| `data/Austin_Animal_Center_Outcomes.csv` | https://data.austintexas.gov/d/gsvs-ypi7 |
| `data/Historical_Intakes.csv` (Step 6 only) | https://data.austintexas.gov/d/wter-evkm |

On each page, use Export → CSV, then rename the file to match the name above.

## License

Code and writing in this repository are released under the MIT License (see `LICENSE`). The
data belongs to the City of Austin and is subject to its Open Data Terms of Use.