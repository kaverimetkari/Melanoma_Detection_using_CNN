# Melanoma_Detection_using_CNN

Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

Melanoma Detection Assignment
Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The data set contains the following nine diseases:

1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. Seborrheic keratosis
8. Squamous cell carcinoma
9. Vascular lesion

#Project Pipeline
1. Data Reading and Understanding → Defining the path for train and test images
2. Dataset Creation and visualisation -Create train & validation dataset from the train directory with a batch size of 32. Also, make sure you resize your images to 180*180. Create a code to visualize one instance of all the nine classes present in the dataset
3. Model Building & training : Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).

Choose an appropriate optimiser and loss function for model training
- Train the model for ~35 epochs
