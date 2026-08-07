# Exploratory Data Analysis & Classification on Fake News Detection Dataset

## Overview
This dataset contains 6,000 labeled English news articles designed for Fake News Detection using Natural Language Processing (NLP) and Machine Learning techniques. It includes news headlines, complete article text, category information, publication dates, and binary target labels, making it suitable for building classification models.

**Task**

Analyze misinformation patterns, evaluate text features, and build classification models to help users accurately distinguish between real and fake news articles.


**Business & Research Questions**
* **Category Concentration:** Which news category (subject) contains the highest concentration of fake news?
* **Temporal Patterns:** How do publication timelines (`date`) correlate with the spread of fake news compared to real news?
* **Linguistic Trends:** What are the most common keywords or linguistic patterns found in fake news headlines versus real news headlines?
* **Article Length:** Does article length differ significantly between fake and real news articles?

**Limitations of the Dataset**
* Categories in the dataset completely segregate real and fake news, which creates a structural shortcut rather than a natural distribution.
* The publishing timeline exhibits heavy temporal spikes tied to specific collection windows rather than an organic representation of daily global news flow.
* Limited to 6,000 English-language articles, meaning models trained on this data may face generalization challenges when exposed to modern, evolving forms of misinformation outside this specific domain.

**Tools**
Python for Data Cleaning, Data Transformation, Data Visualisation and Data Analysis

**Data Set**

The data set is publicly available on [Kaggle](https://www.kaggle.com/datasets/mobeenfatimah/fake-news-detection-dataset-6000-news-articles)

## License
This dataset is released under the CC BY 4.0 license.
