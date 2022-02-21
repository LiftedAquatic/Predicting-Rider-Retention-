# This project makes use of a mock Uber dataset of rider profiles and ride share stats
## The goal is to use this data to generate a model that effectively predicts rider retention

### Prompt
Uber is interested in predicting rider retention. To help explore this question, we have provided a sample dataset of a cohort of users who signed up for an Uber account in January 2014. The data was pulled several months later; we consider a user retained if they were “active” (i.e. took a trip) in the preceding 30 days.
We would like you to use this data set to help understand what factors are the best predictors for retention, and offer suggestions to operationalize those insights to help Uber.
The data is in the attached file ultimate_data_challenge.json. See Munging notebook detailed description of the dataset. 
1. Perform any cleaning, exploratory analysis, and/or visualizations to use the provided data for this analysis (a few sentences/plots describing your approach will suffice). What fraction of the observed users were retained?
2. Build a predictive model to help Uber determine whether or not a user will be active in their 6th month on the system. Discuss why you chose your approach, what alternatives you considered, and any concerns you have. How valid is your model? Include any key indicators of model performance.
3. Briefly discuss how Uber might leverage the insights gained from the model to improve its long term rider retention (again, a few sentences will suffice).
