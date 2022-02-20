# Prostate Cancer Prediction
A Machine learning model to predict prostate cancer 

## Language & OS
1. **Python 3.9.1**
2. **Windows 10 home**

## GPU Support
Please check [Tensorflow](https://www.tensorflow.org/install/) official website to get the correct\
version of [CUDA](https://developer.nvidia.com/cuda-toolkit-archive) & [cuDNN](https://developer.nvidia.com/cudnn) to avoid mismatch with your tensorflow version
## Dataset
The dataset was taken from [kaggle](https://www.kaggle.com/).

[Prostate Cancer Dataset](https://www.kaggle.com/sajidsaifi/prostate-cancer) the dataset what imbalanced. So to balance the dataset I used some Machine learning techniques


## Modules
1. [Numpy](https://numpy.org/)
2. [Tensorflow](https://docs.opencv.org/4.5.5/)
3. [Scikit-Learn](https://scikit-learn.org/stable/)
4. [Pandas](https://pandas.pydata.org/)
4. [Matplotlib](https://matplotlib.org/)
4. [Pickle](https://docs.python.org/3/library/pickle.html)

## Installtion
Just run the below command which installs all the necessary python modules you will need 
```bash
pip install -r requirement.txt
```
## Structure
There are 3 files 
 
One is ```under_sample.ipynb``` which takes the length of the minority class and takes the same amount of length from the majority class and imports them into the Machine Learning model

Another is ```over_sample.ipynb``` which takes the length of the minority class and duplicates the amount of the data until the amount of the minority class matches the majority class.

The last one is ```smote.ipynb``` it creates synthetic data by using K-nearest neighbor and over-samples the minority class with the newly created data
## Execution
To run the code open PowerShell by clicking ```Shift+ Mouse Right Key``` in the directory
```bash
python under_sample.ipynb
```
```bash
python over_sample.ipynb
```


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)