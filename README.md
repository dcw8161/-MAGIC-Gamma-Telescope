# MAGIC-Gamma-Telescope

- This Classification model is done using Machine Leaning and Auto ML
- SVM (F1 = 0.86)  and Nural Networks (F1= 0.88) gave the best models
- Auto ML, Pycaret gave LGBMClassifier as the best model with F1 of 0.91

## Data Source

Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science.

Donated by:
P. Savicky
Institute of Computer Science, AS of CR
Czech Republic
savicky '@' cs.cas.cz

# Data Preprocessing
- No missing values
- All the columns and features were used
- 'class' was the target, gamma (signal), hadron (background)
- The dataset was balanced using Randomoversampler
- The dataset was scaled using StandarsScaler

# Train the model
- The data set was split to train, validation, and test with the proportions of 60%, 20%, and 20%, respectively
- The classifications models kNN, Naive Bayes, Logistic Regression, SVM (Support Vector Machine), and Neural Net were trained
- SVM (Support Vector Machine) and Neural Net have the best F1 values for test data set

### Auto ML
- The model was trained using Auto ML, Pycaret
- LGBMClassifier was the best model with an F1 of 0.91


  
