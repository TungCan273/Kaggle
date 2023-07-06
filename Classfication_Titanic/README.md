# Kaggle_Titanic
## Goal
Build a predictive model that answers the question: "What sorts of people were more likely to survice?" using passenger data (ie name, age, gender, socio-economic class, etc).

It is your job to predict if a passenger survived the sinking of the Titanic or not.

For each in the test set, you must predict a 0 or 1 value for the variable.
## The dataset
- The dataset include passenger information like name, age, gender, socio-economic class, etc.  
- `Train.csv` will contain the details of a subset of the passengers on board (891 to be exact) and importantly, will reveal whether they survived or not, also known as the “ground truth”.  
- The `test.csv` dataset contains similar information but does not disclose the “ground truth” for each passenger. It’s your job to predict these outcomes.  
- Using the patterns you find in the `train.csv` data, predict whether the other 418 passengers on board (found in `test.csv`) survived.  
## Submission File Format  
- **PassengerId (sorted in any order)**  
- **Survived (contains your binary predictions: 1 for survived, 0 for deceased)**  
