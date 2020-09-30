# Skin-Cancer-Detector-using-CNN
 
 Here Datasets must be downloaded from the Kaggle.
 Link to download datasets : https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000
  Then extract the datasets with .csv file into same folder Skin-Cancer-Detector-using-CNN
      That is : HAM10000_metadata.csv
                HAM10000_images_part_1
                HAM10000_images_part_2
                These above should be extracted in that above folder.

Required Libraries :
    Web framework : Flask 
    Tensorflow
    Matplotlib
    Keras
    Numpy
    Pandas
    Sklearn
 These above libraries are mandatory.
 
 Steps to follow :
 Step 1 : Run Skin_CD.ipynb flie in jupyter.
 Step 2 : At final step of Training the model , save that model into models folder.
 Step 3 : Give the path of saved Model in app.py (example : Model= load_model('models/model_pro1.h5') )
 Step 4 : Now run app.py file to get UI of Model.
 Thats All.
 Thank You.
                
