# Notebooks file for Pre-Process, Train, Predict!

- You will be able to ***preprocess*** the dataset, ***train*** a pytorch model of your own, ***predict*** on new unseen data using your model.

## Note: Recommend using Google Colab for running the code.
 
- Links to Colab:
  
  - `pre_process`: [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ntphiep/deepfake-detection/blob/main/test/notebooks/pre_process.ipynb)
  - `train`: [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ntphiep/deepfake-detection/blob/main/test/notebooks/train.ipynb)
  - `predict`: [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ntphiep/deepfake-detection/blob/main/test/notebooks/predict.ipynb)
  
## Datasets
- Some of the dataset we used are listed below:
  - [FaceForensics++](https://github.com/ondyari/FaceForensics)
  - [Celeb-DF](https://github.com/yuezunli/celeb-deepfakeforensics)
  - [Deepfake Detection Challenge](https://www.kaggle.com/c/deepfake-detection-challenge/data)


## Preprocess
- Load the dataset
- Split the video into frames
- Crop the face from each frame
- Save the face cropped video


## Train
- It will load the preprocessed video and labels the `labels.csv` file.
- Create model using transfer learning with `RestNext50` and `LSTM`.
- Train, Test and save to `.pt` file.

# References:
- [Github Repo](https://github.com/abhijitjadhav1998/Deepfake_detection_using_deep_learning)