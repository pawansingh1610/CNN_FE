Requirements
Python 3.6
TensorFlow 1.10 
numpy
scikit-learn
matplotlib
keras
pandas

Data
Train data for training the model and test data for validation
Train data: 
train_data_yongxin.csv   510*16 (There are 255 labels for 1 and 255 labels for 0 data)

Test data:
test_data_yongxin.csv 218*16 (There are 109 labels for 1 and 109 labels for 0 data)

Model:
The file of cnn_5foldpara.py is used to find the optimal parameters by using five-fold cross-validation.
The file of cnn.py is used to train the CNN model.
The file of CNN_SVM.py is used to run the hybrid method of CNN-SVM.
The file of CNN_RF.py is used to run the hybrid method of CNN-RF.
The file of CNN_LR.py is used to run the hybrid method of CNN-LR.

The file svm.py is used to run the SVM model
The file of RF.py is used to run the RF model.
The file of LR.py is used to run the LR model.
