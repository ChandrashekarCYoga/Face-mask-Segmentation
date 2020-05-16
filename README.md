# Face-mask-Segmentation
To build a Face Mask Segmentation model which includes building a face detector to locate the position of a face in an image.

# Objective:
In this problem, we use "Transfer Learning" of an Image Segmentation model to detect any object according to the problem in hand.
Here, we are particularly interested in segmenting faces in a given image
Steps and Tasks:
  Load the dataset given in form .npy format.
  
    We have already extracted the images from wider face-dataset and
  added it in the file images.npy. You can directly use this file for this
  project.
  
    “images.npy” contains details about the image and it’s masks, there
  is no separate CSV file for that
  
    There is no separate train and test data given
    
  Create Features(images) and labels(mask) using that data.
  
  Load the pre-trained model and weights.
  
  Create a model using the above model.
  
  Define the Dice Coefficient and Loss function.
  
  Compile and fit the model.
  
  Evaluate the model.
