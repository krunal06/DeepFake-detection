# DeepFake-detection

Fakeimage1, fakeeimage2 and fakeimage3.ipynb is used to classify real and fake images.
Fakeimage1 uses folder named combined as a dataset. And save the sequential model as custom_model.h5
Fakeimage2 uses custom_model.h5 to extract last layer to get features and save it as features_rep.csv which contains labels also.
Fakeimage3 uses that csv file and perform RFC and SVM and also PCA.
