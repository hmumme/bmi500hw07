# bmi500hw07
This contains my Homework 07 submission for BMI-500 Fall 2021

File Descriptions:
- code/MUMME-BMI500-Fall2021-hw07.ipynb - complete analysis for this assignment. Opens a SQL connection locally and forms databases using MIMIC-III Clinical Database Demo Files (downloaded in data folder)
- data/D_LABITEMS.csv - from MIMIC-III Clinical Database Demo (https://physionet.org/content/mimiciii-demo/1.4/). Contains the itemids for different laboratory tests contained in the database. We will use this file to search for Acute Kidney Injury (AKI) rleated laboratory tests.
- data/LABEVENTS.csv - from MIMIC-III Clinical Database Demo. Contains the laboratory tests for all the subjects in the demo. We will use the subject id, time and date, test value, and test id columns from this resource.
- MUMME-BMI500-Fall2021-hw07.pdf - report for this assignment. Contains the introduction, results, methods, discussion, conclusion, and references for the analysis.

System Requirements:
- Python version >= 3.8.3
- pandas version >= 1.3.3
- sqlite3 version >= 3.36.0
- matplotlib >= 3.4.3
- numpy >= 1.21.2
- scikit-learn >= 0.23.1
- DateTime >= 4.3

Instructions:

Download the data and code folders in the same directory on your system, then follow the jupyter notebook to perform the analysis. The notebook will create local SQL databases in your repository that can be stored and accessed later. It will produce tables and figures within the notebook to display results of the analysis.
