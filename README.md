# Diabetic Retinopathy Classification Model CNN
This repository contains a classification model made by Matlab for Diabetic Retinopathy Detection.

### Dataset
- For classification with 5 classes, I have installed a set of images from this [Dataset](https://www.kaggle.com/code/parisanahmadi/dl-diabetic-retinopathycdetection-95-acc-cnn/input?scriptVersionId=102744745&select=gaussian_filtered_images) (approximately 450MB).
- For classification with 3 classes, I used the same dataset as the previous one (with 5 classes). However, I combined "Mild nonproliferative diabetic retinopathy (NPDR)" and "Moderate NPDR" into 'Moderate', and "Severe NPDR" and "PDR" into 'Advanced'.
<div align="center">
   <img width="700"  src="https://github.com/Bilal-Belli/DiabeticRetinopathy_ClassificationModel_CNN/assets/74218805/bba166f5-04f9-4c93-bf5d-b786f1a89583">
</div>

### Architecture
This model is built using a pretrained model 'AlexNet', along with 3 additional layers.

The model uses the following optimization algorithm:
- Adam ('adam') for training.

The training settings are as follows:
- Mini-batch size (MiniBatchSize): 32
- Maximum number of epochs (MaxEpochs): 10
- Initial learning rate (InitialLearnRate): 0.0001
- Validation frequency (ValidationFrequency): Calculated based on the number of training images
- Displaying

### Training Progress
#### For Model with 5 Classes
<div align="center">
   <img   src="https://github.com/Bilal-Belli/DiabeticRetinopathy_ClassificationModel_CNN/assets/74218805/32ac1645-d51f-46d2-88de-c6a16e6e065d">
</div>

#### For Model with 3 Classes
<div align="center">
   <img   src="https://github.com/Bilal-Belli/DiabeticRetinopathy_ClassificationModel_CNN/assets/74218805/b040627d-e2a4-469f-b19a-5507e3934c47">
</div>

### Accuracy
- The accuracy for the model with 5 classes: 62,14% .
- The accuracy for the model with 3 classes: 73,79% .
- The accuracy is not perfect but it is good, especialy for the 3 classes.

### Other Statistiques for Model with 5 Classes
#### Confusion Matrix
<div align="center">
   <img  width="550" src="https://github.com/Bilal-Belli/DiabeticRetinopathy_ClassificationModel_CNN/assets/74218805/807f62df-df45-487e-937b-ac6e93c429f4">
</div>

#### True Positive Rate - False Positive Rate
<div align="center">
   <img  width="550" src="https://github.com/Bilal-Belli/DiabeticRetinopathy_ClassificationModel_CNN/assets/74218805/4a2d561f-d4b9-4b39-90d5-db0f423e811d">
</div>

### Other Statistiques for Model with 3 Classes
#### Confusion Matrix
<div align="center">
   <img  width="550" src="https://github.com/Bilal-Belli/DiabeticRetinopathy_ClassificationModel_CNN/assets/74218805/83dea5a7-717e-4634-8952-f32d2c06f78e">
</div>

#### True Positive Rate - False Positive Rate
<div align="center">
   <img  width="550" src="https://github.com/Bilal-Belli/DiabeticRetinopathy_ClassificationModel_CNN/assets/74218805/2de40fb8-1649-45a3-ac7c-46164fd5f9af">
</div>

### License
This repository is licensed under the MIT License.
