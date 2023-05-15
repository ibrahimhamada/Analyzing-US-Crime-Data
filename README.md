# Analyzing-US-Crime-Data
*Project of the Statistical Inference and Data Analysis Course Offered in Fall 2022 @ Zewail City*

In this project we used the publicly available crime data offered by the [Federal Bureau of Investigation](https://www.fbi.gov/how-we-can-help-you/more-fbi-services-and-information/ucr/publications) (FBI) and the [Bureau of Justice Statistics](https://bjs.ojp.gov/data-collection/ncvs) (BJS) to analyze the patterns of crime in the U.S across time, regions, and demographics.

## Project Parts:

The project is divided into 6 Parts:

### 1) Data Collection and Cleaning: 
In this part, we collected 4 datasets to be used in the project. Thereadter, we cleaned them as to make them having descriptive column/variable names and numerically-encoded categories replaced by their descriptive string in the analysis outputs and plots. The datasets can be found [here](https://drive.google.com/drive/folders/1xDh8BE7lk3x2xnEbE4HJtjUB-shDm0Pl?usp=sharing)

   * [The national crime victimization survey (NCVS)](https://bjs.ojp.gov/national-crime-victimization-survey-ncvs-api#zjwnq9)
   * [NIBRS Reported offense count data](https://cde.ucr.cjis.gov/LATEST/webapp/#/pages/docApi)
   * [Recidivism data for the state of Georgia [2013-2015]](https://data.ojp.usdoj.gov/Courts/NIJ-s-Recidivism-Challenge-Full-Dataset/ynf5-u8nk)
   * [Firearm laws per state](https://www.statefirearmlaws.org/resources)

### 2) Exploratory Analysis: 
In this part, we used the appropriate statistics and plots to investigate the following:

   1. National criminal offense rates per year across all available years for the top five most frequent offense categories.
   2. The average percentage of violent crimes relative to total crime per state over all available years.
   3. National homicide rates, as well as total violent crime rates per year over all years.
   4. The frequency of non-fatal crime incidents in relation to victim demographics.
   5. The frequency of non-fatal crime incidents in relation to offender demographics.
   6. The relationship between the victim’s education level, their gross household income, and their rate of victimization.

### 3) Answering Questions: 
In this part, we used the Use the appropriate statistics and plots to answer the following
questions:

   1. Which type of non-fatal crime is the most under-reported? Is there an association between the offender-victim relationship and the likelihood of a crime being reported? (reported: ie, police notified at time of occurrence)
   2. Who are the people (the demographic segment) that appear to be most at risk of violent victimization? Who is the least at risk?
   3. Of all victims of non-fatal crimes who suffer an injury, which demographic is the most likely to receive medical attention at the scene? Which is the least likely?
   4. Which class of crimes is associated with the highest rate of same-offense-recidivism; i.e. prison re-entry for the same offense within 3 years of release?
   5. Are prisoners who are younger at the time of release more or less likely to reoffend than those who are older?


### 4) Hypothesis Testing:

   * Claim 1: “U.S. states that implement stricter firearm control laws, have lower violent crime rates on average”
   * Claim2: “Black people are assigned a high risk score compared to white people”
      
In this part, we formulated a hypothesis test to assess the validity of these 2 claims given the available data.



### 5) Regression Analysis:
In this part, we used The [Recidivism data for the state of Georgia [2013-2015]](https://data.ojp.usdoj.gov/Courts/NIJ-s-Recidivism-Challenge-Full-Dataset/ynf5-u8nk) dataset to fit a regression model that predicts the Offender’s supervision risk score based on:

* All prior convictions.
* Offender’s race.
* Offender’s gang affiliation.
* Offender’s age at release.
      

### 6) Machine Learning Model:

In this part, we train a machine learning classifier to predict the likelihood of recidivism within 3 years of release based on the state of Georgia recidivism records using thhe [Recidivism data for the state of Georgia [2013-2015]](https://data.ojp.usdoj.gov/Courts/NIJ-s-Recidivism-Challenge-Full-Dataset/ynf5-u8nk) dataset.


## Notebooks:

   1)[`Notebook1.ipynb`](https://github.com/ibrahimhamada/Analyzing-US-Crime-Data/blob/main/Notebook1.ipynb): This notebook is responsible for dealing with [The national crime victimization survey (NCVS)](https://bjs.ojp.gov/national-crime-victimization-survey-ncvs-api#zjwnq9) dataset to answer some of the questions in Part 3.
   
   2)[`Notebook2.ipynb`](https://github.com/ibrahimhamada/Analyzing-US-Crime-Data/blob/main/Notebook2.ipynb): This notebook is responsible for dealing with [NIBRS Reported offense count data](https://cde.ucr.cjis.gov/LATEST/webapp/#/pages/docApi) dataset to answer some of the questions in Part 3.
   
   3)[`Notebook3.ipynb`](https://github.com/ibrahimhamada/Analyzing-US-Crime-Data/blob/main/Notebook3.ipynb): This notebook is responsible for dealing with [Recidivism data for the state of Georgia [2013-2015]](https://data.ojp.usdoj.gov/Courts/NIJ-s-Recidivism-Challenge-Full-Dataset/ynf5-u8nk) dataset. It includes the implmentation of the Regression Analysis in Part 5 and Machine Learning Model in Part 6. Moreover, it answers some questions from Part 3.
   
   4)[`Notebook4.ipynb`](https://github.com/ibrahimhamada/Analyzing-US-Crime-Data/blob/main/Notebook4.ipynb): This notebook is responsible for dealing with [Firearm laws per state](https://www.statefirearmlaws.org/resources) and [Recidivism data for the state of Georgia [2013-2015]](https://data.ojp.usdoj.gov/Courts/NIJ-s-Recidivism-Challenge-Full-Dataset/ynf5-u8nk) datasets to conduct the Hypothesis Testing in Part 4.
  
  5)[`Statistics_Final_Project.ipynb`](https://github.com/ibrahimhamada/Analyzing-US-Crime-Data/blob/main/Statistics_Final_Project.ipynb): This Notebook combines the 4 Notebooks in one version for the whole project.



