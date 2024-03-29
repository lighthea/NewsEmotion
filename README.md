# Project of Data Visualization (COM-480)

| Student's name | SCIPER |
| -------------- | ------ |
| | Sallinen Alexandre|303162
| | |
| | |

[Milestone 1](#milestone-1) • [Milestone 2](#milestone-2) • [Milestone 3](#milestone-3)

## Milestone 1 (29th March, 5pm)
**Dataset**

For this project, I selected a dataset comprising newspaper headlines paired with their corresponding social media scores sourced from BuzzSumo[https://buzzsumo.com/]. This dataset contains articles headlines from the 10 most read US newspapers.

- The dataset needs to be cleaned to ensure UTF-8 format and removing links or other non alphanumeric data from the titles. Such data cleaning is vital for further processing as the text embeddings quality depend highly on it.

- The choice of this dataset aligns with the course's focus on visualization but headlines need to be embedded using word2vec, TfIdf or Transformer based methods. I intend to highlight how much a title influences the success of a given article.

**Problematic**

The core objective of this visualization project is to analyze and represent how different subjective characteristics of news headlines, such as positivity, negativity, bias, or strength, correlate with their performance on social media, measured through engagement scores provided by BuzzSumo (twitter, facebook, reddit). The objective is to discover whether certain emotional or stylistic attributes in news headlines significantly influence their ability to attract attention and engagement online.

The project targets a broad audience ranging from media professionals and marketers to academic researchers and the general public interested in media studies and communication. By presenting a clear and insightful visualization of the data, I aim to shed some light on the ways in which headline characteristics can shape news consumption in the digital landscape.

**Exploratory Data Analysis**

I cleaned the data from non alpha numeeric tokens and prepared a visualisation pipeline. Initial statistics report :

- 99 572 non empty headlines collected from 2020 to 2021
- An average length of 22 words
- Each newsspaper source is equally represented in terms of number of article
- The distribution of data samples according to engagements is exponential

**Related work**

Analysing news paper headline from a purely data centric point of view is a somewhat new method. Some early nlp papers analyse their emotions but never in correlation with the engagement produced.
I disclose that I did work with similar data for private work for a french newspaper, even though no public/official reports were made the difference are as follow :

- I did not have access to such a range of data nor did I use the words embeddings to compare the data, the work I did was much more rudimentary and used manually crafted dictionnaries to assign characteristics to words. This work will only work on unsupervised learning based methods and should display much more robust findings.
## Milestone 2 (26th April, 5pm)

**10% of the final grade**


## Milestone 3 (31st May, 5pm)

**80% of the final grade**


## Late policy

- < 24h: 80% of the grade for the milestone
- < 48h: 70% of the grade for the milestone

