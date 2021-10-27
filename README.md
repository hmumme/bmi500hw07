# bmi500hw07
This contains my Homework 07 submission for BMI-500 Fall 2021

File Descriptions:
- code/MUMME-BMI500-Fall2021-hw07.ipynb - complete analysis for this assignment. Opens a SQL connection locally and forms databases using MIMIC-III Clinical Database Demo Files (downloaded in data folder)
- data/D_LABITEMS.csv - from MIMIC-III Clinical Database Demo (https://physionet.org/content/mimiciii-demo/1.4/). Contains the itemids for different laboratory tests contained in the database. We will use this file to search for Acute Kidney Injury (AKI) rleated laboratory tests.
- data/LABEVENTS.csv - from MIMIC-III Clinical Database Demo. Contains the laboratory tests for all the subjects in the demo. We will use the subject id, time and date, test value, and test id columns from this resource.

System Requirements:
- Python version >= 3.8.3
- pandas version >= 1.3.3
- sqlite3 version >= 3.36.0
- matplotlib >= 3.4.3
- numpy >= 1.21.2
- scikit-learn >= 0.23.1
- DateTime >= 4.3
