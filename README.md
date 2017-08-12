# deep_font
this is a font detector using deep neural networks and some state-of-the-art techs

the training data is stored in trainL_f1_200bg.dat. You can load it and run the training process immediately. You can also use loadImageToGen(dataset/f1) function to regenerate new training dataset your self. Just change the directory from dataset/f1 to anything like dataset/g1.

You can also either load the best trained model or best weight to get a trained model.
Load model from my_model_0811_f1_063-2.h5 (10MB)
Load best weights from backups/weights0810_f1.best-2.hdf5 (10MB)

Check the whole test results in the excel files in rst.

test images are in test_f folder.

You will need an OpenCV to run the image loader.




