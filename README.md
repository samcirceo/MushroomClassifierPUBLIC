# Mushroom Classification Overview
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/ScikitLearn-F7931E?style=flat&logo=scikitlearn&logoColor=white)

This machine learning project predicts whether a mushroom is edible or poisonous based on categorical features, comparing a baseline model with a PCA-reduced model to assess the impact of dimensionality reduction on performance and training efficiency.

This repository provides a high level overview of the project. The [complete project](https://github.com/samcirceo/MushroomClassification), including code and detailed results, is available in a private repository. If you would like access, please contact me with your GitHub username.

<p align="center">
  <img src="https://raw.githubusercontent.com/samcirceo/samcirceo/main/images/mushroom.png" width="350">
</p>

### Overview of Project
- Preprocessing steps included data cleaning, splitting data into training and test sets, and **One Hot Encoding** categorical features.
- Built a baseline classification model using **Neural Network**
- Implemented **Principal Component Analysis (PCA)** to reduce feature dimensionality
- Compared model performance using **Confusion Matrices** and validation metrics

### Conclusions
- With the PCA model, we were able to reduce the number of features by ~40%, while retainining 95% of the explained variance. 
- The confusion matrix shows that both models have high levels of accuracy.

### Key Takeaways
- Neural networks can classify categorical feature data after proper encoding and preprocessing.
- Dimensionality reduction with PCA reduced the feature space by ~40% while maintaining accuracy
- Reducing dimensionality can improve computational efficiency without sacrificing model accuracy.
- Evaluation using a confusion matrix helps identify classification errors such as false positives and false negatives.

### Future Improvements
- This data set is relatively small, and limitited to a specific set of mushrooms. Future work could incorporate a diverse dataset to evaluate how the model generalizes with different mushroom types.
- Evaluate models using additional metrics such as precision, recall, and F1-score

