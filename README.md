# Session 3: USAS-based Sentiment and Emotion Analysis

This tutorial provides an introduction to using the UCREL Semantic Analysis System (USAS) for sentiment analysis. The focus is on the emotion semantic tags, specifically the Emotional Actions, States, and Processes General category. USAS contains 22 sentiment categories, which are visualized in the included `usas_emo_tags.png` file. The semantic tags often contain one or more ‘pluses’ or ‘minuses’ to indicate a positive or negative sentiment, and this tutorial demonstrates how to leverage these signs for sentiment classification.

## Repository Contents

This repository includes the following files:

1. **Notebooks:**
    - `usas_emotion_analysis.ipynb`: Contains a step-by-step method for tagging and extracting the sentiment (positive, negative, or neutral) of the given text at the sentence level using USAS.
    - `usas_sentiment_classifier.ipynb`: A compacted version of the above notebook that organizes all the functions and classes of the sentiment classifier, allowing it to be imported and used anywhere.
    - `dl_sentiment_classifier.ipynb`: Implementation of five deep learning models (T5, Roberta, RobertaGo, DistilBert, and NRCLex) for emotion analysis, followed by a comparative analysis of these models with the USAS emotion classifier.

2. **Image:**
    - `usas_emo_tags.png`: Visualization of the 22 USAS sentiment categories.

3. **Excel Sheet:**
    - `usas_emo_classes.xlsx`: Detailed list of USAS emotion classes and their descriptions.


## Conclusion

By the end of this tutorial, you will have a comprehensive understanding of how to leverage the UCREL Semantic Analysis System (USAS) for sentiment analysis. You will learn how to effectively utilize the emotion semantic tags provided by USAS to classify sentiments as positive, negative, or neutral. Additionally, you will gain the skills needed to build your own sentiment classifiers, both using traditional methods and advanced deep learning techniques, thereby enabling you to perform detailed sentiment analysis on various text data.


## Acknowledgments
- European Union under Horizon Europe Work Programme 101057332 for their generous grant that made this research possible.
- UCREL Semantic Analysis System (USAS) team for their extensive work on semantic analysis.
- Contributors and maintainers of the Python libraries used in this tutorial.

---

Happy analyzing!
