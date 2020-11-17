# INTRODUCTION

This code project is for the paper  **Convolutional Neural Network-based Diagnostic Model for Solid, Indeterminate Solitary Pulmonary Nodule or Mass on Computed Tomography**

The best model weights parameters are stored in the **model_weights** folder.

## Authors:

- Ke Sun<sup>1</sup>, email: sk_peace@163.com
- Shouyu Chen <sup>2</sup>, email: 1910667@tongji.edu.cn
- Bin Wang<sup>1</sup>
- Tingting Wang<sup>1</sup>
- Yang Yang<sup>1</sup>
- Yin Wang<sup>2</sup>, email: yinw@tongji.edu.cn
- Chunyan Wu<sup>3\*</sup>
- Xiwen Sun<sup>1\*</sup>, email: sunxiwen5256@163.com


1. Department of Radiology, Shanghai Pulmonary Hospital, Tongji University School of Medicine, 507 Zheng Min Road, Shanghai 200433, China. 
2. Department of Computer Science and Technology, College of Electronics and Information Engineering, Tongji University, 4800 Cao'an Road, Shanghai, 201804, China.
3. Department of Pathology, Shanghai Pulmonary Hospital, Tongji University School of Medicine, 507 Zheng Min Road, Shanghai 200433, China.


## Dataset

### Test Set Nodules

![](/imgs/nodule_test_demo.png)

### Node Size Statistics for Each Dataset

![1](/imgs/hist_train_be.png)

![2](/imgs/hist_train_ma.png)

![3](/imgs/hist_valid_be.png)

![4](/imgs/hist_valid_ma.png)

![5](/imgs/hist_test_be.png)

![6](/imgs/hist_test_ma.png)


## Results

### Scores

|     | Training Set  | Validation Set | Test Set | 
|  ----  | ----  | ----  | ----  | 
| Accuracy  | 86.56% | 80.43% | 82.98% | 
| AUC  | 94.66% | 88.49% | 91.17% | 
| Recall  | 90.67% | 82.14% | 85.71% | 
| Precision  | 87.50% | 85.19% | 85.71% | 

### ROC curve

![](/imgs/auc.png)

### Confusion Matrix

![](/imgs/train_confusion_matrix.png)

![](/imgs/validation_confusion_matrix.png)

![](/imgs/test_confusion_matrix.png)


### Hotmap

#### hotmap on a benign nodule
![](/imgs/hotmap_benign_nodule.png)

#### hotmap on a malignant nodule
![](/imgs/hotmap_malignant_nodule.png)

