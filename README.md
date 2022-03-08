# Live-human-face-expression-augmentation-by-projection
my graduation project is about live human face augmentation by projection mapping by using CNN
our system is composed of three essential stages. The first stage is about using a modified function that uses Blendshape class in unity to take the in- put we got from the CNN model of the blendshapes values in C#. After that we create the dataset by gathering a collection of images and process it. We process the images by making our 3d model mimic the human facial expression in the image. the first phase of dataset processing, is making the 3d model expression natural, the second phase is trying the 74 blendshapes by changing the number of the blendshape from range 0 to 100 to get the best expression of 3d model that match the image, the third phase is saving these blendshapes values into a comma-separated values (CSV) file The second stage is to prepare the dataset for Convolutional Neural Network (CNN) model by resizing it and change the RGB color to the gray-scale image. First, we resize the image to 400×400 by using Keras APIs.Second, we change the RGB color to gray-scale color. The third stage is implementing the Convolutional Neural Network (CNN) model to take an input image and output its blendshapes values . Finally, we take the output and put it in the 3d model in unity 

<img width="492" alt="Screen Shot 2021-10-23 at 5 57 39 PM" src="https://user-images.githubusercontent.com/90938419/138563319-402faf26-e529-4e0d-a10c-5e6da11ae2f9.png">

the full project description in Live human face expression augmentation by projection1.pdf

ps: here are the bset weights i get it from cnn
https://drive.google.com/f

© 2021 Mohanad Gad.  All rights reserved.
