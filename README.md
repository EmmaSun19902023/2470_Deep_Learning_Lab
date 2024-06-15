# Deep Learning: Personality Type Detection on Social Media Text

This project focuses on developing and comparing three deep learning models— a multi-level perceptron (MLP) as baseline, a transformer-based model, and a convolutional neural network (CNN)—to predict personality types based on the most recent 50 texts posted by individuals on social media.

The text data underwent rigorous preprocessing, including text cleaning and tokenization, to prepare it for model training. Three distinct models were developed and evaluated using a diverse set of metrics: accuracy, F1-score, precision, recall, and log loss.

The MLP model featured a shared layer utilizing ReLU activation and four output dense layers employing a sigmoid function. The CNN model involved convolving filters over the input text to capture spatial hierarchies in the data. The transformer model was configured with uncased settings and included a dropout layer with a rate of 0.1 to prevent overfitting.

The transformer-based model demonstrated the most promising performance across various metrics, achieving a mean accuracy of 84.4%. This suggests its superior capability in capturing the nuances of social media text for personality prediction. In contrast, the MLP baseline model attained a mean accuracy of 81.8%, while the CNN benchmark model achieved a significantly lower mean accuracy of 68.3%. The overall accuracy figures further highlighted the differences, with the MLP model at 47.8% and the CNN model at 21.2%.

The comparative analysis indicates that the transformer-based model is the most effective for personality type detection from social media text, outperforming both the MLP and CNN models. The advanced architecture of transformers, which allows for better handling of contextual information in text, likely contributes to its superior performance.

Required Library Versions:

python = 3.10.5

matplotlib = 3.5.2

pandas = 1.4.2

scikit-learn = 1.1.1

numpy = 1.22.4

xgboost = 1.5.1

shap = 0.40.0

jupyter_client = 7.3.1

jupyter_core = 4.10.0

jupyterlab = 3.4.2

jupyter_server = 1.17.0

jupytext = 1.13.8

rise = 5.7.1

plotly = 5.8.0

ipywidgets = 7.7.0








