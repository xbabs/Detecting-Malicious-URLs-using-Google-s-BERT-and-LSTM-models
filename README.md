# Detecting-Malicious-URLs-using-Google-s-BERT-and-LSTM-models
In this project, I developed and compared two models, LSTM and Pre-trained BERT, for the task of detecting malicious webpages. The dataset used for training and evaluation was unbalanced, consisting of 522,214 entries with a train-test split of 70% to 30%.

LSTM (Long-Short Term Memory).

For the LSTM model, I tuned the hyperparameters and achieved a training accuracy of 91.23% and a validation accuracy of 91.36%. The model architecture included a single LSTM layer with a dropout rate of 0.2 and a batch size of 1024. Although adding more layers to the neural network was computationally expensive, the model performed well in detecting malicious URLs.

Google's BERT (Bi-directional Encoder Representations from Transformer).

On the other hand, the Pre-trained BERT model required tokenization but encountered difficulties in initializing the classifier due to affected layers. Despite this setback, the model was expected to exhibit excellent performance, but the actual results fell short due to complex computation requirements.

To evaluate the models' performance, I used various metrics and a confusion matrix. The LSTM model achieved an accuracy of 91.36% and a loss of 0.25, while the Pre-trained BERT model achieved a lower accuracy of 75.9% due to hardware malfunctions.

In summary, the LSTM model demonstrated strong performance, accurately detecting malicious URLs in the validation set 9 out of 10 times. However, the Pre-trained BERT model did not meet the expected performance level, likely due to the dataset's imbalance and size.

This project showcases my proficiency in implementing and comparing different deep learning models for the task of malicious webpage detection. It highlights my ability to tune hyperparameters, handle unbalanced datasets, and evaluate model performance using appropriate metrics.
