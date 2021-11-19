# Scream Detection Analysis with CNN

* The model is trained on urban noises combined with screams.  As a result, when testing against yelps and yells like "let's go" or "yeah!", it's not able to classify them as it's not an actual high pitch scream. [1]
* The testing output of the audio was a probabilities graph across the timeline.  It was hard to evaluate which were actual points of screams detection, therefore, I had to apply a given threshold (>.90) and identify clusters of points to pinpoint screams.  When evaluating against actual screams vs predict screams, this let to 4/23 (17%) accuracy rating.  Most probabilities were detect outside and scattered throughout. [2]

Sources:

* [1] https://github.com/fararay/Scream_Detector
* [2] https://vod.endorse.gg/notebooks/Scream%20Detection/Scream%20Detection.ipynb

