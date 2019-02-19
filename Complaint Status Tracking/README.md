![title](bw.JPG)

# Brainwaves-2019-Machine-Learning

Societe Generale Global Solution Centre (SG GSC) is hosting the fifth edition of its hackathon, Brainwaves 2019


## Complaint Status Tracking

# Problem Statement

** A financial institution news agency has collected 3000 news articles that relates to several matters of financial importance. Before analyzing these unlabeled news, it is only fair to try to partition them into some sort of logical groupings based on their similarities.**

**Your task is to use appropriate unsupervised machine learning algorithm to form the news clusters based on their similarity. Prior to clustering it is recommended to perform basic natural language processing steps such as stemming, tokenization and word vectorization for best results.  **

Notes to keep in mind:

There are no duplicate rows in the dataset.

Cluster number should start from 0.

### Data Description
There is only one file news.csv that contains date, headlines and text of the news.

|Column|Description|
|------|------|
|id|The unique id of the news|
|headline|The headline of the news in text|
|text|The body of the news in text|


### Submission
The submission file should be a zip containing a .txt and .csv file. Both should have 3000 rows.

.txt file should contain the matrix / ndarrays you are using to create clusters.
.csv should contain the cluster of customers against every store.
Format of the csv file:

|id|cluster|
|------|------|
|uid-1|0|
|uid-2|0|
|uid-3|1|
|uid-4|1|
|uid-5|4|

### Evaluation Metric
The submissions will be evaluated on silhouette score. Please read more about the metrics here.
