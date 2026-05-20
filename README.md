# Text preprocessing for rater inconsistency detection in Dutch open-ended exam responses

## Introduction

This repository contains the research archive for the master's thesis "Text preprocessing for rater inconsistency detection in Dutch open-ended exam responses". The scripts are available, but the data itself is confidential. A guide to request such data is thus provided, with a mock dataset also provided to give a glimpse of the data structure.

## Data

The repository comes in the structure of:

```         
├── mastersthesis.Rproj
├── Data
│   ├── 01_raw
│      └── data_mock.Rdata
│   ├── 02_preprocessed
│   └── README.md
├── Output
│   ├── 01_preprocessed
│   └── 02_results
├── README.md
├── Scripts
│   ├── 01_preprocessing
│   └── 02_results
├── renv
│   ├── activate.R
│   └── library
├── renv.lock
└── Requirements.md
```

## Reproducing the Results

The preprocessed data and results can be reproduced by running the steps below:

1.  Open the R project file `mastersthesis.Rproj` in RStudio.

2.  Run this command in the following R console:

    ```         
    renv::restore()
    ```

3.  Run the preprocessing script `Scripts/01_preprocessing.qmd` first to obtain the preprocessed data. Make sure you have the specified data at hand to have the same responses and results. This will render `data_preprocessed.Rdata` in both `Data` and `Output` folder.

4.  Then run the second script `Scripts/02_results.qmd` to obtain the results of tables and plots.

## Ethics and Privacy

Ethics approval was granted by Ethics Review Board of the Faculty of Social & Behavioural Sciences at Utrecht University. The ethical approval case number is 25-2039.

Data ownership belongs to Stichting Centraal Instituut voor Toetsontwikkeling (Cito) Netherlands. Upon analysis, data was anonymized.

## Permissions and Access

This archive is made publicly available indefinitely. The public GitHub repository is under the responsibility of Kinansa Husainy. For further questions, contact me through [n.k.husainy\@uu.nl](mailto:n.k.husainy@uu.nl) or [kinansahusainy\@gmail.com](mailto:kinansahusainy@gmail.com).
