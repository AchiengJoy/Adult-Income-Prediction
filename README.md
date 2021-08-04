# Adult-Income-Prediction
The income dataset was extracted from 1994 U.S. Census database.
The objective of this machine learning project is to predict whether a person makes over 50K a year or not given their demographic variation. To achieve this, several classification techniques are explored.
### Algorithms used
Logistic Regression, Decision Tree Classifier, Random Forest Classifier,Support Vector Classifier, KNNeighbors Classifier and Recurssive Feature Elimination
### Data Source
Kaggle. Link:https://www.kaggle.com/wenruliu/adult-income-dataset 
### Data Dictionary
1. Categorical Attributes
- workclass: (categorical) Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.
**Individual work category**
- education: (categorical) Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.
**Individual's highest education degree**
- marital-status: (categorical) Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.
**Individual marital status**
- occupation: (categorical) Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.
**Individual's occupation**
- relationship: (categorical) Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
**Individual's relation in a family**
- race: (categorical) White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.
**Race of Individual**
- sex: (categorical) Female, Male.
- native-country: (categorical) United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.
**Individual's native country**
2. Continuous Attributes
- age: continuous.
**Age of an individual**
- education-num: number of education year, continuous.
**Individual's year of receiving education**
- fnlwgt: final weight, continuous.
The weights on the CPS files are controlled to independent estimates of the civilian noninstitutional population of the US. These are prepared monthly for us by Population Division here at the Census Bureau.
- capital-gain: continuous.
- capital-loss: continuous.
- hours-per-week: continuous.
Individual's working hour per week
