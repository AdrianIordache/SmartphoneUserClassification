# Smartphone User Classification
This project is meant to represent both, an introductory part for Kaggle Competitions and more advanced techniques for improving results.

The solution from 2019 represents an approach to my first competition on Kaggle, where can be found concepts like:
- Signal Interpolation
- Moving Averages
- Statistical Feature Extraction
- LSTM Networks (implementation in Tensorflow 1.X)

And the solution from 2020 represents a more advanced pipeline, developed from previous knowledge and experiences on another Kaggle Competitions:
- Adversarial Validation
- Noise Filtering (by applying a butterworth lowpass filter)
- More Advanced Features Extraction (Fast-Fourier Transformations, Trend Extraction, Skew and Kurtosis)
- Analysis of Highly Correlated Features
- Bagging and Gradient Boosting
- Bayesian Optimization
- Weighted Voting Systems
- Multi-Level Stacking Architectures

# Dataset

The task is to discriminate between 20 mobile device users. For each user, there are 450 accelerometer signal recordings (examples) available for training. The signals are recorded for 1.5 seconds, while the user taps on the smartphone's screen. The accelerometer signal is recorded at 100 Hz, thus containing roughly 150 values. The values are recorded on three different axes: x, y, z.

Each example is assigned to 1 of 20 classes. The training set consists of 9,000 labeled examples. The test set consists of another 5,000 examples. The test labels are not provided with the data.

# Labels Distribution
![Cover Image | 1000x700](https://github.com/AdrianIordache/SmartphoneUserClassification/blob/master/solution-2020/images/data_distribution.png)

From what we can observe in this project won't be necessary to tackle the problem of imbalanced classes.

# Signal Sample Examples
![Cover Image | 1000x700](https://github.com/AdrianIordache/SmartphoneUserClassification/blob/master/solution-2020/images/signals.jpg)

# Classification Reports (Baseline vs Final Model)
![Cover Image | 1000x700](https://github.com/AdrianIordache/SmartphoneUserClassification/blob/master/solution-2020/images/reports_comp.jpg)

# Confusion Matrix (Baseline vs Final Model)
![Cover Image | 1000x700](https://github.com/AdrianIordache/SmartphoneUserClassification/blob/master/solution-2020/images/cm_comp.jpg)

# Predictions Analysis (Baseline vs Final Model)
![Cover Image | 1000x700](https://github.com/AdrianIordache/SmartphoneUserClassification/blob/master/solution-2020/images/predictions_comp.jpg)
