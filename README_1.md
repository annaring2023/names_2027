# Which names will be most popular in 2027?

Probability & Statistics mini-research project.

Data:
- USA: US Social Security Administration baby names, 1880–2025
  (https://www.ssa.gov/oact/babynames/limits.html).
- Poland: baby names (first names) from the PESEL register, 2000–2025
  (https://dane.gov.pl/pl/dataset/219,imiona-nadawane-dzieciom-w-polsce).

The SSA files are not stored in git: the notebooks unpack names.zip into `data/` on first run.
The Polish files are stored in this repo in the folder `poland/`.

## Notebooks
- `part_A_zipf.ipynb`: descriptive statistics for 2025 and Zipf's law (H1).
- `part_B_diversity.ipynb`: diversity of names over time (H2), stability of the top-10.
- `part_C_poland_forecast.ipynb`: Polish data, USA vs Poland, variables and a first logit test for the 2027 forecast.

## Setup
Open a notebook in Google Colab: File → Open notebook → GitHub tab → paste this repo's URL.
Download names.zip in a browser and put it into the root of your Google Drive (My Drive).
For part C, also download all CSV files from the folder `poland/` of this repo
and put them into a folder `poland` in My Drive.
Runtime → Run all and allow access to Drive when asked.

To save changes back here: File → Save a copy in GitHub (keep "Include outputs" on, so the plots are visible on GitHub).
