
## Prerequisite 
```!pip install -U albumentations```  
```!pip install segmentation-models-pytorch```  
```!pip install SimpleITK```  
```!pip install torchmetrics```  
```!pip install Medpy```  
```!git clone https://github.com/deepmind/surface-distance.git```  
```!pip install surface-distance/```

## Task 1 Data Downloading
For Task 1, please run below to download the data  
First mount google drive on colab  
```!wget "https://isic-challenge-data.s3.amazonaws.com/2016/ISBI2016_ISIC_Part3_Test_Data.zip"```  
```!wget "https://isic-challenge-data.s3.amazonaws.com/2016/ISBI2016_ISIC_Part3_Training_Data.zip"```  
```!unzip "/content/ISBI2016_ISIC_Part3_Test_Data.zip" -d "/content/"```  
```!unzip "/content/ISBI2016_ISIC_Part3_Training_Data.zip" -d "/content/"```

## Task 1
Run the cells, you will first see the training & testing records and plots without data augmentation.  
Secondly, you will first see the training & testing record plots with data augmentation.

## Task 2 Data Downloading
For Task 2, please run below to download the data. You might need to upload the dataset zip file for task 2 to your google drive, and then unzip it in the colab  
```!unzip "/content/gdrive/MyDrive/ELEC4010N/HW2/kaggle_3m.zip" -d "/content/"```

## Task 2
Run the cells, you will first see the training & testing records and plots with data augmentation.  
Secondly, you will see four slices of final predicted image and their corresponding masks.
