# Word2Vec vs Doc2Vec - Applying both to analyse Reddit Sentiment
This project focuses on drawing a comparison between Word2Vec algorithm and Doc2Vec algorithm by checking which one performs better in analysing Reddit Sentiment. The project was done in several part as listed below:

1. **Exploraty Data Analysis**
   - Firstly, I conducted indepth data analysis of the text in hand by using various descriptive stats.
   - Visualisations including bar plots, box plots and wordclouds were utilised to gain insight into the text.
   - These helped understand stats. including avg. no. of words/chars., most occuring words, distribution of words etc.

2. **Text Preprocessing and Vectorization**
   - After exploration, text preprocessing was conducted to refine the text and prepare it for vectorization.
   - Unnecessary stopwords, characters, punctautions and unneeded spaces were removed from the data since they do not add any semantic meaning to our text.
   - Once text preprocessing was done text was converted into Word2Vec and Doc2vec embeddings.
   - Data was split into training and testing and was sent to train the model.

3. **Model Fitting, Hyperparameter Tuning and Evaluations:**
   - Popular boosting algorithm, XGBoost was used to conduct a comparison between predictions made by Word2Vec and Doc2Vec embeddings.
   - Hyperparameter tuning was conducted to find the best parameters for the XgBoost model using GridSearchCV.
   - It was seen that Word2Vec outperformed Doc2Vec by a huge margin, achieving an accuracy close to 99%
