# Device Localization Based on RSSI in LoRa Networks
This study presents a machine learning (ML) based device localization approach in an outdoor environment in LoRa networks.

*Dataset*

In this study, we use the latest version of the open-source LoraWAN data set called "Sigfox and LoRaWAN datasets for fingerprint localization in large urban and rural areas."
You can access the data from the link below.

https://zenodo.org/records/3342253

Three Low Power Wide Area Network (LPWAN) datasets, namely "Sigfox_dataset_antrwerp," "Sigfox_dataset_rural," and "lorawan_dataset_antwerp," were recorded from 16 November 2017 to 5 February 2018. In this study, since we focused on outdoor positioning in the LoRa Network, we only used the "lorawan_dataset_antwerp" dataset.

The data set, which contains around $130,000$ in LoRaWAN messages, was collected in Antwerp, Belgium. Each message (each sample) contains $77$ features, including $72$ RSSI values, RX Time, SF, HDOP, Latitude, and Longitude.

# Machine Learning-Based Localization in LoRa
We present the benchmark ML models that we propose for the localization of outdoor devices in RSSI-based LoRaWAN networks: k-NN, CNN, SVR, ANN, XGBoost, and LightGBM.

# Repository Description
* *Data_Description.ipynb* file contains the data preprocessing stage without the normalization script.
* *Enhancing_LoRa_based_Outdoor_Localization_Accuracy_Using_Machine_Learning.ipynb* file is a Supplementary Jupyter Notebook, and it presents the architecture of the ML models. 
