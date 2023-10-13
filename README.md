# NASA OSDR Data Curation
This repo is the continuation of the work started in (https://github.com/AnzorGozalishvili/NASA_ODSR_DATA.git). 

# Latest Update: 13.10.2023

# GOALS:
- 1. Perform full data exploration of OSDR on s3 and make those work available in dataset curation notebook(s)
- 2. Make full data accessible on Huggingface
  - 1. Create `experiments` table which contains list of experiments (around 451 as of now)
  - 2. Create `samples` table which contains all samples tables aggregated
  - 3. Create `assays` tables which will contain assays tables aggregated categorized by the studies
- 4. Add `RNABERT` on Huggingface
- 5. Add `RNA-FM` on Huggingface
- 6. Make inferences on RNA sequences on OSDR dataset and add them as a dataset features
- 7. Perform Multi-Dimensional analysis using clustering, 3D structure prediction, Structural Alignment, etc.

# OUR TEAM: [**Space-Born RNA**](https://www.spaceappschallenge.org/2023/find-a-team/dea-has-covid/?tab=details)
- [Anzor Gozalishvili](https://github.com/AnzorGozalishvili)
- [Amiran Gozalishvili](https://github.com/AmiranGozalishvili)
- [Revaz Revazashvili](https://github.com/revaza05)
- [Kristine Eliosidze](https://github.com/kristiELLL)
- [Medea Gejadze](https://www.linkedin.com/in/medea-gejadze-3ab818207/)
- [Salome Javashvili](https://www.linkedin.com/in/salome-javashvili/)

# Nasa Space Apps Challenge "Space-Born RNA" Team Project Description
[Project Description](nasa_challenge_project_description.md)

# Notebooks
- [dataset curation notebook](dataset_curation.ipynb): contains the codes that collects data (NASA OSDR dataset) from s3, processes and merges tables into one.
- [Dataset exploration notebook](NASA_OSDR_explore.ipynb): contains data exploration code to guide users on loading it using huggingface datasets library, iterate on samples, read RNA sequences from fasta files and make ML model inference (RNABERT example)

# Huggingface Datasets / Models Repositories
- [nasa_osdr](https://huggingface.co/datasets/anz2/nasa_osdr): contains merged table on huggingface datasets repo
- [RNABERT](https://huggingface.co/anz2/RNABERT): incomplete work. Trying to make RNABERT available on Huggingface Models registry.

  
