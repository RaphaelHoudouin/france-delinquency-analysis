# Statistical Study on Delinquency in France

This repository contains a statistical analysis of delinquency data across France, covering regions, departments, and cities. The analysis is based on official crime statistics recorded by the police and national gendarmerie.

### Overview
The study utilizes statistical datasets at the **commune**, **departmental**, and **regional** levels. It focuses on communes where more than 5 incidents of delinquency have been recorded for three consecutive years. The data is sourced from **data.gouv.fr**, a government portal for open data.

### Data Sources
- **Delinquency Data**: The data used in this study is available on [data.gouv.fr](https://www.data.gouv.fr/fr/datasets/bases-statistiques-communale-departementale-et-regionale-de-la-delinquance-enregistree-par-la-police-et-la-gendarmerie-nationales/#/resources).
- **Regions to Codes**: Correspondence table between regions and their codes is available [here](https://public.opendatasoft.com/explore/dataset/anciennes-nouvelles-regions/table/?flg=fr-fr).
- **Departments to Codes**: Correspondence table between departments and their codes is available [here](https://public.opendatasoft.com/explore/dataset/georef-france-departement/export/?disjunctive.reg_name&disjunctive.dep_name&sort=year).
- **Communes to Codes**: The official commune codes table is available [here](https://www.data.gouv.fr/fr/datasets/code-officiel-geographique-cog/).
- **Communes to Coordinates**: Correspondence between communes and their geographical coordinates is available [here](https://www.data.gouv.fr/fr/datasets/villes-de-france/#/resources).

The data for this analysis was retrieved on **September 30, 2024**.

### **Explanation of the "Project Structure" Section:**
- **`ENG/`**: This directory includes the notebooks and files related to the English version of the analysis.
- **`FR/`**: Contains the French version of the analysis and other related resources.
- **`data/`**: Where the data files are stored (e.g., CSV files, datasets).
- **`requirements.txt`**: Lists all Python packages and dependencies needed to run the project.
- **`README.md`**: This file that provides an overview and instructions for the project.

### Installation and Setup
To run the code and replicate the analysis on your local machine, it is recommended to set up a virtual environment using the provided **requirements.txt** file. This will ensure that the necessary libraries and dependencies are installed.

#### Steps to Install Dependencies:
1. Set up a virtual environment (optional but recommended):
   ```bash
   python -m venv env
   
## Contact

For any questions or feedback, please contact the project maintainer: **RaphaelHoudouin**.  
GitHub: [RaphaelHoudouin](https://github.com/RaphaelHoudouin)
