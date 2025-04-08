# Machine-Learning-Model-for-predicting-Cyber-Criminal-Characteristics
The preprocessed data for the paper "Machine Learning Model for predicting Cyber-Criminal Characteristics"

## HistoricalCrimes.csv

### Overview
These historical crimes are the official crimes recorded at the Cyber Crime Combating Department (3CD) from the year 2019 to 2022. The data was manually collected with the supervision of both researchers and police officers. In this data, we use the same terminology used by the 3CD for both the victim and culprit (offender), where the victim is referenced as "Complainer" and the culprit is referenced as "Accused".

### Column Description
- **hackType:** The type of hack used by the accused to hack the complainer
- **compEntity:** Whether the complainer is a person or company
- **compWork:** The career type of the complainer
- **accWork:** The career type of the accused
- **hackedPlatform:** The hacked platform (e.g. Instagram, Email, etc.)
- **compDevice:** The device type of the complainer whether it is mobile or pc
- **accDevice:** The device type of the accused whether it is mobile or pc
- **goal:** The goal of the accused (What purpose the accused had for hacking)
- **compAddr:** The type of residence of the complainer whether it is a residencial area (Houses) or a commercial area (Buildings)
- **accAddr:** The type of residence of the accused whether it is a residencial area (Houses) or a commercial area (Buildings)
- **compNat:** The nationality of the complainer
- **accNat:** The nationality of the accused
- **compGender:** The gender of the complainer
- **accGender:** The gender of the accused
- **damage:** The type of damages that resulted from the hacking crime
- **relationship:** The relationship between the complainer and the accused
- **result:** The result of the case, whether the accused was indicted or not
- **compAgeGroup:** The age group of the complainer. The number in this column reflect the starting age in 5 years intervals (e.g. 20 means 20-25 years old). The "50" age group indicates the ages 50+
- **accAgeGroup:** The age group of the accused. The number in this column reflect the starting age in 5 years intervals (e.g. 20 means 20-25 years old). The "50" age group indicates the ages 50+

## Survey.csv

### Overview
The researchers conducted a survey to collect the prospective of the 3CD staff regarding what features are important in predicting the crime/criminal characteristics.

### Column Description
- **expYears:** The number of years the staff member has in the 3CD
- **numOfHackCases:** The number of hacking cases the staff member worked on previously
- **rank:** The police/civillian rank of the staff member
- **Other Columns:** Every other column reflect the features that the staff member think is required to predict crime/criminal charecteristic in this column. The features are seperated by a ";"
