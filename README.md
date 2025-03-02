
## Statement of the problem and description of data. 

### Summary
Opal cards is a smartcard ticket that is being used to pay while travelling on public transports such as bus, metro and train in Sydney. There are different types of opal cards which are child, senior, concession and adult opal cards. These cards can be recharged and reused and the opal card type datasets can be used to measure who is using the public transports often in Sydney and how often people are using the public transports. In this project we will be analysing different types of datasets which are the bus, train and climate dataset in Sydney. The interrelation between these datasets will be analysed. We will see if number of people commuting by bus and train could be predicted on the basis of weather condition and the volume of the different types of passengers. 

### Goals
In our project we aim to analyse opal usage data and weather condition data. We are interested to see if there is any relationship between the datasets. We will be performing univariate, bivariate, and multivariate analysis to understand how variables relate to each other. Here is our goal:
**1.** Data Preparation- We would clean and restructure all the datasets for consistent view.<br/>
**2.** Data exploration- We would explore the datasets by creating different graphs. This would help us to understand the characteristics of the data.<br/>
**3.** To determine if the weather condition affects public transport usage in Sydney.<br/>
**4.** Use the opal usage data to show different patterns.<br/>
**5.** To create a model which could predict the volume of public transport usage based on weather conditions in Sydney.<br/>

### Summary of the Datasets
The opal usage dataset for the bus and train is in the form of .csv file. These files contain the records of monthly usage of opal cards on bus and train in Sydney and outer Sydney and the types of opal cards used from the year 2016 till 2020. We wanted to use the dataset of 2020. In order to get the 2020 dataset, the dataset will have to be cleaned and then we will analyse how it is interrelated to the other datasets. This dataset was obtained from (https://opendata.transport.nsw.gov.au/dataset/opal-trips-bus).<br/>
The climate datasets were also collected from January 2020 until June 2020 where it reports the maximum, minimum temperature, amount of rainfall, sunshine hours and extra everyday in a particular month of Sydney. This dataset can be found in (http://www.bom.gov.au/climate/dwo/IDCJDW2124.latest.shtml).

### Analysis Techniques
**Heatmap:** The heatmaps will illustrate ups and downs in the use of public transport in comparison to climate changes.<br/>
**Boxplots:** Boxplots will be used to show the distribution of the different datasets.
**Line Chart:** shows the overall trends between climate changes and opal transport usage.<br/>
**Linear Regression:** To determine the weather conditions affecting public transport usage.<br/>
**Decision Tree:** will be used to predict the Opal card usage based on climate data.<br/>
**Recursive Feature Elimination:** RFE will be used to figure out the optimal number of features to be used in predictive analytics.
**Error Criteria:**  Mean Squared Error , Mean Transportation Error , R-squared to test the accuracy of our model.<br/>

### Project Planning
**Project Milestone:**<br/>
**Week 8:** We will clean the dataset and remove if there are any outliers in the datasets and group them up.<br/>
**Week 10:** We will build the predictive model and do data manipulation to understand if the climatic changes in Sydney have an impact on the usage of public transport.<br/>
**Week 12:** The testing and the evaluation of the model that has been built will be done. <br/>

### Conclusion

From the graphs and statistics, it can be observed that weather does not really have an impact on people travelling in Sydney by bus and also train. The number of adults, seniors/pensioners, school students, CTP, child/youth will not drop or increase due to the changes in the climate. Only during lockdown due to COVID-19 we could observe that there was a significant drop in the number of passengers travelling by both the bus and train. In the nutshell, other variables may have an impact on the usage of public transportation such as bus and train Sydney but definitely not weather or climatic changes.










