We (the Erlich Lab) are interested in using this method for estimating spatio-temporal receptive fields in the rodent FOF.
It is particularly interesting that XGBoost can extract features auto-magically (e.g. rather than assuming velocity or acceleration tuning as you would have to do with a GLM).

# SpykesML
## Machine Learning methods implemented as encoding models
This repository accompanies "Modern Machine Learning Far Outperforms GLMs at Predicting Spikes"[https://doi.org/10.1101/111450]. We implement various Machine Learning algorithms for spike prediction and offer this as a Python template.

The meat of this is in a Jupyter notebook. To run yourself, simply clone this repository and open the notebook in Jupyter.

For ML algorithms applied to decoding, see our partner repository Neural_Decoding, also on the main KordingLab GitHub page.

### Dependencies
#### Basics
 - numpy
 - pandas
 - scipy
 - matplotlib

#### Methods
 - sklearn
 - pyglmnet (glm)
 - xgboost
 - theano (NN)
 - keras (NN)


![predictfirst](https://github.com/KordingLab/spykesML/blob/master/predictfirst.jpg)
