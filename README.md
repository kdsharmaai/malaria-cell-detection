# POC AI Projects

## Malaria Cell Detection (CNN, Computer Vision)

Dataset used: [Malaria cell images kaggle dataset](https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria) 

Total 27560 images are divided into,
- Train infected (parasitized) images - 12480
- Train uninfected images - 12480
- Test infected (parasitized) images - 1300
- Test uninfected images - 1300

Tensorflow ImageDataGenerator's *"flow_from_directory"* function used

Various combination of number of neurons and model depth used with different ImageDataGenerator parameters 

Model saved as h5 file for RGB images as well as Grayscale images

For RGB images accuracy achieved is more than 95% and f1-score is 96% for test set

For Grayscale images accuracy achieved is more than 94% and f1-score is 94% for test set

