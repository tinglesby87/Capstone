In this Capstone project, I examined what pitching statistics best predict quality starts in hitter-friendly versus pitcher-friendly baseball stadiums.  I scraped starting pitching lines off of baseball-reference.com for every game from 2014 to 2016, and aggregated them into tough versus easy ballpark categories.  After aggregating the data into a data frame, cleaning the data, and engineering my target variable quality starts, I ran a Lasso regression to determine which features to drop, and then used my own judgment to drop any other I knew would skew my results.  

I then ran a logistic regressionto predict the degree to which my features predicted quality starts.  Following the logistic regression, I stripped out all actual "quality" starts into a new dataset, and ran a linear regression Fielding Independent Percentage, an advanced pitching performance metric I feature engineered from my dataset.  Following the regressions, I ran decision tree, random forest, and extra trees classification and regression tests to determine what the level of feature importances were in producing each respective test score.
