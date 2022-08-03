# AI-CAPSTONE-FINAL

Models were built by Le Quang Minh, Jun-2022

About the Project: The goal is to successfully create a model capable of classifying 102 types of flowers in the Oxford_102_flowers dataset
The problem was approached in 3 ways:
  + Simple CNN model with customizations
  + CNN incorporated with a pre-trained model (which was customized and fine-tuned), namely VGG16 and VGG19 
  + Fine-grained image classification approach: Fine-tune Google's BiT-L (Resnet) model

This github contents: There are 3 models and 1 demonstration included. 
+ The Models are useful in examining the code while the Demonstration offers an easy way for everyone to interact with the best model built. 
+ 3 files (h5 and hdf5) and 1 folder of previously-trained models and model weights were also included so you can load them to explore without training from the beginning.
+ There is also a txt file of flower names in the oxford_102_flowers dataset, which you can have a look to know what types of flowers can be fed to the model so it can return a good prediction. 

For an interactive User Interface, visit https://huggingface.co/spaces/qmjnh/flowerClassification_2
