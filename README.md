# Spotify-Valence-Prediction
In this assignment you will dissect Spotify's Valence metric.

> Panos Louridas, Associate Professor <br />
> Department of Management Science and Technology <br />
> Athens University of Economics and Business <br />
> louridas@aueb.gr


Spotify uses a metric called *valence* to measure the happiness of a track. The metric itself, however, was not developed by Spotify. It was originally developed by Echo Nest, a company that was bought by Spotify in 2014. We don't know exactly how valence is calculated. Some details are given by a blog post, which you can find here:

https://web.archive.org/web/20170422195736/http://blog.echonest.com/post/66097438564/plotting-musics-emotional-valence-1950-2013

Your task is to untangle the mystery behind valence and propose how this is derived.

Spotify offers the following information that may be relevant to your task:

* [Get Track's Audio Features](https://developer.spotify.com/documentation/web-api/reference/#/operations/get-audio-features) and [Get Tracks' Audio Features](https://developer.spotify.com/documentation/web-api/reference/#/operations/get-several-audio-features).

* [Get Track's Audio Analysis](https://developer.spotify.com/documentation/web-api/reference/#/operations/get-audio-analysis).
 

## Questions


### Q1: Expore which Features Influence Valence

You will use inferential statistic methods to study how features (track and possibly audio) influence valence. You must find the best possible model for explaining the valence based on the features that you find significant.

### Q2: Predict Valence

Use Machine Learning techniques to predict valence based on track features:

* You will use at least three different methods that do not use neural networks. For each methods you should ensure that you tune your hyperparameters as best as you can.

* Once you identify the best method and hyperparameters, explain, to the extent that is possible, which features influence the valence metric.

* You will evaluate your predictions on a holdout 20% testing dataset.

* You will also use at least one neural network method. Compare the results you obtain by using a neural network with the results you obtain by using the best non-connectivist approach.
