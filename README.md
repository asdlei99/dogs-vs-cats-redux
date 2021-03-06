# dogs-vs-cats-redux

https://shaoanlu.wordpress.com/2017/04/22/deep-learning-on-floyd-dogs-vs-cats-redux-kaggle-competition/

Kaggle dogs vs cats redux on flyodhub

## Usage

### res50_bneck_fconv.ipynb & res50_fc_and_incep.ipynb<br>
ResNet50 as base model with different top layers. <br>
Result: scored in the top 8% on public LB (ensembling in avg_subm.ipynb).


### res50_incepV3_Xcept.ipynb<br>
ResNet50, inceptionV3 adn Xception as base models with simple fully-connected top layers. <br>
Result: scored within top 2% on public LB. 


### knn_image.ipynb<br>
Average test image predictions using k-Nearest-neighbors.


### opt_experiment.ipynb<br>
Comparisons between optimizers: SGD, Adam Nadam and RMSprop inspired by [this paper on arxiv](https://arxiv.org/abs/1705.08292). Result shows that SGD with momentum has better performnace on validation data than adaptive optimizers. [See this blog post for detail.](https://shaoanlu.wordpress.com/2017/05/29/sgd-all-which-one-is-the-best-optimizer-dogs-vs-cats-toy-experiment/)

## Requirements

* Keras 1.2.2
* Tensorflow 1.0
