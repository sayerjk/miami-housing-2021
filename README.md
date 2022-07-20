# Miami Home Sale Price Prediction Model

An analysis of the 2021 real estate in Miami. Predicts accurate sale price on new data with a $50,000 margin of error on the test data. Many additional external factors need to be considered and integrated with the current model before any dependable predictions can be made. Real-time updates optimal, and further tuning for accuracy needed.

This project is intended as a real estate business insights exercise, as well as comparsion in performance of various machine learning regression models.The steps taken and models performance are broken down in this repo's [.ipynb file](https://github.com/sayerjk/miami-housing-2021/blob/main/Miami_SFH_Predictions_2021.ipynb). 

Two visualizations in the notebook will not load on Github, and require running on Colab or a local Jupyter instance to view.

![Miami, Florida](https://media.istockphoto.com/photos/aerial-view-of-downtown-miami-florida-picture-id802893644?k=20&m=802893644&s=612x612&w=0&h=_nh3kgUZFP5EO8guUu91ZY-Y7RuxwAgzQwC187Wmb4A=)

- 13,932 samples with 15 predictors to train model on
- Reserving 60% of dataset for training (appx. 8300 samples)
- The remaining 40% split evenly into validation and test sets to prevent data leakage and allow the model to generalize better (appx. 2800 each)
