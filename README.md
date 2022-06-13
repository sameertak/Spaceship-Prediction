# Spaceship-Prediction

The dataset is from a Kaggle Competition.

Link :- https://www.kaggle.com/competitions/spaceship-titanic/

What's in the code?
---------------------------------
1) Concated train and test files
2) Dropped PassengerId and Name, as they are not needed in the prediction.
3) Used Label Encoder to convert Strings to Integers. 
4) Didn't converted the last column (Transported) as it'll convert the null values also.
5) Used Simple Imputer to fill the NaN values.
6) For Age, I used the mean strategy & for others I used the mode strategy.
7) Splitted the train and test.
8) Used LabelEncoder again to convert the labels in the Transported column (as the train dataframe needs it).
9) Splitted the train into x & y.
10) Applied Scaling Techniques.
11) Applied Models.

----------------------------------
I've uploaded the submission to Kaggle and achieved 75% score with a rank of about 1647 on the leaderboard.

Link to my Kaggle account:- https://www.kaggle.com/samirtak
