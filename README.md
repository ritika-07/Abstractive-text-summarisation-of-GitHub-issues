# Abstractive text summarisation of GitHub issues

## Overview

A dataset of GitHub Issues' titles, bodies and URLs has been used to create a Sequence to Sequence model with GRUs to summarize the GitHub issue body. The machine generated title is a more compact yet accurate representation.

#### The project includes:
- RNNs to create a sequence to sequence model for abstractive text summarisation. 
- Teacher forcing algorithm is used to train the decoder model.
- A recommender that suggests GitHub issues with similar titles. The Spotify ANNOY package is used for this purpose.
- The model's performance determined through it's BLEU score.

## Architecture
![Architecture diagram](https://github.com/ritika-07/Abstractive-text-summarisation-of-GitHub-issues/blob/main/architecture.png)

## Dataset
- The dataset used has over 8M entries and hence the model requires sufficient training time.
<br>
- You can find the dataset [here](https://www.kaggle.com/davidshinn/github-issues).
