# ACCE


## 1. Environment
Create a new conda environment firstly.
```
conda create -n name python=3.8
conda activate name
pip install -r requirements.txt
```

## 2. Prepare Data
###  MVTec AD Dataset
Download MVTec AD from [MVTec AD](https://www.mvtec.com/company/research/datasets/mvtec-ad/). 
Unzip the file to `./dataset/`.
```
|--dataset
    |-- mvtec_anomaly_detection
        |-- bottle
        |-- cable
        |-- ....
```


## 3.Train and Test
To get the training and inference results, simply execute the following command.
```
python train.py
```
