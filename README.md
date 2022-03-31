# 221 Data Curation and Management Reddit r/TheRedPill

This repository contains the code that we have used in our project so far.

trp_data_grabber.ipynb contains the API calls to collect the data from the Pushshift Archive.

The collected data for both the submission and comments data resides at a zenodo link available [here](https://zenodo.org/record/6386942).


clean_data.ipynb takes in the json datatables available at the zenodo link and converts this to workable dataframes. It has a data sanity check at the bottom to confirm which months are present in the dataset.


TODO
1. Clean the 'body' data in 'comments' dataframe to be used in [Perspective API](https://www.perspectiveapi.com/)
  - potentially done using NLTK or regex
3. Get toxicity and severe toxicity scores from [Perspective API](https://www.perspectiveapi.com/)
4. Load scores into existing comments dataframe
5. Analyze data - get daily comments, submissions, daily active users, toxicity over time
6. Create visualizations
