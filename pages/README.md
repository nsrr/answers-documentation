# answers-documentation

## Background
Assessing Nocturnal Sleep/Wake Effects on Risk of Suicide Phase I Study (ANSWERS) Phase I Study was a cross-sectional survey conducted among undergraduate students to evaluate sleep continuity, timing, quality, and disorders in conjunction with general mental health and suicidal thoughts and behaviors. The ultimate goal of the study was to guide subsequent longitudinal studies of sleep and suicidal thoughts and behaviors among undergraduates. The phase I study was conducted from June 2020 to June 2021.

The NSRR ANSWERS dataset includes demographic and survey questionnaire data of 971 young adult participants (18 to 25 years old).
 
## Methods

Survey forms		

The ANSWERS survey questionnaire was meant to measure primary exposures such as self-reported Insomnia severity, nightmare severity, sleep duration, time in bed, sleep efficiency, total wake time, sleep quality, sleep onset, sleep offset, chronotype, absolute and relative social jetlag, as well as secondary exposures such as sleep latency, wake after sleep onset, early morning awakenings, anxiety, depression, alcohol use, cannabis use, tobacco use, thwarted belongingness, perceived burdensomeness, and impulsivity.

The following validated survey instruments were implemented:
-	Pittsburgh sleep quality index
-	Brief Inventory of Sleep Control
-	Insomnia Severity Index
-	Short UPPS-P measure of impulsivity
-	Center for Epidemiologic Studies Depression Scale
-	Generalized Anxiety Disorder – 7 item scale
-	Sleep Disorders Symptoms Check List – 25
-	Columbia Suicide Severity Ratings Scale
-	Disturbing Dreams and Nightmares Severity Index
-	Interpersonal Needs Questionnaire

The ANSWERS Questionnaire form is available for review (see: ‘forms’ folder). 
-	ANSWERS_Survey.doc
 
## Data de-identification
Data are de-identified in that name, date of birth, and any other contact details have been removed. Each individual is identified only by an “ID” variable, which is a random number.

## Data overview
Covariate/phenotype datasets (CSV)
The covariate dataset files (answers- dataset-0.1.0.csv and answers-harmonized-dataset-0.1.0.csv) contain 971 rows each. The first column (ID) is the unique ANSWERS subject identifier. 
The dataset columns are described in the accompanying data dictionary files. The variables data dictionary file includes column names (ID), labels (display names), descriptions, and other metadata. Categorical variables also include an associated “domain” (e.g., 0=Male, 1=Female), which are described in the domains data dictionary file. The forms data dictionary files provide links between variables and the sleep questionnaire form.
The history of the covariate dataset and data dictionary files have been tracked on GitHub (https://github.com/nsrr/answers-data-dictionary). 
The harmonized-dataset contains many of the most frequently used demographic variables. These variables were curated by the NSRR team to allow ready inter-operability with other NSRR datasets. Key variables include:
-	nsrr_age – Subject age
-	nsrr_sex – Subject sex
-	nsrr_race – Subject race
-	nsrr_ethnicity – Subject ethnicity
-	nsrr_current_smoker – Currently smoking cigarettes
-	nsrr_ever_smoker – Ever smoked cigarettes
 
## Access and usage restrictions
Non-commercial use only.
 
## Citation and acknowledgement

When using this dataset, users must cite the following:

> [Zhang GQ, Cui L, Mueller R, Tao S, Kim M, Rueschman M, Mariani S, Mobley D, Redline S. The National Sleep Research Resource: towards a sleep data commons. J Am Med Inform Assoc. 2018 Oct 1;25(10):1351-1358. doi: 10.1093/jamia/ocy064. PMID: 29860441; PMCID: PMC6188513.](https://pubmed.ncbi.nlm.nih.gov/29860441/)

> [Tubbs AS, Hendershot S, Ghani SB, Nadorff MR, Drapeau CW, Fernandez FX, Perlis ML, Grandner MA. Social Jetlag and Other Aspects of Sleep Are Linked to Non-Suicidal Self-Injury Among College Students. Arch Suicide Res. 2022 Apr 7:1-18. doi: 10.1080/13811118.2022.2057262. Epub ahead of print. PMID: 35389330.](https://pubmed.ncbi.nlm.nih.gov/35389330/)

Users must include the following text in any Acknowledgements:
> The National Sleep Research Resource was supported by the U.S. National Institutes of Health, National Heart Lung and Blood Institute (R24 HL114473, 75N92019R002).
 
## References
>	ANSWERS on the National Sleep Research Resource (NSRR): https://sleepdata.org/datasets/answers/

>	NSRR ANSWERS GitHub Data Dictionary: https://github.com/nsrr/answers-data-dictionary
![image](https://user-images.githubusercontent.com/96704544/195895437-d297b386-831a-431b-9a06-f0e4922599b4.png)

## Recent Changes
> Find a complete list of changes in the [CHANGELOG.md](:pages_path:/CHANGELOG.md)