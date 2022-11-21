# Convolutional Neural Network for Brain Lesion Segmentation in MRI Images


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
* U-Net  
* SegNet  
* Deeplab V3

# Optimization  
1. Resnet Jump Link
2. Transform Learning
3. Dilated Convolution  

# Result
* Before Optimization
![image](https://user-images.githubusercontent.com/63941834/199623094-50f55f94-a7f0-4fc9-8aa2-ffda05cea6f2.png)
* After Optimization
![image](https://user-images.githubusercontent.com/63941834/199623470-446548b4-e76e-4e90-a574-f07fe85896a5.png)


# Visualization  
* Segnet  
![image](https://user-images.githubusercontent.com/63941834/199623275-84e68141-4a45-4aba-80c4-487beecc555f.png)  
* FCN
![image](https://user-images.githubusercontent.com/63941834/199623293-4c927e99-62b8-4bca-899f-994ea38f79de.png)  
* DeepLab
![image](https://user-images.githubusercontent.com/63941834/199623323-16b250c8-7866-40c9-a861-4c4b009a853f.png)  
* U-Net
![image](https://user-images.githubusercontent.com/63941834/199623368-7c443031-0723-4309-ba16-9e89e01aebaf.png)
* Optimization U-Net
1. U-Net  
![image](https://user-images.githubusercontent.com/63941834/199623575-d8a0dcfb-f15e-46ea-989a-16b732d8d1db.png)
![image](https://user-images.githubusercontent.com/63941834/199623707-747b2ec2-e960-4996-ac2f-a04d95d07926.png)

2. U-Net+Res18  
![image](https://user-images.githubusercontent.com/63941834/199623613-b5944b94-751f-4cc7-95c9-e3c9e11a1f25.png)
![image](https://user-images.githubusercontent.com/63941834/199623715-9410ea19-38b7-4de2-ae53-a29e66793c26.png)

3. U-Net+Res18+Dilated  
![image](https://user-images.githubusercontent.com/63941834/199623682-6966ac04-bae4-48ce-bead-e30546d0c6be.png)
![image](https://user-images.githubusercontent.com/63941834/199623725-069d8cb2-416f-467d-8492-bf6f83e27ad0.png)

# Transfer Learning
![image](https://user-images.githubusercontent.com/63941834/199623786-396e887b-e8ed-4d89-98ec-030c77d06469.png)
* Before use transfer learning  
![image](https://user-images.githubusercontent.com/63941834/199623876-ffe96682-4309-4830-9a1e-73e190f09b65.png) ![image](https://user-images.githubusercontent.com/63941834/199623889-b6735498-e6d0-45b4-aabc-5cb30f293aa6.png)  
* After use transfer learning  
![image](https://user-images.githubusercontent.com/63941834/199623940-4013dc3c-0354-4bb8-bc8a-437cda136b0d.png) ![image](https://user-images.githubusercontent.com/63941834/199623966-384cbe03-d9f5-456f-9d89-d4fc555682cf.png)
  





