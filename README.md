## Overview
I completed this project for a machine learning class. My class had a private competition hosted on Kaggle to build the most accurate model classifying images of tulips, sunflowers, daisies, dandelions, and roses. I do not have access to the image labels for the test data set, as these were hidden for competition integrity. 

The repository includes the saved model, the predictions for the test data, and a Jupyter Notebook with my code and model description. Data can be found [here](https://drive.google.com/file/d/11oYevrntDb1i3z09EVaCvY7gQTlLl_I9/view?usp=sharing). I wanted to practice CNN concepts without the help from the pretrained image recognition models that many of my classmates used. The saved model is purely a result of my own experimentation with CNN techniques and hyperparameter tuning.

## Results
The results are reproduceable in Google Colab utilizing a T4 GPU or TPU runtime environment, but free tier usage limits may require training to be done over two days. My model classified the test set images with **89% accuracy** with similar results on the validation set. These results could improve with more data, greater compute capacity, or incorporation of a pretrained model.
