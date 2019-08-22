# Plant seedling classification with neural nets

In this notebook, convnets are used to predict 12 classes of plants from pictures, based on a Kaggle competition data set: https://www.kaggle.com/c/plant-seedlings-classification/leaderboard
<br><br>
Several neural nets are experimented with: 

**No transfer learning**
> 1) 4-layer convnet (3 * conv -> batchnorm -> pooling + 1 * Dense) <br>
> 2) Same 4-layer convnet + regularization (dropout + L1 L2 before output layer) <br>
> 3) 4-layer convnet (4 * larger conv layers, no extra Dense before output) <br>
> 4) 6-layer convnet (6 * larger conv layers) <br>
>
<br><br>
**Transfer learning (Xception)**
> 1) Xception + extra Dense layer before output
