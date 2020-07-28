
1. git clone https://github.com/ieee8023/covid-chestxray-dataset.git
2. git clone https://github.com/agchung/Figure1-COVID-chestxray-dataset.git
3. git clone https://github.com/agchung/Actualmed-COVID-chestxray-dataset.git
4. go to https://www.kaggle.com/tawsifurrahman/covid19-radiography-database to download the COVID-19 Radiography database. Only the COVID-19 image folder and metadata file is required. 
5. go to https://www.kaggle.com/c/rsna-pneumonia-detection-challenge/data to download the RSNA pneumonia dataset
6. Download rsna_test_patients_pneumonia.npy and rsna_test_patients_normal.npy



1. Create a folder , name it covidxdata
2. Unzip all file in the covidxdata folder.
3. Inside covidxdata create a subfolder named CovidxDatasetSplit
4. Inside create 3 subfolders , covid19-pneumonia-normal
5. Run CovidxDataset ,  ~ 20min

Results:

- Count:  {'normal': 10192, 'pneumonia': 7402, 'COVID-19': 762}
