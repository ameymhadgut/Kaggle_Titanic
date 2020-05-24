# Kaggle_Titanic

## Kaggle Titanic Tutorial

### Source:  https://www.kaggle.com/c/titanic/overview

### Objective: "Use machine learning to create a model that predicts which passengers survived the Titanic shipwreck." -> Maximize Accuracy

### Data Sets: 'train.csv'; 'test.csv'

### Data Notes:

Variable | Definition | Key
-------- | ---------- | ---
survival | Survival | No, 1 = Yes
pclass | Ticket class | 1 = 1st, 2 = 2nd, 3 = 3rd
sex | Sex	
Age | Age in years	
sibsp | # of siblings / spouses aboard the Titanic	
parch | # of parents / children aboard the Titanic	
ticket | Ticket number	
fare | Passenger fare	
cabin | Cabin number	
embarked | Port of Embarkation | C = Cherbourg, Q = Queenstown, S = Southampton

     * pclass: A proxy for socio-economic status (SES)
       * 1st = Upper
       * 2nd = Middle
       * 3rd = Lower

     * age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

     * sibsp: The dataset defines family relations in this way...
       * Sibling = brother, sister, stepbrother, stepsister
       * Spouse = husband, wife (mistresses and fiancés were ignored)

     * parch: The dataset defines family relations in this way...
       * Parent = mother, father
       * Child = daughter, son, stepdaughter, stepson
       * Some children travelled only with a nanny, therefore parch=0 for them.
     
### Engineered Data:
*Use this section to define new features that were created from the original data set.*

### Procedural Notes:
*Use this section to annotate the steps taken to create our model.*
