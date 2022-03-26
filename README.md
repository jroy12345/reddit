# 221 Data Curation and Management Reddit r/TheRedPill

- dataset [link](https://zenodo.org/record/6386942)
- contains both tables

clean_data.ipynb takes in json datatables found at zenodo link and converts to usable data frames

TODO
1. Data sanity check
  - convert the POSIX timestamps in 'created_utc' into human readable format
  - run quick viz to see if any data is missing
2. regex 'body' data in 'comments' dataframe
3. get toxicity and severe toxicity scores from [perspective api](https://www.perspectiveapi.com/)
4. analyze data - get daily comments, submissions, daily active users, toxicity over time
5. create viz
