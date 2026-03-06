# Mushroom Classification (Neural Networks)
Machine learning project that predicts whether a mushroom is edible or poisonous using categorical feature data. This project compares a baseline model to a PCA-reduced model to evaluate dimensionality reduction effects on performance and training efficiency. 

<img src="https://raw.githubusercontent.com/samcirceo/samcirceo/main/images/mushroom.png" width="350" />

### Overview of Project
- Preprocessing steps included data cleaning, splitting data into training and test sets, and One Hot Encoding categorical features.
- Built a baseline classification model using neural network
- Implemented Principal Component Analysis (PCA) to reduce feature dimensionality
- Compared model performance using confusion matrices and validation metrics

### Conclusions
- With the PCA model, we were able to reduce the number of features by **40%**, while retainining 95% of the explained variance. 
- The confusion matrix shows that both models have high levels of accuracy.

### Key Takeaways
- Neural networks can classify categorical feature data after proper encoding and preprocessing.
- Dimensionality reduction with PCA reduced the feature space by ~40% while maintaining accuracy
- Reducing dimensionality can improve computational efficiency without sacrificing model accuracy.
- Evaluation using a confusion matrix helps identify classification errors such as false positives and false negatives.

### Future Improvements
- This data set is relatively small, and limitited to a specific set of mushrooms. Future work could incorporate a diverse dataset to evaluate how the model generalizes with different mushroom types.
- Evaluate models using additional metrics such as precision, recall, and F1-score

###  Skills used
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/ScikitLearn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
