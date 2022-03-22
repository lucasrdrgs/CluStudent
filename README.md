# CluStudent
Student clustering based on ENEM grades and socioeconomic factors.
Also has school efficiency estimator using an ensemble of regression models.

## Steps Taken
### 1. Gather data
We used data from ENEM 2019 acquired from [INEP](https://inep.gov.br). The data, however, has been taken down and replaced by ENEM 2020 (which we did not intend to use due to Covid influence on education, which we consider as an outlier). Therefore, we have decided to release the CSV we used [in this link](https://drive.google.com/drive/folders/1xoeH5objOs0JGlGR4Xv59UwmGD0lsop2?usp=sharing).

### 2. Clean up data
There is a lot of garbage and useless variables in the dataset. Most attempts to load the CSV into a Pandas DataFrame will end up freezing the computer. To avoid the problem, we analyzed the variable dictionary and curated a list of variables that could be useful, both categorical and numeric. The list is the following:
- ID
- wip
