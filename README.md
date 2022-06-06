# LocationMatching_FourSquare
Kaggle Competition: Foursquare - Location Matching
## Goal of Competition
- Given data of certain location, we are to use machine learning models to match location duplicates.
- Data of certain location may be updated regularly and may cause duplicates of data that may reduce the accuracy of search.
- To maintain the highest level of accuracy, the data must be matched and de-duplicated with timely updates from multiple sources


# Dataset 
- Data is comprised of over 1.5 million entries of places for hundred of thousands of Points-of-Interest (POIs) around the world.
- For the competition, there are 3 different dataset provided which are train.csv, pairs.csv
- Train.csv, comprised of 11 attributes such as:
    -  Name, latitude, longitude, address,etc
- Test.csv (for submission)
    - For testing (does not contain POI)


# Feature Engineering/Extraction
- Implementation of Feature Engineering
    - Using pre existing knowledge to select and transform the most relevant features from raw data
- Feature Selection
    - Improves machine learning process and predictive power by selecting important features and eliminating redundant and irrelevant features
    - Example of such data (Missing values, low variance, Highly correlated features)





# Model Explanation
LightGBM : a gradient boosting framework which uses tree based learning algorithm
Advantages of LGBM:
- Faster training speed / efficiency
- Lower memory usage
- Improved accuracy
- Capable of handling large-scale data
![Model summary](/img/lgbm.png)