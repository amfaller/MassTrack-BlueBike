# 🚲 MassTrack: BlueBike 🚲
Author: Tony Faller (af3370@columbia.edu)

## Description
MassTrack is a privacy project developed across two seminars at Columbia University:
* COMS E6156 Topics in Software Engineering (Professor Gail Kaiser)
* COMS E6998 Private Systems (Professor Roxana Geambasu)

This repository contains the Jupyter notebook corresponding to **COMS E6998**, focusing on examining privacy vulnerabilities in publicly-available BlueBike data -- specifically, analyzing pseudo-identifiers which may compromise user privacy.

The Topics in SwE portion of MassTrack can be found here: [https://github.com/amfaller/MassTrack-MBTA](https://github.com/amfaller/MassTrack-MBTA)


## Threat Model
Threat models are detailed within the notebook.

## Dataset & Reproduction
Public BlueBike data is available here: [https://bluebikes.com/system-data](https://bluebikes.com/system-data).

The terms-of-service of this data restricts re-publication, so there was no Zenodo mirror created to this dataset. Instead, this data was downloaded locally, and re-uploaded to a private Google Drive; Google Colab is then able to pull in this data.

To reproduce these results, it is as sufficient as defining paths to the relevant dataset(s) and executing all code cells.
