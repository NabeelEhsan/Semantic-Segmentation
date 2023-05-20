# Semantic-Segmentation
## Introduction
In this assignment, the task is semantic image segmentation using two CNN architectures. The first architecture is based on the FCN (Fully Convolutional Network) style with VGG16 as the backbone, while the second architecture is an enhanced version that utilizes the FPN (Feature Pyramid Network) style with MobileNet as the backbone.

## CNN Architectures
-- Baseline Architecture: FCN with VGG16
The first architecture used for semantic segmentation is based on the FCN style with VGG16 as the backbone. The model is implemented using the segmentation_models library.

-- Enhanced Architecture: FPN with MobileNet
The second architecture is an enhanced version of the baseline architecture, utilizing the FPN style with MobileNet as the backbone. The segmentation_models library is also used to implement this model.

## Training and Evaluation
Batch size: 16

Loss function: Cross entropy (For each pixel)

Optimization algorithm: Adam

Number of epochs: 4 (Due to memory constraints)

### Baseline Architecture: FCN with VGG16

F1 Score: 0.31191959977149963

Dice Coefficient: 0.6880804300308228

Accuracy: 0.8491533398628235

Mean IOU: 0.515702188014984

![9](https://github.com/NabeelEhsan/Semantic-Segmentation/assets/99320378/c011d634-7d67-406f-9630-4ce745d59535)

### Enhanced Architecture: FPN with MobileNet
F1 Score: 0.37166091799736023

Dice Coefficient: 0.6283390522003174

Accuracy: 0.8925751447677612

Mean IOU: 0.5399609804153442


![8](https://github.com/NabeelEhsan/Semantic-Segmentation/assets/99320378/7c17fc5e-1fb7-45f0-aaf0-9f766c99a7a0)

## Discussion
Two CNN architectures were implemented for semantic image segmentation. The enhanced architecture, utilizing FPN with MobileNet, demonstrated better qualitative and quantitative results compared to the baseline architecture with FCN and VGG16. The use of data augmentation and transfer learning techniques further improved the performance of the models.

dataset "https://www.kaggle.com/datasets/nabeelehsan11/segmentation"


