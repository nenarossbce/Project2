# Adult Income 
## Predicting if an adult income will be greater than $50,000 based on occupation, education, age and other attributes. 

**Nena Esaw**: 

### Introduction:

The Adult Income dataset was extracted from the 1994 US Census database. The goal is to determine if several factors contribute to individual making a salary over $50,000 with classifiaction techniques. 


### Data Source:
Adult Income https://www.kaggle.com/datasets/wenruliu/adult-income-dataset

For this dataset, there were 48,852 rows and 15 columns. 

![AdultIncome_DataDictionary](https://github.com/nenarossbce/Project2/assets/134180290/738dd7c4-89d7-482c-8dde-86e9da864c56)

### Exploratory Data Analysis
During the exploratory data analysis, it was determined that several columns could be removed to improve predictions. 
  * Native-Country not relavant information for predicting the income 
  * Capital-loss and capital gain has a lot of missing data 
  * Educational-num is the numerical values for education
  * Fnlwgt doesn't add in value in predicting our target 
  * Relationship seems very similar to martial-status 

### Explanatory Visuals
We will look at the attributes that did help with predicting the higher income. 


![gendervsage](https://github.com/nenarossbce/Project2/assets/134180290/535f0452-2cc8-4308-83f7-4cfca8ed10db)

* We can see that more male over the age of 40 generate a higher income over 50k than compared to females. 
* Females over the age 40 make over 50k as well but not as much as males.
* We can determine that over the over of 40 for both male and females they generate a higher income. 

#### Occupation and Hours Worked 
![Occupation vs Hours Worked](https://github.com/nenarossbce/Project2/assets/134180290/175c71b5-292e-4157-99a7-4299dc773b97)

* This graph shows up that Farming-fishing occupation generates the highest income and work more than 50 hours per week. 
* We can also see that a majority of the work class that work over 40 hours per week generate over 50k income. 

### Machine Learning using KNN: 
During the model phase, the KNN was used and the GridSearchCV was used to improve our model's predictions. 
![KNN_GS](https://github.com/nenarossbce/Project2/assets/134180290/2ed65f58-15b7-47f3-9ff7-3c0472bb27b7)

![knn_metrics](https://github.com/nenarossbce/Project2/assets/134180290/147da458-66b5-4364-a829-e3dde9b432b1)


The KNN model is predicting at 83% accuracy. 



