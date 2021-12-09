# Melanoma_CNN_Model
**You can download the dataset here**: https://drive.google.com/file/d/1xLfSQUGDl8ezNNbUkpuHOYvSpTyxVhCs/view?usp=sharing

We built a multiclass classification model using a custom convolutional neural network in tensorflow. 
Aim is to build a CNN based model which can accurately detect melanoma.

**Project Pipeline:**

 	1. Data Reading/Data Understanding → Defining the path for train and test images.
	
	2.Dataset Creation→ Created train & validation dataset from the train directory with a batch size of 32. Also, make sure you resize your images to (180x180).
	3. Dataset visualisation → Create a code to visualize one instance of all the nine classes present in the dataset.
        
	4. Model Building & training : 
	 →Created a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
	 →Choose an appropriate optimiser and loss function for model training.
	 →Trained the model for ~20 epochs.
	 
	5. Choose an appropriate data augmentation strategy to resolve underfitting/overfitting.
	
	6. Model Building & training on the augmented data :
	  →Created a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
	  →Choose an appropriate optimiser and loss function for model training.
	  →Trained the model for ~20 epochs.
	  
	7. Class distribution: Examined the current class distribution in the training dataset.
	
	8. Handling class imbalances: Rectify class imbalances present in the training dataset with Augmentor library.
	
	9. Model Building & training on the rectified class imbalance data :
	  →Created a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
	  →Choose an appropriate optimiser and loss function for model training.
	  →Trained the model for ~30 epochs.
