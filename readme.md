# Wildfire Detection System

this is a project i did to predict if there will be a forest fire in algeria based on weather data. it was super interesting to work on and i tried like a ton of different models to see which one was the best at predicting fires.

## Why i made this ipynb

*   i kept seeing news about wildfires and wanted to see if i could use data to predict them.
*   it felt like a more important problem to solve than just predicting house prices or something.
*   i thought it could be useful for an early warning system for firefighters.
*   also it was a good way to practice a bunch of different ml models and techniques.
*   my grandpa had some health issues and it made me think about how data analysis could help in real-world problems.


## How i made it

*   got the data from the uci machine learning repository.
*   used pandas for all the data cleaning and prep. had to fix some weird formatting.
*   made a ton of graphs with matplotlib and seaborn to explore the data first.
*   used scikit-learn for all the machine learning stuff. its awesome.
*   scaled all the features with standardscaler so the models wouldn't get confused.
*   i tried like 9 different models to be super thorough. like random forest, logistic regression, gradient boosting, all those.
*   used gridsearchcv to automatically find the best settings for the best model.
*   i used cross-validation to make sure my results weren't just a fluke.
*   i also made a confusion matrix and roc curves to really see how good the models were.
*   feature importance helped me figure out what weather conditions were the most important predictors.
*   saved the best model and the scaler with pickle, so its reusable.

## Struggles and what i have learned

*   the data was pretty messy. data cleaning is like 80% of the work, for real.
*   learned that accuracy isn't the only thing that matters. for this, "recall" is super important because you dont want to miss a real fire (a false negative).
*   hyperparameter tuning takes a long time to run! had to let my computer run overnight.
*   it was really cool to see how different models performed and why. the stacking model that combines other models did the best which was interesting.
*   overall it was a super fun project and i'm happy with how the final model turned out.

## usage of AI

* Error Lens : finds error in realtime
* Amazon Q Cli : real time code suggestion and explains error
* ChatGPT and Claude : solves bigger porblems