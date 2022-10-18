# Deep Learning Framework For NFT Price Evaluation

# Research problem 
Evaluate the price based on NFT image features only

# Data
Bored Ape: 8774 images after cleaning 

<img width="116" alt="image" src="https://user-images.githubusercontent.com/54750727/196317777-dd197de8-06d2-4d0e-a955-2f01a4e9b926.png">
Grayscale
<img width="94" alt="image" src="https://user-images.githubusercontent.com/54750727/196318426-2ad46966-2617-4367-b1c1-90ce8581eced.png">
blur
<img width="94" alt="image" src="https://user-images.githubusercontent.com/54750727/196318433-dca2df62-4c31-42c1-80c5-f5d78bbb7cb4.png">

# Methodology
baselineCNN & DenseNet

# Computational Resources
Colab Pro+ *2

## About the files
- baselineCNN.ipynb : 
The original code of baselineCNN (2bin)

- optunaxxxx.ipynb :
Use Optuna to tune the hyperparameters

- xxxgrey/blur.ipynb :
Grayscale images & Blurred images

- adjusted accuracy :
By taking predicted labels in the neighboring bins are correct

