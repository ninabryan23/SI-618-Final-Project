# SI 618 Final Project

## Overview
This project was completed as the final project for **SI 618** and focuses on end-to-end data analysis and machine learning using multiple real-world datasets. The project integrates data from diverse domains, including geography, climate, media metadata, and event-based records, to explore patterns and relationships through structured analysis and modeling.

The work is organized into three main phases: a project proposal, exploratory and statistical analysis, and a machine learning component. Each phase is documented using Jupyter notebooks and exported to HTML for reproducibility and submission.

---

## Methods
The following methods and techniques were used throughout the project:

- Data cleaning and preprocessing using **pandas**
- Exploratory Data Analysis (EDA) with summary statistics and visualizations
- Dataset merging and feature engineering
- Geospatial analysis using **GeoPandas** and U.S. state shapefiles
- Statistical modeling (e.g., regression-based approaches)
- Supervised machine learning models for prediction and pattern discovery
- Model evaluation using appropriate performance metrics

All analysis was conducted in Jupyter notebooks, with rendered HTML versions included for easy viewing.

---

## ⚠️ Data Availability Notice
Raw datasets used in this project are **not included in the GitHub repository** due to GitHub file size limitations.  
All dataset download links, sources, and descriptions are explicitly documented in:

- **Project Part I: Project Proposal.html**
- **Project Part I: Project Proposal.ipynb**

The notebooks in this repository reference these datasets and document all preprocessing and feature engineering steps.

---

## Project Structure
```
SI-618-Final-Project/
├── 20240223-190850/                # Geospatial shapefile data (US states)
│   ├── cb_2018_us_state_500k.shp
│   ├── cb_2018_us_state_500k.dbf
│   ├── cb_2018_us_state_500k.prj
│   ├── cb_2018_us_state_500k.shx
│   └── metadata XML files
│
├── data/                            # Raw and processed datasets (not tracked in repo)
│   ├── city_temperature.csv
│   ├── drug_use.csv
│   ├── keywords.csv
│   ├── merged_df.csv
│   ├── merged_df2.csv
│   ├── Meteorite_Landings.csv
│   ├── movies_metadata.csv
│   ├── ratings.csv
│   ├── scrubbed.csv
│   ├── sf_aliens.csv
│   ├── sf_alternate_universe.csv
│   ├── sf_apocalyptic.csv
│   ├── sf_cyberpunk.csv
│   ├── sf_time_travel.csv
│   └── ufo_df.csv
│
├── deepnote_exports/                # Exported outputs from Deepnote
│
├── Project Part I (Proposal + EDA)/
│   ├── Project Proposal.html
│   └── Project Proposal.ipynb
│
├── Project Part II (Analysis)/
│   ├── Analysis.html
│   └── Analysis.ipynb
│
├── Project Part III (Machine Learning)/
│   ├── Machine Learning.html
│   └── Machine Learning.ipynb
│
└── requirements.txt                 # Explicit Python dependencies
```

---

## Environment + Dependencies
This project was developed primarily in **Deepnote**, which provides a preconfigured data science environment. The `requirements.txt` file lists additional non-default Python dependencies required to run the notebooks outside of Deepnote.

To install dependencies locally:
```bash
pip install -r requirements.txt
```

---

## Notes
- HTML files are rendered versions of the notebooks and can be viewed without executing code.
- Large raw datasets are intentionally excluded from version control; dataset sources are documented in the project proposal.
- The directory structure mirrors the logical progression of the project from proposal to modeling.