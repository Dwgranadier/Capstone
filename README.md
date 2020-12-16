# Capstone
## This document describes my Capstone project organization and workflow

Organization: Datasets (described below) can be found in the 'data' folder'. The 'misc' folder contains scratch files that I used throughout but do not contain anything to be graded
The answer to the below questions are in Capstone_project.Rmd and TCFB_2020.ipynb

Choice of datasets: I chose the publication describing Immunohistochemical typing of adenocarcinomas 
[Fernandez Moro, et al.](https://datadryad.org/stash/dataset/doi:10.5061/dryad.g8h71)

The downloaded data package contains several folders with non-tidied data. 
Below is the markdown for the path to find an Rmd file that cleans up the marker expression data such that it get's rid of samples with missing variables.
I edited and ran this package and generated the marker_expression.csv and markerexpression.xlsx found in my submission.
I did not include the downloaded raw data in my github but do include the cleaned up version.
/Downloads/doi_10.5061_dryad.g8h71__v1/PCBIL_data_and_code/data_analysis/src/1_pcbil_missing_data.Rmd

For the clinical data, I used the raw clinical data found in the DRYAD folder (path from downloads below) and cleaned it up a little myself
/Downloads/doi_10.5061_dryad.g8h71__v1/PCBIL_data_and_code/raw


## Identify 3 research questions:
1. The three most commonly tested tumors were: Ductal Pancreatic Adenocarcinoma, Hepatocellular Carcinoma, and Intrahepatic cholangiocarcinoma. 
What are the most differentially expressed surface markers between these three diagnoses?
2. Similar to how it is performed in the paper, use machine learning clustering algorithms to determine which diagnoses are most closely related
3. How many patients with each of the tumor diagnoses received chemotherapy?

I answered question 1 in R (see Capstone_project_Final_.Rmd) or just see html or pdf of knitted document 
I answered questions 2 and 3 in python (see TCFB_2020.ipynb)
 