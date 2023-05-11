# Image-Classification-Unbalanced-Data-Distribution-for-lung-cancer
In this project, we aimed to address the issue of data imbalance in cancer detection using deep neural networks for image classification.

Dataset: https://www.kaggle.com/datasets/andrewmvd/lung-and-colon-cancer-histopathological-images

The first step was to record the performance of a model trained on a balanced dataset and the performance of the same model trained on an unbalanced dataset. Then, apply the techniques we studied on the unbalanced dataset to achieve a similar performance to the model trained on the balanced dataset.

The methodes used to handle the imbalance problem used in this project are:

   *The weighted method: assigns higher weights to the examples from the minority class and lower weights to the examples from the majority    class. The weights are proportional to the inverse of the class frequencies, so that the total weight assigned to each class is equal.      This means that the model gives equal importance to each class during training. 
  
   *The SMOTE (Synthetic Minority Over-sampling Technique) method: is used to deal with class imbalance in the dataset, by generating new      synthetic examples of the minority class, SMOTE increases the size of the minority class and balances the class distribution. 
  
   *The ensemble method works by combining the predictions of multiple models to improve the overall performance of the system. The basic      idea is to use the collective knowledge of multiple models to make better predictions than any single model could make alone. The models    used to form the ensemble model are; ResNet50, VGG16, and EfficientNetB5. 
  
Our results showed that the balanced dataset achieved high accuracy in classifying lung tissue abnormalities. However, the unbalanced dataset demonstrated variations, emphasizing the need to address class imbalance. The weighted class and SMOTE methods improved accuracy but fell short of the balanced dataset's performance. The ensemble method on the other hand achieved the best performance. 

