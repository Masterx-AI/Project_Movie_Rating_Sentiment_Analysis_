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
<p align="left"><img src="https://user-images.githubusercontent.com/54996245/141677319-6a2b067d-f2df-4ad7-a783-ff12e92d4207.png" /></p>

**2. Feature-set Distribution**

![image](https://user-images.githubusercontent.com/54996245/141677301-5eaaab92-136e-44a2-80d5-329c7249a045.png)

**3. Data Retention after preforming preprocessing step**

![image](https://user-images.githubusercontent.com/54996245/141677403-b634ae2a-fff4-4576-a1ed-649fc9a1c5d1.png)

**4. Correlation plot for features**

![image](https://user-images.githubusercontent.com/54996245/141677415-6a207c1e-146a-4ec4-b656-2a3d1673fe14.png)

**6. PCA Feature Importance**

![image](https://user-images.githubusercontent.com/54996245/141677429-8fc7e07e-e5a1-4496-8bea-6cbbc9d8cca0.png)

**5. ROC Plots**

![image](https://user-images.githubusercontent.com/54996245/141677436-2bafe4aa-08ed-477c-9977-8afbb9156ea2.png)


**7. ML Algorithm's Scores**
![image](https://user-images.githubusercontent.com/54996245/141677442-43190b6c-c761-42c5-9531-6fb5cbb6bc2c.png)
![image](https://user-images.githubusercontent.com/54996245/141677444-7da0ab25-ac71-4b2c-ab1c-e0dcdb15898f.png)

### Here are some of the key outcomes of the project:
- The Dataset was small totally around 4600 samples & after preprocessing 6.2% of the datasamples were dropped. 
- The spam emails were 20% more than non-spam ones, hence SMOTE Technique was applied on the data to  balance the classes, adding 13.5% more samples to the dataset.
- Visualising the distribution of data & their relationships, helped us to get some insights on the sparse matrix distribution.
- The large feature set was reduced by Feature Extraction Technique - PCA, reducing to 30 features.
- Testing multiple algorithms with default hyperparamters gave us some understanding for various models performance on this specific dataset.
- The ensemble & boosting algorithms perform the best on the current dataset, followed by Support Vector Machines.
- Yet it wise to also consider simpler model like Logistic Regression as it is more generalisable & is computationally less expensive.

