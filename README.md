# Titanic: Machine Learning from Disaster
Start here! Predict survival on the Titanic and get familiar with ML basics
(Dataset taken From Kaggle)

**Competition Description**
The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.  On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

In this challenge, we ask you to complete the analysis of what sorts of people were likely to survive. In particular, we ask you to apply the tools of machine learning to predict which passengers survived the tragedy.

**Practice Skills**
Worked on the Dataset using Python
Steps:
1. Analysis of the dataset through Exploratory Data Analysis
  - Using Visualization extracted some useful insights like Women, Children and Pclass 1 passengers survived the most.
  
2. Feature Engineering and Extraction
This is the most important phase in machine learning. A model can work at its best only if the features provided to it are good enough.
  - Imputation of Missing Values: The dataset had missing values in some columns like age. Imputing was done by first extracting the titles from the names and then taking the mean of those individual categories. 
  - Feature Extraction: A number of features were extracted like title as mentioned above. FamilySize, Child, Mother etc were other features extracted to better the model.
  
3. Modelling using:
- Phase 1
   - Base Models: Used Logistic Regression, Decision Tree, Random Forest, Extra Trees Classifiers, SVM and KNN 
   - Ensembles :  Used Bagging with Logistic Regression, Decision Tree and Random Forest, Boosting like Adaptive Boosting, Extreme Gradient Boosting and Gradient Boosting
 
- Phase 2
   - Used hyperparameter tuning like GridSearchCV to fine tune the base models and ensembles. 
   - Worked on a number of permutations and combinations with the base and ensembles 
   - Finally also performed Stacking

4. Further Work that needs to be done
- Work on extracting more features
- Work on feature specific models
- Use deep learning techniques
