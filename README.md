# Reddit Political Sentiment Analysis (2024 U.S. Elections)

## Project Overview
In today’s digital era, platforms like Reddit have emerged as modern public forums, hosting extensive discussions on politics. This project analyzes sentiment trends in Reddit threads during the 2024 U.S. general elections. Using Natural Language Processing (NLP) and Machine Learning (ML) models, we explore leader mentions, voter sentiments, and discussion patterns to reveal insights into public opinion.

## Key Objectives
- **Sentiment Analysis**: Identify positive, negative, neutral, and mixed sentiments surrounding leaders like Kamala Harris, Joe Biden, and Donald Trump.
- **Topic Modeling**: Use BERTopic and Latent Dirichlet Allocation (LDA) to uncover trending topics and themes over time.
- **Model Comparison**: Evaluate ML models (Random Forest, Logistic Regression, Naive Bayes) and deep learning models (Bidirectional LSTM, MLP) for sentiment prediction.
## Files in the Repository

- **EDA_and_LDA_Topic_Modelling.ipynb**: Contains exploratory data analysis (EDA) and topic modeling using LDA on Reddit data.
-**Project Paper**: Documentation and context of all the findings
## Dataset
- **Source**: Reddit posts from 2021-2024, scraped using the Python Reddit API Wrapper (PRAW).
- **Content**: Text data from subreddits such as `r/elections` and `r/replublicans`.
- **Preprocessing**: Tokenization, lemmatization, stop-word removal, and vectorization (Count Vectorizer and TF-IDF).

## Methodology
1. **Data Collection**: Extract posts mentioning key political leaders from Reddit using Praw API using keywords to extract US elections 2024 related posts.
2. **Text Preprocessing**: Clean text data using tokenization, lemmatization, and stop-word removal.
3. **Topic Modeling**: Apply BERTopic and LDA for trend analysis.
4. **Sentiment Prediction**: Train models (Random Forest, Logistic Regression, Naive Bayes, Bidirectional LSTM, MLP) to classify sentiments.

## Results
- **Random Forest**: Achieved 90% accuracy.
- **Logistic Regression**: Achieved 86% accuracy.
- **Naive Bayes**: Achieved 75% accuracy.
- **Bidirectional LSTM**: Achieved 83.5% accuracy.
- **MLP**: Achieved 81.6% accuracy.
- Notable insights include spikes in leader mentions during the election period, with Kamala Harris and Donald Trump dominating discussions.

## Limitations
- **Data Volume**: Praw API allows you to scrape the title and flair but not the comments on Reddit.
- **Sentiment Tagging**: Challenges in automatic sentiment labeling due to dataset complexity.

## Tools & Technologies
- **Programming**: Python
- **Libraries**: scikit-learn, gensim, BERTopic, spaCy, NLTK
- **Platforms**: AWS Comprehend API

## Future Work
- Include more extensive datasets to improve model generalization.
- Incorporate additional engagement metrics like comments and user profiles.

## Contributors
- **Anushka Pandey**
- **Confidence Oguebu**

## References
1. Hofmann, V. et al., 2021. *The Reddit Politosphere*.
2. Guimaraes, A. et al., 2019. *Analyzing Traits in Political Discussions on Reddit*.


