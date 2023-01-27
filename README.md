# Skin Cancer Classification - Convolutional Network

## Overview - Active Project
This project utilizes a convolutional network to identify 9 different kinds of skin cancers including melanoma, nevus, and more. The model is trained on over 2,200 pictures of various skin cancers based off of this [dataset](https://www.kaggle.com/datasets/nodoubttome/skin-cancer9-classesisic). This model implements fundamental computer vision and classification techniques and includes a step-by-step implementation of the model as well as in-depth notes to customize the model further for higher accuracy.


<div align="center">

<img src="https://user-images.githubusercontent.com/113388793/214178621-3daf9238-cef2-4626-93c1-979e666b87f3.png">

</div>


## Project Website

If you would like to find out more about the project, please checkout: [Project Website](https://www.redaysblog.com/)

## Installing the libraries

This project uses several important libraries such as Pandas, NumPy, Matplotlib, and more. You can install them all by running the following commands with pip:

```bash 
pip install pandas
pip install numpy

python -m pip install -U matplotlib
pip install seaborn

pip install -U scikit-learn
pip install tensorflow

```

If you are not able to install the necessary libraries, I recommend you **use Jupyter Notebook with Anaconda**. I have a .ipynb file for the project as well.


## Configurations

This project utilizes a CSV file for loading the dataset. If you have a CSV file full of text that you would like to use, please feel free to use this code to load your dataset in to the file:


```python
with open("YOUR-TRAINING-DATA.p", mode = 'rb') as training_data:
    train = pickle.load(training_data)

with open("YOUR-VALIDATION-DATA.p", mode = 'rb') as validation_data:
    valid = pickle.load(validation_data)

with open("YOUR-TEST-DATA.p", mode = 'rb') as testing_data:
    test = pickle.load(testing_data)
```


## License

[MIT](https://choosealicense.com/licenses/mit/)
