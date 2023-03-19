﻿# COVID-19-detection-from-CXR-images-using-transfer-learning-approaches.
 
 ## Abstract:
 
In this study, CXRcovNet, an 11-layer custom-designed CNN model, and three state-of-the-art models were evaluated with CXR images to detect COVID-19. Transfer learning techniques were used on the three pre-trained CNN models (VGG-16, ResNet-50, and EfficientNetB3), while the CXRcovNet models were designed and trained from scratch. In order to determine which model is most suitable for this task, all pre-trained as well as CXRcovNet models have been trained on a total of 8,965 CXR scans: 3616 covid-19, 4000 healthy, and 1345 viral pneumonia cases. To perform cross-validation, the samples are divided into 80% for training and 20% for testing. As part of the experiment, all pre-trained and CXRcovNet models were trained with the same hyperparameters and their performance was checked for matrix-like sensitivity, specificity, f1-score, precision, accuracy, and ROC curve. During the experiment, VGG-16 achieved the highest classification accuracy of 97.9%, while its average precision was 97.86%, its recall was 97.9%, and F1 scores were 97.86%. ResNet-50 had 97.6% accuracy, with 97.8% mean precision, 97.3% recall, and 97.3% F1 score, yielding an average AUC of 98.3%, followed by EfficientNet-B3 accuracy = 97.3%, mean precision = 97.3%, recall = 97.3%, F1-score = 97.3%, and average AUC = 98%. An accuracy of 95% and an average AUC of 96.3% were obtained from the custom-designed CNN model. The results show that pre-trained models using the transfer learning concept outperformed the CXRcovNet model trained from scratch for detecting COVID-19 cases using CXR scans.

* Kay words: CXR, CXRcovNet, ResNet-50, AUC, VGG16, EfficientNetB3, X-ray, F1-score

# Model architecture:

### 1. Combied Model architecture

![model architecture](https://github.com/ahmecse/COVID-19-detection-from-CXR-images-using-transfer-learning-approaches./blob/c75035b753ce1c5cd862e669176f521b4f7b3eb2/model%20arch.png)

### 2. VGG 16 Base Model architecture

![model architecture](https://github.com/ahmecse/COVID-19-detection-from-CXR-images-using-transfer-learning-approaches./blob/c75035b753ce1c5cd862e669176f521b4f7b3eb2/vgg16.png)

### 3. VGG 16 Proposed Model architecture

![model architecture](https://github.com/ahmecse/COVID-19-detection-from-CXR-images-using-transfer-learning-approaches./blob/c75035b753ce1c5cd862e669176f521b4f7b3eb2/vgg16proposed.png)

### 4. EfficientNet B3 Proposed Model architecture

![model architecture](https://github.com/ahmecse/COVID-19-detection-from-CXR-images-using-transfer-learning-approaches./blob/2666b679179cd9d4525004812009a32e404140b5/Proposed%20Efficient%20Net%20%E2%80%93B3%20architecture.png)

### 5. Resnet 50 Proposed Model architecture

![model architecture](https://github.com/ahmecse/COVID-19-detection-from-CXR-images-using-transfer-learning-approaches./blob/2666b679179cd9d4525004812009a32e404140b5/Proposed%20ResNet-50%20architecture.png)

# results:
### 1. Confusion metrics (CM) 
### 2. Train loss vs validation loss
### 3. ROC evaluation 
### 4. Inference 
### 5.Classification report summary ![image](https://github.com/ahmecse/COVID-19-detection-from-CXR-images-using-transfer-learning-approaches./blob/af1e73339d8dd54a5eb89e51420fdee5be2494dc/classsification%20reprt.png)
### 6.Model Comparison![image](https://github.com/ahmecse/COVID-19-detection-from-CXR-images-using-transfer-learning-approaches./blob/af1e73339d8dd54a5eb89e51420fdee5be2494dc/modelcoma.png)






