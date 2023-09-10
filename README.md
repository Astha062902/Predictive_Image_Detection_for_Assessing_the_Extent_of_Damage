# Predictive_Image_Detection_for_Assessing_the_Extent_of_Damage
Developed an innovative machine learning solution for precise flood damage assessment, leveraging image analysis of before and after photos of the same location. This project offers a valuable resource for disaster recovery and response planning.


## Dataset Description
The dataset comprises a total of 322 images, with each half consisting of images depicting a specific location both before and after a flood event. These images are individually identified by a unique identifier referred to as "Image_ID." It is pertinent to note that for each set of images depicting the before/after flood scenes, there is a corresponding image taken during the flood event. For example, the image labeled as "3005.png" captures the scene both before and after the flood, and in tandem with this image, there exists an image denoted as "3005_0.png." The appended "_0.png" suffix indicates that the area depicted within this image remained unaffected by the flood.
This dataset pertains specifically to the Louisiana Floods that transpired in the year 2016. Accompanying the images, there is a complementary CSV file that delineates the associations between the images and their corresponding before and after flood states.



![1005](https://github.com/Astha062902/Predictive_Image_Detection_for_Assessing_the_Extent_of_Damage/assets/118397408/79aa618b-3821-44b7-87d4-3c6eafc3730d)
![1005_1](https://github.com/Astha062902/Predictive_Image_Detection_for_Assessing_the_Extent_of_Damage/assets/118397408/426e8d2e-17f4-40c6-bf6e-788f8625cb29)


## Graphs

### Training and Validation Loss Curves:
To visualize how the training and validation loss change over epochs, you can create loss curves.
<img width="397" alt="Screenshot 2023-09-10 120625" src="https://github.com/Astha062902/Predictive_Image_Detection_for_Assessing_the_Extent_of_Damage/assets/118397408/a440247c-5c28-4582-866a-a1163621a4a5">

### Training and Validation Accuracy Curves:
To visualize how the training and validation accuracy change over epochs, you can create accuracy curves.
<img width="423" alt="Screenshot 2023-09-10 120641" src="https://github.com/Astha062902/Predictive_Image_Detection_for_Assessing_the_Extent_of_Damage/assets/118397408/90202ce1-574e-4fbc-aad3-d2d4090b822e">

### Confusion Matrix:
A confusion matrix can help you understand how well your model is classifying samples.
<img width="472" alt="Screenshot 2023-09-10 120701" src="https://github.com/Astha062902/Predictive_Image_Detection_for_Assessing_the_Extent_of_Damage/assets/118397408/1ddaa7bb-ef50-403f-8d40-a88f3942649e">

### ROC Curve and AUC (Area Under the ROC Curve):
If you're dealing with binary classification, you can create an ROC curve to visualize the trade-off between true positive rate and false positive rate.

<img width="437" alt="Screenshot 2023-09-10 120713" src="https://github.com/Astha062902/Predictive_Image_Detection_for_Assessing_the_Extent_of_Damage/assets/118397408/9f1c500a-28e9-43ea-a4ff-894b062f254c">

### Precision-Recall Curve:
To evaluate the precision-recall trade-off, you can create a precision-recall curve.
<img width="417" alt="Screenshot 2023-09-10 120728" src="https://github.com/Astha062902/Predictive_Image_Detection_for_Assessing_the_Extent_of_Damage/assets/118397408/d82e09f2-abe0-4c7a-82ac-77879d782cbf">






