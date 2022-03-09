# Skin-Cancer-Detector-using-CNN

Steps to follow :
1. Run `Skin_CD.ipynb` flie.
    - First cell will download and unzip the dataset automatically.
    - Just make sure to have the Kaggle API configured, follow the [official guide](https://github.com/Kaggle/kaggle-api#api-credentials) if not.
    - Also visit [this](https://www.kaggle.com/smerllo/download-the-dataset-directly-to-the-cloud) page to know more about how to use Kaggle API.
2. At final step of Training the model , save that model into models folder.
3. Give the path of saved Model in `app.py`
    - Example : `Model = load_model('models/model_pro1.h5')`
4. Now run `app.py` file to get UI of Model.

**If using the following method, do not run the first cell in the notebook.**
The dataset can also be downloaded manually from [this](https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000) Kaggle page. Then extract it in the root folder containing `Skin_CD.ipynb`.

Thank You.
