# MAGIC-Gamma-Telescope

- This Classification model is done using Machine Leaning and Auto ML.
- SVM (F1 = 0.86)  and Nural Networks (F1= 0.88) gave best models.
- Auto ML, Pycaret, gave LGBMClassifier as the best model with the F1 of 0.91

## Data Source

Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science.

Donated by:
P. Savicky
Institute of Computer Science, AS of CR
Czech Republic
savicky '@' cs.cas.cz

# Data Preprocessing
- No missing Values
- All the columns and features were used
- 'class' was the target, gamma (signal), hadron (background)
- Balanced the data set using Randomoversampler
- Scale the dataset using StandarsScaler

# Train the model
- Split the data set to train, validation, and test in the proportion of 60%, 20%, and 20%, respectively
- Trained the model for kNN, Naive Bayes, Logistic Regression, SVM (Support Vector Machine), and Neural Net
- SVM (Support Vector Machine) and Neural Net have the best F1 values for test data set

### Auto ML
- Trained the model using auto ML, Pycaret
-  LGBMClassifier was the best model with F1 = 0.91


  
