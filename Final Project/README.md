
# Prerequisite 
```!pip install -U albumentations```  
```!pip install segmentation-models-pytorch```  
```!pip install torchmetrics```  
```!pip install Medpy```  
```!git clone https://github.com/deepmind/surface-distance.git```  
```!pip install surface-distance/```

## Project 1  
### Project 1 Data Downloading
For Project 1, please run below to download the data  
First mount google drive on colab  
```!wget https://isic-challenge-data.s3.amazonaws.com/2016/ISBI2016_ISIC_Part3_Training_Data.zip```
```!wget https://isic-challenge-data.s3.amazonaws.com/2016/ISBI2016_ISIC_Part3_Training_GroundTruth.csv```
```!unzip "./ISBI2016_ISIC_Part3_Training_Data.zip"```

### Flowchart
1. Importing all the libraries  
2. Loading data from file system 
3. Data augmentation & Data loaders 
4. Build Model & Mean Teacher architecture 
5. Training & Testing 
6. Results  

## Project 2  
### Project 2 Data Downloading
For Task 2, please run below to download the data. You might need to upload the dataset zip file for task 2 to your google drive, and then unzip it in the colab  
```%cd "/content/gdrive/MyDrive/Colab Notebooks/ELEC4010N/Final Project/Project2"```
```!unzip "/content/gdrive/MyDrive/Colab Notebooks/ELEC4010N/Final Project/Project2/Fundus-doFE.zip" -d "/content/"```

## Flowchart  
1. Loading data from file system 
2. Naive Baseline Model - U-Net  
3. FACT model  
    1. Data augmentation 
    2. Build model & Mean Teacher architecture 
    3. Training & Testing
