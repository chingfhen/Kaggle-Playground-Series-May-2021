# Kaggle-Playground-Series-May-2021
A machine learning practice practice project hosted on kaggle


Results:
- at competition close, i was ranked  453 out off 1100 kagglers
- top kaggle scorers had around 0.004 improvement in logloss compared to my score
- generally top scorers used autoML models, stacking and ensembling to achieve top scores
- in future competitions, i could 
    1. learn to use autoML which essentially automates many parts of a ML project such as feature engineering and selection
    2. use better hyperparameter optimization alternatives besides random search, such as OPTUNA 
        - it will search promising parameter spaces and ignore the unpromising ones, essentially speeding up HP search and potentially finding better HP
    3. Further feature engineering such as clustering features 
    4. utilise stacking algorithms to intelligently combine multiple different models like XGboost and catboost by reducing each of their biases
	
Learning Outcomes:
1. Target encoding only had marginal improvements in performance likely due to some target leakage
    - could explore other encoding methods next time
2. Low variance features tend to contain less info and are less important, but dropping the lowest variance features won't necessarily improve performance
3. Dropping features based on feature importances does see some slight improvements in model performance due to reduction in model complexity
4. Adding pairwise features does improve model performance slightly - especially 'addition' pairwise features
    - could explore other ways to combine and engineer new features
5. Random search is an effective and fast way to find better hyperparameters compared to exhaustive GS
    - could explore alternatives like optuna next time
6. Learnt how to use catboost library 
    - it essentially has all the tools and documentation on its own
    - the performance is great though it is also fast
    - could explore autoML and stacking for better to improve performance
