# 221 Data Curation and Management Reddit r/TheRedPill

This repository contains the code that we have used in our project so far.

Our zenodo link available [here](https://zenodo.org/record/6474336) contains all of the datasets used between analysis files.
The files were too large to be hosted directly on github.

trp_data_grabber.ipynb contains the API calls to collect the data from the Pushshift Archive and outputs the trp_submissions and trp_comments json objects.

clean_data_initial takes in trp_comments.json and returns the filtered_comments_json.

clean_data_RQ2 takes in the filtered_comments.json as well as the lexicon dictionaries courtesy of 1] Farrell, Tracie; Fernandez, Miriam; Novotny, Jakub and Alani, Harith (2019). Exploring Misogyny across the Manosphere in Reddit. In: WebSci '19 Proceedings of the 10th ACM Conference on Web Science, pp. 87–96. http://oro.open.ac.uk/61128/1/WebScience139.pdf. Their github is available [here](https://github.com/miriamfs/WebSci2019). The notebook returns the comments_rq2.json file.


## RQ1 - Activity in the Subreddit
analysis_RQ1.ipynb file contains grouped data table for each data for easy visualization

TODO RQ1
- Create Visualizations

## RQ2 - Toxicity/Misogyny

TODO RQ2

- Create visualizations
