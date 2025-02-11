# MLB-Win-Predictor

This project aims to predict MLB team wins based on key statistics using machine learning models such as Linear Regression, Random Forest Regressor, and K-Means Clustering.

**Dataset**

Teams Dataset: Contains overall team statistics per season.

Batting Dataset: Aggregated individual batting statistics.

Pitching Dataset: Aggregated individual pitching statistics.

Fielding Dataset: Aggregated fielding statistics.

**Approach**

  Data Preprocessing
  
    Load and clean team and player statistics datasets.
    
    Aggregate relevant statistics by team and year.
    
    Identify key features that influence team wins.

  Modeling
    
    Linear Regression: Initial model to assess feature importance.
    
    Random Forest Regressor: More robust model to capture non-linear relationships.
    
    K-Means Clustering: Unsupervised learning to explore team groupings based on performance.

**Results**

Evaluated model accuracy using R² Score and RMSE.

Analyzed which statistics influence team wins the most
