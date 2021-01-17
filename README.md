HW16_MachineLearning

01/17/21

I did devlope and train one model.  When I conducted my initial test of the data, it was generating a Training Score of 0.7239 and a Test Score of 0.5148.

For my model I did the label encoded and a max min scaler.  I coverted the koi_disposition (ultimately was the outcome) with One Hot Encoder and applied the Keras model package of Sequential and layered that with Dense.  I fitted the few times with different epochs and was content with the 50 epochs which generated an accuracy of 0.84.  

I was able to save my trained model (koi_trained.h5) as regan.sav file.   