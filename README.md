# AI/ML Project: Movie Rating Sentiment Analysis 🎬

<p align="center"><img src="https://user-images.githubusercontent.com/54996245/143764055-51537f10-e51c-4a50-a335-6725a13c53ef.jpg" style="width: 1000px;"/></p>

### Description:

The dataset is comprised of tab-separated files with phrases from the Rotten Tomatoes dataset. The train/test split has been preserved for the purposes of benchmarking, but the sentences have been shuffled from their original order. Each Sentence has been parsed into many phrases by the Stanford parser. Each phrase has a PhraseId. Each sentence has a SentenceId. Phrases that are repeated (such as short/common words) are only included once in the data.

train.tsv contains the phrases and their associated sentiment labels. We have additionally provided a SentenceId so that you can track which phrases belong to a single sentence.
test.tsv contains just phrases. You must assign a sentiment label to each phrase.
The sentiment labels are:

0 - negative
1 - somewhat negative
2 - neutral
3 - somewhat positive
4 - positive

The dataset can be downloaded here: https://archive.ics.uci.edu/ml/datasets/spambase

### Objective:
- Understand the Dataset & cleanup (if required).
- Build classification models to predict the ratings of the movie.
- Compare the evaluation metrics of vaious classification algorithms.

### The Project is divided into the following steps:
1. Data Exploration
2. Data Preprocessing
3. Exploratory Data Analysis
4. Predictive Modeling
5. Project Outcomes & Conclusions

### Some Visuals of the Project:

**1. Target Variable Distribution**

<p align="left"><img src="https://user-images.githubusercontent.com/54996245/143764112-a539a43d-e391-4162-98a7-83cfffc883e3.png" /></p>

**2. Sequence Length Distribution**

![image](https://user-images.githubusercontent.com/54996245/143764143-b9dfcd0a-05ea-442c-9192-82b4920dbd1c.png)

**3. Most frequent Positive & Negative Words Wordcloud**

![image](https://user-images.githubusercontent.com/54996245/143764150-bc5bf89a-0b9c-4e18-86ae-c222af823323.png)

**4. ROC Plots**

![image](https://user-images.githubusercontent.com/54996245/141677436-2bafe4aa-08ed-477c-9977-8afbb9156ea2.png)


**7. ML Algorithm's Scores**
![image](https://user-images.githubusercontent.com/54996245/143764203-17ce422d-1bba-44ad-a099-dc1112dea314.png)
![image](https://user-images.githubusercontent.com/54996245/143764205-83f2aad2-7454-42d1-bb8f-b5b573356273.png)

### Here are some of the key outcomes of the project:
- The Dataset was large enough totally around 40000 samples & preprocessing was done to clean the samples. 
- The positive & negative reviews were equally distributed.
- Visualising the distribution of data & their relationships, helped us to get some insights on the sparse matrix distribution.
- Testing multiple algorithms with default hyperparamters gave us some understanding for various models performance on this specific dataset.
- Surprisingly Logisitic Regression outperformed most of the other alogrithms. It is more generalisable & computationally less expensive.
