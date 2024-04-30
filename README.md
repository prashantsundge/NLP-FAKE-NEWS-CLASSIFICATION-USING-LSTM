# NLP-FAKE-NEWS-CLASSIFICATION-USING-LSTM
NLP FAKE NEWS CLASSIFICATION USING LSTM

### Kaggle Link : https://www.kaggle.com/code/prashantkumarsundge/fake-news-classification-using-lstm

### NLP Standardized Index for Fake News Classification Using LSTM

1. [Download and Load Dataset](#download-and-load-dataset)
2. [Distribution Plot on Target Variable](#distribution-plot-on-target-variable)
3. [Data Preprocessing](#data-preprocessing)
   - [Lowering the text](#lowering-the-text)
   - [Removing special symbols](#removing-special-symbols)
   - [Removing tags (\n etc)](#removing-tags-n-etc)
   - [Removing web tags (www. @ etc)](#removing-web-tags-www--etc)
   - [Removing numbers/figures](#removing-numbersfigures)
4. [Text Cleaning](#text-cleaning)
   - [Lowering the text](#lowering-the-text-1)
   - [Removing special symbols](#removing-special-symbols-1)
   - [Removing tags (\n etc)](#removing-tags-n-etc-1)
   - [Removing web tags (www. @ etc)](#removing-web-tags-www--etc-1)
   - [Removing numbers/figures](#removing-numbersfigures-1)
5. [Tokenize and Remove Stopwords](#tokenize-and-remove-stopwords)
6. [One Hot Encoding](#one-hot-encoding)
7. [Embedding Representation](#embedding-representation)
   - [Feature Creation for Each vector](#feature-creation-for-each-vector)
      - [Sequential](#sequential)
      - [LSTM](#lstm)
      - [Dense](#dense)
8. [Model Compile](#model-compile)
9. [Model Summary](#model-summary)
10. [Data Splitting and Preparation](#data-splitting-and-preparation)
    - [Train Test Split](#train-test-split)
11. [Model Training](#model-training)
12. [Observations](#observations)
13. [Model Predict](#model-predict)
14. [Metrics Observations](#metrics-observations)
15. [Model Evaluation](#model-evaluation)
    - [History Graph Observations](#history-graph-observations)
16. [Test Data](#test-data)
17. [Submission File](#submission-file)


