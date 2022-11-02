# Convolutional-Neural-Network-for-Brain-Lesion-Segmentation-in-MRI-Images
In this work, three popular deep convolutional neural networks (U-NET, DeepLab, and SegNet) for image segmentation are constructed and compared. This comparison reveals the tradeoff between achieving effective segmentation and segmentation accuracy. Using deep learning, specifically convolutional neural network methods, to build and train models, brain lesions can be identified from MRI images. After the model was able to identify brain injury, the deep learning model was improved by adjusting the model structure, implementing data enhancement, and searching for optimal hyperparameters. We also elaborate on the implementation details and evaluation criteria to improve its segmentation benchmark and performance based on the original model.

# Dataset
1. We select data from TCIA Brain MRI segmentation dataset, which is provided by the cancer image archive.
2. 110 patients' brain MRI images, 3929 images in total
3. Correctly labeled 
4. Data will not be published for privacy. You can get the dataset from kaggle.


# Metric

* Pixel Accuracy  
  
$\text { Pixel Acc }=\frac{\text { accurate pixel }}{\text { total pixel }}$


* MIoU (Intersection over Union)
  
$M	I o U=\frac{A \cap B}{A \cup B}=\frac{T P}{F P+F N+T P}$

    TP:  True positive  
    FP:  False positive  
    TN:  True negative            
    FN:  False negative  

* Dice Coefficient  
  
$\text { Dice }=\frac{2 \times|A \cap B|}{|A|+|B|}$


# Architecture  
* Fully Convolutional Networks (FCN)
* U-net  
* SegNet  
* Deeplab V3

# Optimization  
1.
2.
3.
4. 
