# ESDA dissertation clustering analysis
This is a data analysis that I conducted as part of my MSc dissertation in Energy Systems and Data Analytics at University College London (UCL).
  
  
## Description
The aim of this analysis is to identify potential user groups in the UK that are inclined to adopt autonomous vehicles (AVs). It is anticipated that individuals who currently do not, or cannot, drive - such as children and the elderly - may rely on AVs for transportation once they become fully automated. To estimate the size of such groups, clustering analysis will be performed in order to identify them.

   
   
## Data
[The UK National Travel Survey (NTS)](https://www.gov.uk/government/statistics/national-travel-survey-2019) is an annual travel database of UK households that is collected by the Department for Transport (DfT) (DfT, 2022). This anonymized dataset contains basic information about individuals, such as age, gender, and economic status, as well as subjective survey responses, including reasons for not driving. Additionally, it includes travel-related records, such as travel time, distance, and mode choice. The NTS dataset will be used to identify new user groups and estimate mode choice.
 
It is worth noting that the publicly available NTS data is aggregated, which may render it unsuitable for data analysis. However, a disaggregated version of the NTS is available to those who have access to the UK Data Service, which provides greater flexibility in data manipulation. In this study, we utilized the most recent version of the National Travel Survey (2002-2020) dataset, which is available through the [UK Data Service (UK Data Service, 2021)](https://beta.ukdataservice.ac.uk/datacatalogue/studies/study?id=5340). We will focus on the 2019 data, as the 2020 data was heavily influenced by Covid-19 restrictions in the UK.

The datasets utilized for this analysis are as follows:
* **day_eul_2002-2020.sav**: Day-level data file (week of travel)
* **household_eul_2002-2020.sav**: Household-level data file
* **individual_eul_2002-2020.sav**: Individual-level data file
* **trip_eul_2002-2020.sav**: Trip-level data file
 
Note that the size of the files exceeds the upload limit of GitHub. As a result, the files have been downloaded and can be retrieved from my Google Drive. The Jupyter notebook includes a code that facilitates the download of these files.
