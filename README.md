**Melanoma Detection Assignment** <br>

The Assignment is to make a multiclass classification model using convolutional neural network which can accurately detect melanoma, which is a type of cancer that can be deadly if not detected early and it accounts for 75% of skin cancer deaths.<br>

**Table of Contents**<br>

•	 General Information<br>
•	 Conclusions<br>
•	 Technologies Used<br>

**General Information**<br>

-	Melanoma is a type of cancer which accounts for 75 percent of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. The model can classify nine different classes of the disease which includes 'actinic keratosis', 'basal cell carcinoma', 'dermatofibroma', 'melanoma', 'nevus', 'pigmented benign keratosis', 'seborrheic keratosis', 'squamous cell carcinoma', 'vascular lesion'.<br>
-	Here in order to solve this problem we are using the International Skin Imaging Collaboration (ISIC) dataset which contains 2357 which are sorted according to the classification taken with ISIC<br>

**Conclusions**<br>

-	A combination of image augmentation, batch normalization and dropouts seem to be working well in reducing the overfitting of the data.<br>
-	The training and validation loss is nearly decreasing with every epoch. <br> 

**Technologies Used**<br>
-	Tensorflow- 2.12.0<br>
-	Numpy- 1.22.4<br>
-	Augmentor- 0.2.12<br>
-	Keras – 2.12.0<br>
