# Symptom2Disease
Task: Predict Disease from Natural Language symptom described by patient

Dataset: Kaggle - [niyarrbarman/symptom2disease](https://www.kaggle.com/datasets/niyarrbarman/symptom2disease/data)  
Diseases and Natural Language Symptom Descriptions

### About Dataset
The dataset consists of 1200 datapoints and has two columns: "label" and "text".

    label : contains the disease labels
    text : contains the natural language symptom descriptions.

The dataset comprises 24 different diseases, and each disease has 50 symptom descriptions, resulting in a total of 1200 datapoints.

**Experiments**
- TF-IDF vectorization
   - KNN
   - SVM
   - Random Forest
- Embedding Layer
     - LSTM - one dirn/bi-directional
     - GRU - one dirn/bi-directional

**Libraries Used**
- Sklearn
- NLTK
- Pytorch, Torchtext
- WordCloud
