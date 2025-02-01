# Detect keylogger using Machine Learning 


## Keylogger Detection

Keyloggers are malicious programs that record keystrokes, posing serious security threats. This project focuses on detecting keyloggers using **machine learning** techniques. The model has been trained on the [Keylogger Detection Dataset](https://www.kaggle.com/datasets/subhajournal/keylogger-detection) and achieves **97% accuracy** using **Random Forest and K-Nearest Neighbors (KNN)**.

### Dataset and Code Availability

- **Dataset:** Available on Kaggle: [Keylogger Detection Dataset](https://www.kaggle.com/datasets/subhajournal/keylogger-detection)  
- **Code:** Implementation can be found in the Jupyter Notebook: [`keylogger_detection.ipynb`](keylogger_detection.ipynb)  

### Features Used for Detection

- **Keystroke Timing & Frequency:** Analyzing the time interval between key presses.  
- **System Process Monitoring:** Identifying hidden or suspicious background activities.  
- **Pattern Recognition:** Using machine learning to differentiate between normal and malicious keystrokes.  

### Model Performance

| Algorithm       | Accuracy |
|----------------|----------|
| Random Forest  | 97%      |
| KNN            | 97%      |

