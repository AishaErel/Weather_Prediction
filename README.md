We used a public weather dataset to predict weather conditions:
https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository/data

The key steps in our approach include:
- Data Cleaning:  Preparing the dataset by handling missing values and inconsistencies
- Outlier Detection and removing them (Box Plot and Isolation Forest)
- EDA: Understanding data distrubution trends and visually representing them
- Correlation Matrix: Analyzing feature relationships
- After detecting most important features, using Label Encoder to convert categorical target values (cloudy, sunny,etc)
to numerical values.
- Using Decision Tree, Random Forest Regression/Classification methods to train and test data
- Created streamlit web page which uses Random Forest Classification to predict the weather type

Team Members (club project):
Aisha Erel (me)
Yash Nadge (project manager)
Aseel Ahmed Lakadia
Linjie Yang
Erin Lee


