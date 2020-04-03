# Image_captioning_project
Image captioning using keras.


The model has been trained on flickr 8K dataset.

Repositry contains file "image_captioning.ipynb' which has all the code for Image Captioning
New folder in Repositry contains some of predictions/images by model.
model_final_trained_20epochs.h5 is the final model and can be used for predictions with any image with little preprocessing 
for which a function is already present in the code.

folder names saved contains two object named encoding_train.pkl and encoding_test.pkl 
, these folders are mapping between image ids and the feature vectors for the image.
these can be loaded on the go using pickle.

