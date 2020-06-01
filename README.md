# JanataHack-Machine-Learning-for-Banking
Repository for Analytics Vidhya Hackathon

<img src="data.png"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />
# A Description of my Methodology
#### Feature Engineering & Approach
Loan_Amount_Requested was converted to numeric by removing commas
Catboost requires minimum pre-processing while lightgbm requires some more pre-processing
All NaN's were converted to "NaN"
Created 2 new features.
For lightgbm all string features were label encoded
Catboost was somewhat tuned and the first set of prediction probabilities were generated
LightGBM was somewhat tuned and the second set of prediction probabilities were generated
Finally, a weighted average of the probabilities from both classifiers are used to generate the final predictions
#### Tools used
Python for programming
sklearn and numpy libraries for methodology
lightgbm and catboost library for the final model
matplotlib and seaborn was used for plotting and analyzing the data
#### Competition Result
Rank: 2nd on public LB and 4th on private LB

[link to LeaderBoard!](https://datahack.analyticsvidhya.com/contest/janatahack-machine-learning-for-banking/#LeaderBoard)
